# Full Stack Web App - SNHU CS465

## Architecture

The different types of frontend development used in this project include Express, HTML, Javascript, and the single page application (SPA). HTML is the 
groundwork for the site. The majority of websites use HTML to create a layout for where different containers, buttons, text, etc. go. CSS is used along with
it to make the stylization of certain elements easier through compartmentalizing them into classes that can be applied to the HTML tags. JavaScript is then 
used to code functionality into different sections of the site, such as submitting a form through a button click. Submitting the form with its entire 
functionality like using the form to update an element would require a working API system, which is where Express JS comes in. It is a Node JS framework
that is designed to integrate that backend functionality. The single page application is used for the admin view of the site. SPAs differ from most other
websites where each page is a different HTML file separately. Instead, an SPA will just rewrite the current HTML of the one page. The backend of this site 
uses a NoSQL MongoDB database because it uses JSON-like documents to interact with data which fits well with the other JavaScript components of the MEAN
stack (MongoDB, Express, Angular, NodeJS). 

## Functionality 

JavaScript is different from JSON since JavaScript is a programming language, and JSON is a data format that is derived from JS. JSON ties together the 
frontend and backend development pieces since the data in this site is stored as JSON objects that then get formatted and displayed on the frontend.
An instance in the full stack process when I refactored code to improve functionality and efficiencies would be when the admin SPA was refactored
to include login/security functionality. Reusable UI components are beneficial for the site since that was how the site cards were integrated in the 
front and backend pages. That way the cards did not have to be hard-coded into the app and could be rendered dynamically just from the format of the card
and the contents of the data. 

## Testing

The common methods for request and retrieval in API testing include GET, PUT, POST, and DELETE. POST creates new resources (like adding a trip card in this 
site example), GET retrieves those resources to display them on a page, PUT updates existing information, and DELETE deletes information. The API endpoints
are tied to certain URLS of the site. An example of testing done for the API of site would include using a GET method on a page like /api/list-trips to 
retrieve the trips data. Security was added to the site which made it so that certain methods could only be done by an authenticated, logged-in user, such
as adding or editing trips. 

## Reflection

This course has helped me in reaching my professional goals since it is another full stack web app which I have created, though this time with a different 
stack. Last time I used React and MySQL instead of Angular and MongoDB. A skill I have learned would be how to create a single page application that rewrites
itself instead of linking different pages together. 
