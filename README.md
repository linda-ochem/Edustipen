# HOW TO START THIS APPLICATION

- Fork and clone this repository to your local machine.
- Import the folder to Visual Studio Code.
- Run `npm install` on the VsCode terminal.
- Run `npm start` to kick-start the local development server.

### You can test its functionality of the endpoint on postman with these steps: 

#### To test the comment endpoint on postman:
- Add this endpoint on postman 'http://localhost:8088/api/comments/' set it as a **GET** request.
- Add the limit you want as an `INTEGER` at the tail of the endpoint.
- Send the request on postman.

when the input is provided and sent, if succesfull, you would recieve a *200* status code to show for it.
The response would be in a *JSON* format showing you the limit you set.

if it is not successful, you will recieve an error message, verify your input (Limit) and try again.

#### To test the post endpoint on postman:
- Add this endpoint on postman 'http://localhost:8088/api/posts/' set it as a **GET** request.
- Add the limit you want as an `INTEGER` at the tail of the endpoint.
- Send the request on postman.

when the input is provided and sent, if succesfull, you would recieve a *200* status code to show for it.
The response would be in a *JSON* format showing you the limit you set.

if it is not successful, you will recieve an error message, verify your input (Limit) and try again.
