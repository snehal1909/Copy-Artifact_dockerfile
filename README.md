# Jenkins JOB to copy Artifcats on to Dockerhost

->docker connection with jenkins ,copy artifacts on docker host

-.->WAR file under the target folder
![warfile](https://user-images.githubusercontent.com/72296999/115152424-9d500780-a08e-11eb-8bd6-045dcba89f27.PNG)


///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
->after build successful transfering file and try to connect to docker host
![connectto docker](https://user-images.githubusercontent.com/72296999/115152213-d0de6200-a08d-11eb-9748-95d84f462880.PNG)


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////
->Before building remove the existing artifacts to avoid overlapping

![webappremove](https://user-images.githubusercontent.com/72296999/115152648-86f67b80-a08f-11eb-9a8d-0884dd64817c.PNG)

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////
-> After build success the WAR file 
![build success](https://user-images.githubusercontent.com/72296999/115152897-d1c4c300-a090-11eb-81ec-c98f440326ac.PNG)
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
WAR file copied under HOME directory......
![warfilecopiedhome](https://user-images.githubusercontent.com/72296999/115152955-17818b80-a091-11eb-8ea5-b9c3c212bb3e.PNG)









