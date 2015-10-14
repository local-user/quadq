# quad-q
####a BASH flat file job queue script



###usage

quadq [add|clone|delete|edit|finish|flush|help|list|quadq|read|restart|start] option

quadq example usage:

- quadq add 'ls -lah /'
- quadq clone 1444801649672551
- quadq delete 1444801649672551
- quadq edit 1444801649672551
- quadq flush
- quadq help
- quadq list
- quadq quadq
- quadq read
- quadq restart
- quadq start



###extra


#####matching jobid

To select a job you only require a unique portion of the jobib.

- quadq read 1444801649672551
- quadq read 2551
