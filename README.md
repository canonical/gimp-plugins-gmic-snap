# G'MIC-Qt for GIMP Snap

This is a content producer snap providing G'MIC-Qt plugins for the GIMP snap.

To integrate the plugins with the GIMP snap, first install the snap from the Snap Store or from the command line:

```shell
sudo snap install gimp-plugins-gmic
```

Then connect the plugins to the GIMP snap:

```shell
sudo snap connect gimp:gimp-plugins gimp-plugins-gmic:gimp-plugins
```
