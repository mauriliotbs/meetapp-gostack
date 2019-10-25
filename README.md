# Meetapp Gostack

Final Project of GoStack (Rocketseat's Bootcamp of NodeJS, React and React Native)  :tada:

The task was to develop a Meetup similar app: Server, Web Application and Android App.

## Instructions

I have three submodules here in github: backend, web and mobile

I used docker, PostgreSQL, VSCode, Reactotron, WSL 2.0. 

___

### Backend

API REST. 

I used Express JS, JWT, Multer, Nodemailer, BCrypt, ...

| Routes | Description |
| --- | --- |
| `GET /schedule` | List all meetups of a specific day. Includes pagination |
| `GET /meetups` | List all meetups of a user |
| `POST /meetups` | Create a new meetup |
| `PUT /meetups` | Update a meetup |
| `DELETE /meetups` | Delete a meetup |
| `GET /attendances` | List all the next attendances of a user |
| `POST /attendances` | Create a new attendance |
| `DELETE /attendances` | Delete an attendance |
| `POST /files` | Upload a new banner/image to be included in a Meetup |
| `POST /sessions` | Create a new session |
| `POST /users` | Create a new user |
| `PUT /users` | Edit user profile |


Commands:
`yarn dev`
`yarn queue`

:loudspeaker: Don't forget to fill .env file 

___

### Web

Responsible to create new user accounts, login users and allow them to create their own Meetups with Description, Title, Banner, Location.


Commands: `yarn start`

___

### Mobile (Android)

Responsible to create new user accounts, login users and allow them to create their own Attendances and list other meetups that they could attend.

 :loudspeaker: Please, consider just ANDROID because I don't have Apple devices to test.
 
 :loudspeaker: For some reason I had to manual link the `react-native-localize` lib 
 
 :loudspeaker: You need to change services/api.js IP to your own Android Emulator or Computer address. I used an USB Android Smartphone.
 
## Thanks

Thanks Diego Fernandes and Rocketseat team for all the support and knowledge that have been given on this Bootcamp.  :cool:
