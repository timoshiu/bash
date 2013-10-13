bash env manager
================

Help bash to manager environment varaibles.

1. manage a set of environment variables (a subset of /bin/env for example)
2. set (export), unset, and edit environment variable (emacs for the moment)
3. bash shell code only (no 3rd party tool dependency)

Installation
------------
Just copy this .bash_envs to somewhere in your directory and source it.

Usage
------------
It use bash alias to overload env (which is /usr/bin/env for example)

Usage: env [-h|-e|-E] [env_val_file]
- environments setter function for /usr/bin/env
- each line of the input file support the following syntax:

Flag
- -h           print this help message
- -e           edit env_file environment values
- -E           edit env_file environment variables
- nv_val_file  specify env_file filename, (.env default)

Format: (inside env_val_file)
- ENV      (use exist ENV value)
- ENV=env  (set ENV to value env)
- ENV=     (unset ENV)
- #        (comment)


have fun



