This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Local Development

Requires first to setup and run [booktonica-api](https://github.com/Techtonica/booktonica-api)

`heroku local`

## Heroku Deployment

- Deploy the api app above and use this app's Heroku URL in its config (for CORS)
- `heroku config:set REACT_APP_API_URL=https://booktonica-api.herokuapp.com` but replace with your API server


