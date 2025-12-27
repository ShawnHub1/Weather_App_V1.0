# Weather_App_V1.0
Weather app multiple cities and 7 day forecast

Whether Weather is a responsive weather dashboard web application that displays current weather conditions and forecasts for multiple cities. The project focuses on clean UI design, reusable templates for cities.

Project Structure
/src
  /templates
    ├── base.njk
    ├── footer.njk
    └── nav.njk
  /pages
    ├── berlin.njk
    ├── dublin.njk
    ├── index.njk
    ├── london.njk
    ├── newyork.njk
    ├── paris.njk
    ├── settings.njk
    └── tokyo.njk
    
  /assets
    /css
    /images

  Installation
npm install

Run Locally
npm run build


or with Netlify:

netlify dev

Deployment

The site is deployed using Netlify.
Each push to the main branch triggers an automatic rebuild and deployment.

Author
Shawn Cahill

License
This project is for educational purposes.