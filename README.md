# DVSA Digital Service Portfolio

[Take a look](http://dvsa-digital-services.herokuapp.com/)

[Big Screen view](http://dvsa-digital-services.herokuapp.com/)

to start: ```nodemon server.js```

http://localhost:3100

To add new project:

 - duplicate a project config json file in ```lib/projects``` and name accordingly
 - add relevant data
 - assign relevant "theme", eg, MOT, CVS, VOl etc If a new one is required, add it in ```app/routes.js``` to ```var theme_order```
 - increment ```id``` in project config file        
