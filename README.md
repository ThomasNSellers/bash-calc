# bash-calc
Runs calc command when you enter a mathematical expression into the terminal

Forked from https://github.com/hkbakke/bash-insulter for the logic to change logic when invalid command is inputed.

```bash
tom@TomsLaptop $ 10+15
	25
tom@TomsLaptop $ whoami
tom
```

# Compatibility
* Bash v4 and newer

# Installation

    git clone https://github.com/ThomasNSellers/bash-calc.git bash-calc
    sudo cp bash-calc/src/bash.calc /etc/

Edit your ~/.bashrc and add this to it
```
if [ -f /etc/bash.calc ]; then
    . /etc/bash.calc
fi

```
Relog, or exit and reopen your terminal and it should work.
