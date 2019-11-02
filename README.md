# This README contains information regarding running nginx + react configuration.

This is a clean create-react-app with nginx and docker as contianer for both of them. This was created in need of making sure the config was allright and couldn't find an example anywhere.
Docekr exposes react-app through nginx on port 80 and 443, so after running just go to http://localhost and you'll be presented with react starting page.


To run just use command:

```
docker-compose build --no-cache && docker-compose up
```
