restore database "`cat mydatabase_backup.sql| docker exec -i tapcoDB_postgres psql -U aivd tapco_new_db` "