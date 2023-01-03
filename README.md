# Real Python snakesay
RealPython code conversation about packaging with pyproject.toml

https://www.youtube.com/watch?v=v6tALyc4C10

## Editable install
Clone the repo. Navigate to rp-snakesay dir. Run the following command.

```python -m pip install -e snakesay```

This will point the installation to cloned source files. Changes to the source files will take effect in the install.

## Command line arg
We add a project.scripts header to the TOML file to create a command line arg. We use a different command 'snakey' to demonstrate that the command doesn't have to be the same as the package name.