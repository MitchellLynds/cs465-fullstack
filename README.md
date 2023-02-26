# cs465-fullstack
CS-465 Full Stack Development with MEAN
Architecture
Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

The Express static site uses HTML views and handlebars templates to generate HTML which is served to the user's browser. The interaction with the Express HTML page is handled by controllers in order to provide the requested HTML. The Angular project on the other hand, supplies HTML components, along with typescript functions and data services in order to access the database and generate the requested HTML in-browser.


Why did the backend use a NoSQL MongoDB database?

The backend uses MongDB for three primary reasons. The first two reasons are that MongoDB is fast and easily scalable. The third reason is that MongoDB stores information in BSON format, which can easily be converted to JSON and integrated into our other JavaScript based tools easily.

Functionality
How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

While Javascript is a programming language often used in web development JSON is just a file format type. The "JavaScript" in "JavaScript Object Notation" comes from the fact that JSON utilizes JavaScript syntax. JSON is used to tie together the front end as the chosen format for data that needs to be transferred from the DB to the frontend.

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

  A specific instance where the code was refactored was the replacement of large portions of the static site HTML with Handlebars templates. This has significant benefits for reusability because it is much more readable and the individual components are separated into files that can be imported. Another benefit comes when it is necessary to make additional changes to the HTML; A single template can be modified rather than changing every individual instance of that component.

Testing
Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

In a full stack application Http methods such as GET, POST, PUT and DELETE are used in combination with the API endpoints. API endpoints are URL's that allow the frontend to interact with the backend. It is important to think about and test for security when developing full stack applications to ensure that the methods and endpoints don't give a malicious user the ability to modify or access data in unintended ways.

Reflection
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course will help me in reaching professional goals because there is a lot of demand in the job market for full-stack developers. The biggest skill that I  learned in this course was about how API's work and how to develop and implement one to meet the goals of a project. 
