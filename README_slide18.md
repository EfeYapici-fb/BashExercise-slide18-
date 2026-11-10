# Bash Exercise - Slide 18

`env_install.sh` installs Python, pip and Jupyter Notebook. It works on macOS and Linux.

## What it does

- Detects the operating system (`$OSTYPE`)
- Checks if Python and pip are installed, installs them if not
- Installs Jupyter Notebook
- Prints clear messages with a `pretty_print` function

## How to run

```bash
chmod +x env_install.sh
./env_install.sh
```
