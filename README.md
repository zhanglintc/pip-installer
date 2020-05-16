# pip-installer
install pip handy

-----

Use the one-line script below:

curl:
``` Shell
# pip
sh -c "curl https://raw.githubusercontent.com/zhanglintc/pip-installer/master/get-pip.py | if [ "$(id -u)" = "0" ]; then sudo python; else python; fi"

# pip3
sh -c "curl https://raw.githubusercontent.com/zhanglintc/pip-installer/master/get-pip.py | if [ "$(id -u)" = "0" ]; then sudo python3; else python3; fi"
```

