# Kubernetes project

## Creating a voting app, it has 5 components
1.  Voting app: created in python to input vote.
2. Result app: Created in Node to see the result of votes.
3. Redis server: It will store the vote from voting app.
4. worker: .Net backend to fetch the votes from redis & store it in postgres.
5. postgres server: it stores the votes in category.
