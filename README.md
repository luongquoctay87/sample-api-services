
### Getting started
1. Maven Build All Services
    ```
    $ mvn verify
    ```

2. Docker Build Images & Run Container
    ```
    $ docker-compose up -d --build
    ```
   
3. Update code and rerun
   ```
    $ mvn -pl [service-name], [other-services] -am clean install
    $ docker-compose up -d --build [service-name]
   ```
4. Test
   ```
   $ curl --location --request POST http://localhost:80/api/v1/auth/login --header Authorization:Basic b2F1dGgyQ2xpZW50Om9hdXRoMlNlY3JldA== --header Content-Type:application/x-www-form-urlencoded --data-urlencode username=sysadmin --data-urlencode password=password
   ```