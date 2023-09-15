 # Background:
EECE4081_SoftwareEngineering CRUD project with a team of 4: Ashton Hill (Developer), Nicholas Gilchrist (Developer), Kevin Pham (Developer), and Professor Ahmed (Scrum Master).
We followed scrum methodology with 2 weeks sprints and used Trello for tracking user stories.

### Endpoints 

|HTTP Method|URL|Description|Preview|
|---|---|---|---|
|`GET`|http://127.0.0.1:5000/         | Read Rooms page | |
|`GET`|http://127.0.0.1:5000/about    | About Us page | |
|`GET`|http://127.0.0.1:5000/create   | Create Rooms page | |
|`GET`|http://127.0.0.1:5000/update   | Update Rooms page | |

#### User Service

|HTTP Method|URL|Description|
|---|---|---|
|`POST`|http://127.0.0.1:5000/create/{room_id}   | Creates a new room |
|`POST`|http://127.0.0.1:5000/update/{room_id}   | Updates a room by ID |
|`DELETE`|http://127.0.0.1:5000/delete/{room_id} | Deletes a room by ID |
|`GET`|http://127.0.0.1:5000/init_db             | Clears the db of all values |


Techstack: Python, Flask, SQLAlchemy, HTML, CSS
