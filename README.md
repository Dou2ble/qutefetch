# qutefetch
A homepage for qutebrowser inspired by neofetch

## Demo
![Shot of qutefetch](.demo.png)

# Install

First download index.html
with wget
```bash
wget https://raw.githubusercontent.com/Dou2ble/qutefetch/main/index.html
```
or with git
```bash
git clone https://github.com/dou2ble/qutefetch
```


When using autoconfig.yml run this command in qutebrowser
```
:set url.start_pages file:///path/to/qutefetch/index.html
```

If you instead are using config.py instead add this line to your config
```py
c.url.start_pages = "file:///path/to/qutefetch/index.html"
```
or
```py
config.set("url.start_pages", "file:///path/to/qutefetch/index.html")
```
