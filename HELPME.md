1. Docker:
- image-> grafana/grafana:latest
- port-> 3000:3000
- http://localhost:3000

user:admin
password:admin

2. Docker:
- image-> prom/prometheus:latest
- port-> 9090:9090
- http://localhost:9090

3. How to run:
   + Application run as debug
   - gradle build -x test
   - in git bash ./gradlew build -x test
   - 
4. http://localhost:8080/hello



