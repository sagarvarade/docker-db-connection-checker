This is to check connection is available to DB or not. <br>

<Pre>
  Supporting now for Mysql,Oracle , Postgres.
  Develop to check on docker 

  Postman collection attached with this repo to check connection.

  Demo request as below :

 POST :  localhost:7070/api/database/check

  {
    "url": "jdbc:mysql://localhost:3306/world?allowPublicKeyRetrieval=true&useSSL=false",
    "username": "root",
    "password": "admin",
    "driverClassName": "org.hibernate.dialect.MySQLDialect"
}
  
</Pre>

