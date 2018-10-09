#Installing

    https://www.linode.com/docs/applications/remote-desktop/install-vnc-on-ubuntu-16-04/

#Unlocking

    Unlock VNC display:  

    vncconfig -display :1 -set BlacklistTimeout=0 -set BlacklistThreshold=1000000
