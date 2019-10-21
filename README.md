# projector
A custom project manager written in python for use with tmux

## Usage
```
usage: projector.py [-h] [-n NAME] [-g [GITHUB]] [-p PATH] [-o] [--no-attach]
                    [--remove-from-disk]
                    {add,a,open,o,connect,c,remove,r,new,n}

positional arguments:
  {add,a,open,o,connect,c,remove,r,new,n}
                        The command to execute

optional arguments:
  -h, --help            show this help message and exit
  -n NAME, --name NAME  The name for the project being removed, added, opened,
                        connected to, or created
  -g [GITHUB], --github [GITHUB]
                        Flag to specify whether project name is from a
                        repository on github
  -p PATH, --path PATH  The path to use with the add and new project commands
  -o, --open            Include this option to automatically open a project
                        that is being added or created
  --no-attach           Tell projector not to attach to tmux session after
                        creation
  --remove-from-disk    Include this option when using the delete command to
                        delete project from the projectsfile and from disk
```
