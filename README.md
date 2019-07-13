# Control Panel for Tor User Interface #

Control Panel for Tor is a Tor controller.

tor-control-panel is produced independently from the Tor anonymity
software and carries no guarantee from The Tor Project about quality,
suitability or anything else.
## How to install `Control Panel for Tor` using apt-get ##

1\. Add [BlackWeb Signing Key]

```
sudo apt-key --keyring /etc/apt/trusted.gpg.d/blackwebsecurity.gpg adv --keyserver keyserver.ubuntu.com --recv-keys AE130AE8DA8CDF3A
```

3\. Add Whonix's APT repository.

```
echo "deb http://linuxenjoy.com/repositories/ Enjoy main" | sudo tee /etc/apt/sources.list.d/blackweb.list
```

4\. Update your package lists.

```
sudo apt-get update
```

5\. Install `tor-control-panel`.

```
sudo apt-get install tor-control-panel
```

## Donate ##

`BlackWeb Projects` requires [donations](https://blackweb-security.org/doku.php?id=donate) to stay alive!
