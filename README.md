# UWB_Hackathon2022

This app uses Node.js/Express/MongoDB with Google OAuth20 for authentication and Handlebars/Materialize for design. 

The purpose of this app is to allow users to easily create notes during class and collaborate with other students who also use this app by setting their notes to public. You can also set your notes to private so only yourself will be able to view them. 

# Usage
Install Dependencies:
  - npm i express mongoose connect-mongo express-session express-handlebars dotenv method-override moment morgan passport passport-google-oauth20
  - npm i -D nodemon cross-env
  
Run in Development:
  - npm run dev
  
Run in Production:
  - npm start
  
# Hosted website on the cloud
https://tranquil-bastion-78148.herokuapp.com/ 

# Screenshots
![image](https://user-images.githubusercontent.com/77636982/168485281-3df4e3cf-9a59-466f-989f-17764c3d2558.png)

![image](https://user-images.githubusercontent.com/77636982/168485369-535b9908-2844-4525-a834-5972e4cfd3eb.png)

![image](https://user-images.githubusercontent.com/77636982/168485390-7df2783c-a582-4be6-903e-e84df1e7eb1e.png)

![image](https://user-images.githubusercontent.com/77636982/168485424-2c538597-864e-4cc4-9a2a-32ea1cab096c.png)


# Future Additions

- Add feature that will allow others to suggest changes in public notes from other users.
- Add feature to allow users to save public notes into their own private collection.

# Bugs
- Users with a google account with only a first name cannot login. 
