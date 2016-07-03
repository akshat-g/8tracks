# 8tracks
Discovery Logic for Playlists based on the tags.

How to Run
---------------
1) unzip the downloaded file and cd into the main directory.

2) create the virtual environment using command - virtualenv <name of the environment> 

3) Activate the virtual environment using command - source <name of the environment>/bin/activate

4) Install all the required packages by running command - pip install -r requirements.txt

5) 






Detail of any PlayList can also be viewed via URL - http://localhost:8000/api/playlists/playlists/<playlist_id>/ where playlist_id can be unique id of any playlist in the system. 

For ex - http://localhost:8000/api/playlists/playlists/1/  returned on my system - 

HTTP 200 OK
Allow: GET, PUT, PATCH, HEAD, OPTIONS
Content-Type: application/json
Vary: Accept

{
    "playlist_id": 1,
    "playlist_name": "Led Zeppelin",
    "likes": 10,
    "plays": 3
}
