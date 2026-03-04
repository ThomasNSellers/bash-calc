# bash-calc
Runs calc command when you enter a mathmitical expression into the terminal

```bash
tom@TomsLaptop $ 10+15
	25
tom@TomsLaptop $ whoami
tom
```

# Compatibility
* Bash v4 and newer

# Installation

    git clone https://github.com/hkbakke/bash-insulter.git bash-insulter
    sudo cp bash-insulter/src/bash.command-not-found /etc/

Then source the file automatically for new logins by adding the following to `/etc/bash.bashrc` or any of the other locations where you can configure your shell automatically during login:
```
if [ -f /etc/bash.command-not-found ]; then
    . /etc/bash.command-not-found
fi
```
Login again and type some invalid commands for the effects to be visible.

Then source this file before you source the script:
```
if [ -f /etc/bash.calc ]; then
    . /etc/bash.calc
fi

```
