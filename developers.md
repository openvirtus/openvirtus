## Dear developer, do not be shy

Most developers think that their scripts are unshareable, because of the
following points:

1.- The script/library has only been **tested in a certain situation**. Let's
    say you only tested it in Ubuntu.

2.- The script/library is very **specific for a task**.

3.- The script/library is **bound to a project**, for instance to some DevOps
    operation.

4.- The script/library is **poorly written**.

5.- The script/library project has no internal mission statement, you bundled
    code there. For example a saras-scripts or libcsara.

We think that this points can be overcomed and make a shareable product out of
them. Contact us and we'll tell you how. Maybe someone can benefit from your
messy code. It's also a good way to improve your [virtus](https://en.wikipedia.org/wiki/Virtus).

## Coding style for shell scripts

We want the cripts to follow the following template:

    #!/bin/sh -e
    
    #l: Use always -e so that the execution fails on error.
    #l: Put the license here.
    
    #h: Usage: $0 ...
    #h:
    #h: Put the help here.
    
    . dependency-script1 # Source the script you depend on so that you will
    . dependency-script2 # be able to build bundles.
    
    your_script_name() {
    
        # Parse options with getopt.
        while getopts "v" optopt;do
            local ops="${ops}${optopt}"
            case $optopt in
                # Get options with parameters here.
                \?) return 1;;
            esac
        done
        shift $(( $OPTIND - 1 ))
        
        # Print variables with -v
        case "${ops}" in *v*) your_script_name_show_variables;; esac
    }
    
    your_script_name_show_variables() { # Show variables.
        printf '%-20s : %s\n' VARIABLE "${VARIABLE}"
    }
    your_script_name_calc_variables() { # Calculate variables.
        VARIABLE="${VARIABLE:-123}"
    }
    
    your_script_name_calc_variables
    if test @"`basename "$0"`" = @"your-script-name";then
        if test -n "$1";then
            your_script_name "$@"
        else
            sed -n 's/^ *#h: \{0,1\}//p' "$0" | sed "s|\\\$0|`basename $0`|g"
            echo ""
            sed -n 's/^ *#l: \{0,2\}//p' "$0"
        fi
    fi




