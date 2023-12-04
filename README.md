# votingappkubernetes
A microservice application that uses python , redis , .net , node,js , postgresql.

![image](https://github.com/Diwakar-hub123/votingappkubernetes/assets/83933859/3257be3a-a5b5-4551-85c6-e759c48ba2ff)

A front-end web app in Python or ASP.NET Core which lets you vote between two options
A Redis or NATS queue which collects new votes
A .NET Core, Java or .NET Core 2.1 worker which consumes votes and stores them in…
A Postgres or TiDB database backed by a Docker volume
A Node.js or ASP.NET Core SignalR webapp which shows the results of the voting in real time
Note
The voting application only accepts one vote per client. It does not register votes if a vote has already been submitted from a client.
