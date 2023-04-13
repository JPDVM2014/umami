#Installing Umami on Unraid

1. Install postgresql from the Community Apps store. Tested working on postgresql12 and postgresql15.

2. If you already have postgresql installed, you will need to create a new database.

3. When installing the Umami template, the database URL has the following format: postgresql://superuser:password@IP_Address:5432/db_name. 
   NOTE: I tried using a non-superuser postgres role, but it caused errors with umami. There may be a way to do it, but I haven't found it.
   
4. At this point, you should be able to reach the Umami webui. Default login is "admin" and "umami". Change your password right after first login.

If you made it this far, you can refer to https://umami.is/docs/getting-started to finish setting up umami.
   
