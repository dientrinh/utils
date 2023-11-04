## Database testing
- TESTING FREE QUERIES: https://extendsclass.com/postgresql-online.html
- Show all tables: SELECT * FROM pg_catalog.pg_tables

## Free database connection: https://uibakery.io/sql-playground
- Host:psql-mock-database-cloud.postgres.database.azure.com
- Userrname:fcflknbqwyvlxneagouvvtlx@psql-mock-database-cloud
- Password:szrykedqsdlmrkndbpokbiit
- Database name:booking1699047614704hbaqomanmroibbgg

 ### Read only free Database
Main database
Hostname: hh-pgsql-public.ebi.ac.uk
Port: 5432
Database: pfmegrnargs
User: reader
Password: NWDMCE5xdipIjRrp
## Free Run Postgre:https://extendsclass.com/postgresql-online.html
### Comment out in DB Vib
### Comment out: <br />
select * from company <br/>
        where age >0 <br/>
               /* and id>1 */ <br/>

### Update without commit
BEGIN; <br/>
UPDATE company SET name = 'dien'<br/>
    WHERE id = 1;<br/>
SELECT * FROM company;<br/>
ROLLBACK;<br/>
               

