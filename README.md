# API-NODE-RED-ELASTICSEARCH-LOCALFILES
## 1) logging data from Weather API using Node-RED into local files and visualizing the same into dashboard
## 2) ingest API Data into elasticsearch service using Node.js & Node-RED 

## Node_RED Flow
![Node-RED Flow](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/16c855a6-8472-45f2-af1b-57a87aa09009)



## elasticsearch deployments
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/07624aa3-77fe-4509-9157-b27bef1e6ae2)

## elasticsearch credentials
![elasticsearch-credentials](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/d9e273f7-324e-4ad2-aaa2-3d48ef564211)


## inject node
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/43113eea-1ef3-4218-a05a-13f0b089f5ee)

## http request node
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/232b22ee-702c-497a-ab8e-093ba5da440a)

## change node - extracting main weather data
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/9f1d5edf-8bed-4424-ad73-2abbe3feeef7)

## function node - adding time stamp to data
![function node - adding time stamp to data](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/d13650d9-91a3-4d2c-b3c0-b2be78a16c99)

## function node - elasticsearch - node.js code to ingest data to elasticsearch service
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/49fb5f86-75f8-4f87-94ae-4d8188aff609)


## debug node to print data into console
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/070cb32e-9f05-48f3-b4cf-f38c5ae7a764)

## file node to save data to text files locally
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/4da4894a-8c7b-48cd-85c2-1b8851d12727)

## change node1 - extract temperature seperately into dashboard
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/10816aa0-3b13-4e81-947b-e86ffb1dbff1)

## change node1 - extract humidity seperately into dashboard
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/8b5c9ac3-056f-4ebc-ace6-edd49675bc00)

## change node1 - extract pressure seperately into dashboard
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/4de41b40-c5d3-43f8-940d-0b5e765e3450)

## change node1 - extract temperature seperately into dashboard
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/295c68ee-a1b6-49fe-a5fd-c77b87312958)

## weather-data dashboard
![image](https://github.com/SuryaMahesh789/API-NODE-RED-ELASTICSEARCH-LOCALFILES/assets/101471548/d343ffd9-fad3-42ee-a194-2a54c57f39b3)
