# Create sample python application using flask and mysql Database

##RUN
### Create python envionment and clone repo

### first time build
    docker-compose -f docker-compose.dev.yml up --build

### To up and down services
    docker-compose -f docker-compose.dev.yml up
    docker-compose -f docker-compose.dev.yml down

### Request -Load and display data from data directory
    $ curl -X POST  http://localhost:5000/widgets
    $ curl -X GET  http://localhost:5000/widgets
    
### Web-browser 
http://localhost:8080/ (username:root, host: mysqldb)

http://localhost:5000/initdb (reset db)

### Request -Load and display data from data directory
    $ curl -X POST  http://localhost:5000/widgets
    $ curl -X GET  http://localhost:5000/widgets

http://localhost:5000/widgets (Data display)

