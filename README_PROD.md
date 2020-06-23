# Production Special Configuration

1) Be sure to setup MongoDB lab with your heroku application
2) When deploying to heroku you'll need the following environment variables:
   
   https://passport-react-jwt-app.herokuapp.com is the name of my app url, feel free to replace that with your heroku url app.
   Be sure to not replace the endpoints like, /auth and /login

   a) CALLBACK_URL : https://passport-react-jwt-app.herokuapp.com/auth
   b) GITHUB_CLIENT_ID : 4186fef936e04d18b1bf
   c) GITHUB_CLIENT_SECRET : 6ffafe00788dc5b9b5b8b19e25a9d4099af286e9
   d) JWT_SECRET : your_jwt_secret
   e) REACT_APP_PROD_URL : https://passport-react-jwt-app.herokuapp.com
   f) REACT_APP_PROD_URL_LOGIN : https://passport-react-jwt-app.herokuapp.com/login
   g) MONGODB_URI : HEROKU_WILL_SET_FOR_YOU_JUST_CONFIRM_YOU_HAVE