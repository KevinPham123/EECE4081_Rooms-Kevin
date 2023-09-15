# EECE4081_Rooms 

Background:
EECE4081_SoftwareEngineering CRUD project with a team of 4: Ashton Hill (Developer), Nicholas Gilchrist (Developer), Kevin Pham (Developer), and Professor Ahmed (Scrum Master).
Followed scrum methodology with 2 weeks sprints and used Trello for tracking user stories.

This project has the following endpoints exposed:
GET: /about
-goes to the page about the developers of the project and their contact information
![About](https://github.com/KevinPham123/EECE4081_Rooms-Kevin/assets/54450659/5c1d7dd9-f1d2-4820-9168-c428d3308ee8)

GET: /create
-navigates to the create page
![CreateRoom](https://github.com/KevinPham123/EECE4081_Rooms-Kevin/assets/54450659/c93ff309-9bf6-4129-ab86-7550e688d6aa)

POST: /create
-updates the db accordingly
![AfterCreateRoom](https://github.com/KevinPham123/EECE4081_Rooms-Kevin/assets/54450659/a94cbc0f-cf64-47c2-b925-586e1e6cf78c)

GET: /
-reads the db and shows the values
![ReadRoom](https://github.com/KevinPham123/EECE4081_Rooms-Kevin/assets/54450659/46ff6737-b6f2-4e77-a3fe-cb249dc72a43)

GET: /update/<room_id>
-navigates to the update page

POST: /update/<room_id>
-update the existing room in the db
![UpdateRoom](https://github.com/KevinPham123/EECE4081_Rooms-Kevin/assets/54450659/64cf852f-b62d-4238-8f58-7bad8d885970)

DELETE: /delete/<room_id>
-modal will appear to check confirmation on delete, then if confirmed deletes the existing room by id in the db,
![DeleteRoomConfirmationModal](https://github.com/KevinPham123/EECE4081_Rooms-Kevin/assets/54450659/efd9ef0e-f236-4d03-bd1d-ac718f89d7f2)

![AfterDeleteRoomSuccess](https://github.com/KevinPham123/EECE4081_Rooms-Kevin/assets/54450659/bd429a5b-590d-4cc4-a8c9-f7c6f7a01944)


Techstack: Python, Flask, SQLAlchemy, HTML, CSS
