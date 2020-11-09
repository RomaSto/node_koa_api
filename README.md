
1. npm install
2. npm install knex@0.13.0 -g
3. 
    ///
    $ psql
    # CREATE DATABASE koa_api;
    # CREATE DATABASE koa_api_test;
    ////
4. knex migrate:latest --env development
5. knex seed:run --env development
6. Sanity check - `npm start`
7. Test - `npm test`


pg port 5432