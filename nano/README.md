# nanorc syntax highlighting files

The config files in nanorc.configs have been taken from this repository [https://github.com/scopatz/nanorc](https://github.com/scopatz/nanorc)

To install the config files you can either follow the directions as given in the original linked repository or manually do something on your own.

Copy the nanorc file to /etc/nanorc
    
    cp /etc/nanorc /etc/nanorc.bk
    cp nanorc /etc/nanorc

Copy the nanorc.config files to /usr/share/nano
    
    cp nanorc/*.nanorc /usr/share/nano/
    chmod 644 /usr/share/nano/*.nanorc

###### Note: This action will overwrite the existing nanorc profiles which are provided from upstream nano
