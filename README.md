# 30-hills

In order to start the project, it is necessary to execute the npm install command inside the backend folder, which gives an error
MongooseError: The `uri` parameter to `openUri()` must be a string, got "undefined". Make sure the first parameter to `mongoose.connect()` or `mongoose.createConnection()` is a string.
You need to create an .env file and put this in it

PORT=4000
MONGO_URI = mongodb+srv://miximixi:Twistedfate123@mernapp.fqhuwmz.mongodb.net/?retryWrites=true&w=majority


Inside the online-shop-frontend folder, run the npm install command to install the required packages.
And run it with npm start.
