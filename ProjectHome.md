This is a very small system designed to run on an OpenSolaris host, that will reach out to multiple machines on a network using rsync and ssh in order to provide backups. After each backup, a set of snapshots are created for the day, month, and year that the backup was completed, and symbolic links are created for each of them.

ExampleUsage