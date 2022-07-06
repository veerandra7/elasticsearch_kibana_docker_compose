### Here is the docker compose yml file to setup elastic search and kibana simply through docker container

#### How to Run:
1. Make Sure you have docker desktop and docker compose installed in your PC
2. Go to the above directory and type "docker-compose <filename.yml> up -d" in the command prompt
3. Your docker images will be downloaded as per the configuration provided in the "yml" file
4. Elastic search and kibana are mapped and connected in the "yml" file with ports 9200 and 5601 respectively
5. After successful download of the containers, check if they are running with "docker ps" command in command prompt
 ![image](https://user-images.githubusercontent.com/74710089/177461234-b2fa378c-800d-4c70-a210-44163c0ab7e0.png)
6. Open the port numbers 9200 and 5601 in your localhost browser. 
7. Kibana UI will be accessible now and we can run all the operations.
 
