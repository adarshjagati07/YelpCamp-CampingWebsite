# YelpCamp-CampingWebsite
This is a camping website, I have used MERN(mongodb express and nodejs) Stack to build this. This is a full stack application where you can add, edit, delete and search for your camp-grounds. I have also added Map functionality over here.

## Preview.
![Camping Website](https://github.com/adarshjagati07/YelpCamp-CampingWebsite-/assets/91245532/a68c5db0-834b-4ecb-8b0d-003e3f2f95fb)



## What you'll get
- You can register your campgrounds over here with charges and their images.
- You can add, remote or update your campgrounds.
- List the user with its details.
- Complete authentication is provided here with session tracking.
- You can view and select your campgrounds.
- Only the authenticated user is able to add the campground.
- I have provided map functionality over here, through which you can easily identify the place wherever you want to place your campground.

## Technologies used

- I am using HTML5, CSS3, vanilla javascript and BootStrap library for frontend related stuff.
- For backend I am using NodeJs, Express for server related work and MongoDB for database.

## You can run it locally.
- Install [mongodb](https://www.mongodb.com/).
-  Create a cloudinary account to get an API key and secret code.

```sh
git clone https://github.com/adarshjagati07/YelpCamp-CampingWebsite-.git
cd YelpCamp-CampingWebsite-
npm install
```

Create a .env file (your private information over here) in the root of the project with the following details:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then in your browser go to [localhost:3000](http://localhost:3000/).
(For any other references and error checking at your end, open your developer tools on the other side of browser.)

Hope you like it.
If you visiting over here please star the repo.
