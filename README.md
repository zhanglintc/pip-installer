# pip-installer
install pip handy

-----

Use the one-line script below:

curl:
``` Shell
# pip
sh -c "curl https://raw.githubusercontent.com/zhanglintc/pip-installer/master/get-pip.py | if [ "$(id -u)" = "0" ]; then python; else sudo python; fi"

# pip3
sh -c "curl https://raw.githubusercontent.com/zhanglintc/pip-installer/master/get-pip.py | if [ "$(id -u)" = "0" ]; then python3; else sudo python3; fi"
```

