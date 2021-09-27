# Linux Commands

## ssh public key
`cat ~/.ssh/id_rsa.pub`

## ssh status
`service ssh status`

## ssh restart
`service ssh restart`

## rsync
 
Allows synchronization and transfer between local <-> remote files
* --archive (-a) enable archive mode
* --verbose (-v) show the progress of process
* --compress (-z) compress the data in the transference
* --rsh=COMMAND (-e) specify the remote shell to use
* --exclude=PATTERN exclude the files/dir matching PATTERN
  
`rsync -avz -e 'ssh' /source/folder/ root@ip:/destination/folder --exclude file/dir`

## scp

Secure copy

`scp /source/folder/ root@ip:/destination/folder`

## tree
-L Descend only level directories deep

`tree -L number`

## curl
`curl ifconfig.me` show ip

## Screencast
Setting max time `gsettings set org.gnome.settings-daemon.plugins.media-keys max-screencast-length 60`

`ctrl+alt+mayus+r`
