# DREAM STREAM

Dream Stream is an image sharing platform where users can create accounts and upload tagged images. Users can also filter for specific content using the tag system called streams. Additionally, users can follow new streams. 

The project is built using the JAMstack which means that it does not have a traditional backend but instead utilizes serverless functions that lives in the cloud.

This project was built by Mob The Builders as a final project for `<salt/>`. 

[Try it here](https://dream-stream.netlify.app/)

> Serverless Full Stack App

- Written in: 
  - Gatsby with React 
  - Netlify for the serverless functions 
  - Fauna as a serverless database


![Main view](/assets/dream-stream.png "Main View") 

 #### Features implemented

- Log in Page - Sign up new user - Logout
- Make a Post - Comment on Post - Like a Post - Delete a Post
- Profile: sort by - Posts created by the user / Posts liked
- Streams: (un)/follow streams


#### Features for next version

- Confirmation when deleting Post

## Run App

#### Install Dependencies

```
- npm install netlify-cli -g
- yarn install
- Add Fauna key to .env
```

#### Run in dev

```
# Run in dev mode 
netlify dev
```

- Version 1.0

- License: MIT