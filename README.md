Problem connecting to VNC server in ubuntu from Windows

Problem Description:
Unable to connect to VNC Server using your chosen security setting. Either upgrade VNC Server to a more recent version from RealVNC, or select a weaker level of encryption.

Resolution:
gsettings set org.gnome.Vino require-encryption false

or

dconf write /desktop/gnome/remote-access/require-encryption false
