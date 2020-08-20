# Prabhakar_FindShortestPath_Discovery

Application: ShortestDistancePath
Purpose : to find out the distance between any two planets (source and distance)
========================================================================================

Package Structure
---------------------
za.co.prabhakar.algorithm --> Dijkstra algorithm to find out shortest path
za.co.prabhakarcontroller --> Rest Controller for import the file and 
					to load the UI and deligate the request to the service and repository.
za.co.prabhakar.service --> Service classes.
za.co.prabhakar.repositoy --> repository classes 
						and CRUD operational methods for graph domain object.
za.co.prabhakar.entity --> entities classes.

------------------

Application Port 
--------------------

application start with 8888 port 

Frontend pages
-----------------
html files place under the resources/templates

index.html
result.html

to start the application 
--------------------------
Application .java ---> starting point of the service 
run this class to read the graph file and persist with H2 Database on application start up.
so that data is ready after start up.

URLs to the load the UI page 
-----------------------------
http://localhost:8888/ --> it loads the frondend page where you can select source and destination planet


how run the application.
---------------------------

mvn clean install 
run as java application from Application.java 
http://localhost:8888/  

