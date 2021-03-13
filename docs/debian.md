# Debian install

There is a .deb package in the Releases you can install with APT using

```
sudo apt install ./yabt-version.deb
```

After installing, run

```
cat /opt/yazt/etc/templates/rcs/bashrc >> ~/.bashrc
```

This inputs the Yazt RC to your zshrc if you have one.  
If you don't have bash, don't worry -- it comes as a depend.
