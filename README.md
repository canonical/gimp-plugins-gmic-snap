# G'MIC-Qt for GIMP Snap

[![Get it from the Snap Store](https://snapcraft.io/en/light/install.svg)](https://snapcraft.io/gimp-plugins-gmic)

This is a content producer snap providing G'MIC-Qt plugins for the GIMP snap.

To integrate the plugins with the GIMP snap, first install the snap from the Snap Store or from the command line:

```shell
sudo snap install gimp-plugins-gmic
```

Then connect the plugins to the GIMP snap:

```shell
sudo snap connect gimp:gimp-plugins gimp-plugins-gmic:gimp-plugins
```
