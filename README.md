 # Background:
EECE4081_SoftwareEngineering CRUD project with a team of 4: Ashton Hill (Developer), Nicholas Gilchrist (Developer), Kevin Pham (Developer), and Professor Ahmed (Scrum Master).
We followed scrum methodology with 2 weeks sprints and used Trello for tracking user stories.

### Endpoints 

|HTTP Method|URL|Description|Preview|
|---|---|---|---|
|`GET`|http://127.0.0.1:5000/         | Read Rooms page | ![](/static/images/ReadRoom.JPG) |
|`GET`|http://127.0.0.1:5000/about    | About Us page | ![](/static/images/About.JPG) |
|`GET`|http://127.0.0.1:5000/create   | Create Rooms page | ![](/static/images/CreateRoom.JPG) |
|`GET`|http://127.0.0.1:5000/update   | Update Rooms page | ![](/static/images/UpdateRoom.JPG) |
-------------------------------------------------
#### User Service

|HTTP Method|URL|Description|Preview|
|---|---|---|---|
|`POST`|http://127.0.0.1:5000/create/{room_id}   | Creates a new room          | ![](/static/images/AfterCreateRoom.JPG) |
|`POST`|http://127.0.0.1:5000/update/{room_id}   | Updates a room by ID        | ![](/static/images/AfterUpdateRoom.JPG) |
|`DELETE`|http://127.0.0.1:5000/delete/{room_id} | Deletes a room by ID        | ![](/static/images/AfterDeleteRoomSuccess.JPG) |
|`GET`|http://127.0.0.1:5000/init_db             | Clears the db of all values | ![](/static/images/DBinit.JPG) |

-------------------------------------------------

`Please note:DELETE endpoint will ask a confirmation before deleting as shown below.`
![](/static/images/DeleteRoomConfirmationModal.JPG)




Techstack: Python, Flask, SQLAlchemy, HTML, CSS

`Note this is a refactor of an old project: https://github.com/ahmed217/EECE4081_Rooms/tree/Kevin`
