# hs-tcp-server

Technology stack used 
1) Java 8
2) Spring Boot
3) Maven

Supported features are
1) select * from actors
2) select <column name separated by comma> from actors
Ex, select id,name from actors
3) select * from <table> where <column><space><operator><space><user value>
Ex. select * from actors where age > 16
4) THe entire code supports only actors.csv 

Not Supported
1) Query ending with semi colon - ;
2) Multi line queris.
3) Not generic for the different csvs other than actors.  
