# Broadcast_App
The Application allows multiple people to collaborate on a single topic.
The Application lets the user create a Profile using three credentials. i.e., Username, E-mail, and Password.
The Application then uses bcrypt to encrpyt ur password with 10 rounds of salt hash.
The Application stores ur credentials on MongoDb Atlas using mongoose.
![image](https://github.com/Rathode117/Broadcast_App/assets/112964733/c2d600b4-fa4e-4531-810a-9e7c696674d4)
As you can see even the DBA can't see the passwords.
After successful login, the user is redirected to the chat page.
![image](https://github.com/Rathode117/Broadcast_App/assets/112964733/27b54fd7-1575-4213-a98d-df471188331e)
All the currently logged in users can chat here.
![image](https://github.com/Rathode117/Broadcast_App/assets/112964733/010f6023-e57a-4e3c-9b44-4774772f171a)


How to Run:
1. You need to have MongoDB account for this, create it here - https://www.mongodb.com/
2. Then u need to link your DataBase to the Application.
3. Create a .env file in the root directory of the application folder.
4. The .env file should contain your MongoDB connect URL.(obtained from the network section of MongoDb).
5. Install the required dependencies using the command -   npm install
6. Run the index.js file using the command -    node .\index.js




