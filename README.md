# fabric2
Network for 2.0 version of fabric


The zip files includes a docker-compose-e2e.yaml file whcich starts all the docker conatiner of two Organisation with 2 peer each

It also has a crypto-config.yaml which contains network topology

It has joinchannel.sh file which creates a channel block and joins two peer in it.

It has generate_test.sh file which create the genesis block a channel file and achor peer updation of two peers

It has configtx.yaml file which has channel policy and orderer related configuration

The Commands.txt file has all the method in chronological order in which these command should be executed to deploy a chaincode in two peers

