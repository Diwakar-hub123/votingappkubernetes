# votingappkubernetes
A microservice application that uses python , redis , .net , node,js , postgresql.

![image](https://github.com/Diwakar-hub123/votingappkubernetes/assets/83933859/3257be3a-a5b5-4551-85c6-e759c48ba2ff)

## Project Overview

- Front-end web app in Python or ASP.NET Core allowing users to vote between two options.
- Utilizes a Redis or NATS queue to collect and manage new votes.
- Worker application in .NET Core, Java, or .NET Core 2.1 processes and stores votes.
- Data storage handled by a Postgres or TiDB database, backed by a Docker volume.

## Real-Time Results

- Node.js or ASP.NET Core SignalR web app displays voting results in real-time.

## Voting Restrictions

- Application only allows one vote per client.
- Votes are not registered if a client has already submitted a vote.

## Components

1. **Front-end Web App**
   - Developed in Python or ASP.NET Core.

2. **Message Queue**
   - Uses Redis or NATS to collect and manage votes.

3. **Worker Application**
   - Written in .NET Core, Java, or .NET Core 2.1.
   - Consumes votes and stores them in the database.

4. **Database**
   - Postgres or TiDB.
   - Docker volume for data persistence.

5. **Real-Time Display**
   - Node.js or ASP.NET Core SignalR web app for real-time voting results.

## Voting Rules

- Enforces a one-vote-per-client policy.
- Rejects votes from clients that have already submitted a vote.

<img width="939" alt="image" src="https://github.com/Diwakar-hub123/votingappkubernetes/assets/83933859/c0bc0149-71b0-4039-90e9-b61f73d537af">

<img width="767" alt="image" src="https://github.com/Diwakar-hub123/votingappkubernetes/assets/83933859/513853f2-bb3e-4520-a177-12aa7da2cec1">



Reference:
https://github.com/kodekloudhub/example-voting-app/tree/master

