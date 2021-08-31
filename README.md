# Linux Commands

## rsync
 
Allows synchronization and transfer between local <-> remote files
--archive (-a) enable archive mode
--verbose (-v) show the progress of process
--compress (-z) compress the data in the transference
--rsh=COMMAND (-e) specify the remote shell to use
--exclude=PATTERN exclude the files/dir matching PATTERN
  
`rsync -avz -e 'ssh' /home/epc91/dev2021/seleniumCheck/ root:185.70.198.174:/root --exclude env`
