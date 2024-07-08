1. Node version -

v12.22.12

2. yarn --version  -

1.22.19

3. docker version -

Docker version 24.0.5, build ced0996

4. docker-compose version -

docker-compose version 1.29.2, build 5becea4c

--------------------------------------------------------------
To run graphnode -
1. cd docker
2. nano docker-compose.yml
3. change rpc endpoints
4. Run below line
5. sudo docker-coompose up

-----------------------------------------------------------------
To run subgraph / deploy subgraph - 

Change factory address from everywhere to your used factory address of the chain.

1. To install dependecy run "yarn" in subgraph folder.
2. yarn codegen
3. yarn build
4. yarn create-local
5. yarn deploy-local
