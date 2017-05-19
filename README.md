# Development Docker environment
- [./docker-compose.yaml](docker-compose.yaml)
- [./Makefile](Makefile)

```
$ make

Development Docker compose console

frontend                     - Starts frontend
frontend.console             - Frontend console
frontend.build               - Frontend build
backend                      - Starts backend
backend.console              - Starts backend console
backend.build                - Backend build
redis.console                - Redis console
mongo.console                - MongoDB console
ps                           - List of processes
stop                         - Stop all processes
kill                         - Kill current processes
kill.all                     - Kill all docker processes

```