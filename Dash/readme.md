With Docker :
1- pull the image from DockerHub :
docker pull samiadata/itinerary_dash:1.2.0
2- run the container :
docker run -p 8050:8050 samiadata/itinerary_dash:1.2.0
3- go to :
`http://localhost:8050`

Without Docker (Python need to be installed on your machine) :
1- dowload the Dash folder on your machine 
2 - Install the requirements:
`pip install -r requirements.txt`
3 - from the Dash folder, launch the app:
'python3 app.py' 
5- go to :
`http://localhost:8050`


