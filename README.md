dojo-basic-docker
=================

This is a simple wrapper for dojo-basic to make it easier to clone and stand-up with docker-compose.

For the moment a few manual steps remain:
 - Copying the database credentials (including hostname of "db") into dojo-basic's config.inc file.
 - Once the environment is up, navigating to /reset_db.php to initialize the DB.

**Also note that the ports are mapped 30080 and 30443 on localhost.**
SSL config is completely untested at this time.
