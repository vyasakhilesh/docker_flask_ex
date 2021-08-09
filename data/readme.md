##RUN
### Initial
    docker-compose -f docker-compose.dev.yml up --build
### After first start
    docker-compose -f docker-compose.dev.yml up
    docker-compose -f docker-compose.dev.yml down
### Request -Load data from data directory
    $ curl -X GET  http://localhost:5000/widgets
    $ curl -X POST  http://localhost:5000/widgets
### Web-browser 
    http://localhost:8080/ (username:root, host: mysqldb)
    http://localhost:5000/widgets (Data display)

