# Recurring-pgdump
An example of running recurring pg_dump inside a container

### Environment Variables

 * PGHOST - Hostname or ip address of psql host.
 * PGPORT - port 
 * PGUSER - database user account to use
 * PGPASSWORD - the password for the PGUSER database user that is created
 * PGDB - a database that needs to be backup
 * BKPTIME - hour of day at which backup should run

### Mount

The mount point where the data will be dumped.
 ``/var/lib/pgsql/data`` 
  
