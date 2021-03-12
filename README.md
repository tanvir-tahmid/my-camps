# my-camps 
### A website for creating and reviewing campsites around the world 

### MyCamps has everything you would expect from a full-fledged website (Authorization, Authentication, Image Upload, Maps & More) 
# View Demo: 
https://sleepy-anchorage-84048.herokuapp.com/

## Note:
### MyCamps uses Cloudinary for Image Storage and Mapbox for showing Maps

# Some Features Include:
* Users can create, edit, remove and review campgrounds
* Users can login and register accounts
* Users can search campground by name or location

# To Run:
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
cd my-camps
npm install
```

Create a .env file on the root folder and add the following:

```
CLOUDINARY_CLOUD_NAME=<name>
CLOUDINARY_KEY=<key>
CLOUDINARY_SECRET=<secret>
MAPBOX_TOKEN=<token>
DB_URL=<url>
```

Run ```node app.js``` in the terminal

Open your browser and head to localhost:3000

Done
