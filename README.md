# Internsctl
NAME
       internsctl - System information and user management tool

SYNOPSIS
       internsctl [options] <command>

DESCRIPTION
       internsctl is a command-line tool for retrieving system information and
       performing user management tasks.

OPTIONS
       --help
              Show help message.

       --version
              Show version information.

COMMANDS
       ls
              List available commands.

       cpu getinfo
              Display CPU information.

       memory getinfo
              Display memory information.

       user create <username>
              Create a new user.

       user list [--sudo-only]
              List users, optionally limited to sudo users.

       file getinfo [options] <file-name>
              Get information about a file.

       File Information Options:
              --size, -s
                     Print file size.

              --permissions, -p
                     Print file permissions.

              --owner, -o
                     Print file owner.

              --last-modified, -m
                     Print last modified time.

EXAMPLES
       internsctl cpu getinfo
              Retrieve CPU information.

       internsctl user create johndoe
              Create a new user 'tushar'.
