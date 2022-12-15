We're going to use the OMDB API as our source for movies. This API is free to use, and all we have to do is sign up and get an API key.

How to Get an API Key
Go to http://www.omdbapi.com/apikey.aspx and fill out the form. You should receive an email like this

![Alt text](https://www.freecodecamp.org/news/content/images/2020/11/Screenshot-2020-11-10-at-07.37.11.png)

Click the activation link (highlighted in green) and you're good to go. Woohoo!

Exploring the API with PostMan
This is an optional step, so if you'd rather get into the React-y goodness feel free to jump to the next section.

We're going to use Postman (download if here if you haven't got it) to play with the API.

Fire up Postman and paste in the "OMBb API" URL you received in your email (highlighted in yellow in the image above). Click "send" and you should get some JSON back in the "body" section like so:

![Alt text](https://www.freecodecamp.org/news/content/images/size/w1600/2020/11/Screenshot-2020-11-10-at-07.53.58.png)

This means our URL from the email is working fine and our React App will be able to retrieve movies.