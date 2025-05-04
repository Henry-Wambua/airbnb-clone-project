"About the project"

This is project is developed to simulate real world application of a robust booking system just like AirBnB. It encompasess backend systems, database design, Modern and efficient API dvelopments and the appplication security. 
The sets of technologies stacked together to build the entire booking system include:
  1.Django
  2.REST API
  3.GraphQL
  4.Docker


"Team Roles"
1. _Business Analyst_: Bridges the gap between the stakeholders of the product and the development team. BA transalates the stakeholders' needs into requirements that the development team can work on.

2. _Product Owners_: Takes the responsiblity of the product's success. Definifion of the business strategy that shapes up the product vision all lies on their hands.

3. _Product Manager_: Ensures the success is delivered as desired in due time and within the designated budget.

4.__ UI/UX Designers__: Maps out the user journey for the best customer experience.

5. _Software Architect_: Lays out the blueprint for the actual development of the prokduct. this ranges from the selection of appropriate tools and platforms to implement the product vision. Also sets out the code standards and performance reviews.

6. _Quality Assurance Engineer_ Ensures that the product developed is in accordance with the set guidlines. responsible to pick out errors or defects.

7. _DevOps Engineer_: Facilitates cooperation between development and operations teams. Creation of Continuos Intergration and Continous Deployment pipelines.
8. _Backend Engineer_: Implementing the core of the product development, that is the infastructure and logic.

9. Frontend Engineer: Developing the interface which the user of the product interacts with.


“Technology Stack”
1. Django: This is a web framework based on the python langauage that assist in building secure and scalable websites much faster.

2. PostgreSQL: An open source database system used to store and query data using SQL

3. GraphQL: A query language for API that uses a type system defined by the developer.

4. Docker: A tool used to package development, testing and deployment tools in standardized units called containers.

5. GitHub Actions: CI/CD platform that allows users to automate, customize and execute software development workflows.

6. MySQL: A relational database management system.


"Database Design"
1. User: Two types of users(Guest and Host). The fields include username, userID, contact info(most probably email), login password.
A user can have multiple listings and bookings.

2. Listing: Name of the property, location of the property, price rate, availability, capacity of accomodation.
A listing can have multiple bookings.

3. Booking: Check In, Check Out, type of accomodation booked, method of payment, total price, time stamp, status of Booking.
Booking links a user with one listing.

4. Review: Comment, rating, listing, timestamp
A review collects information from the user.
Different guest may give multiple reviews to one listing.

5. Payment: Method of payment, currency, payment time stamp, amount paid, property paid for, customer ID.
Payment confirms the booking of a user to a property.


"Feature Breakdown"
1. User/Account Management: Login credentials, profile setup, pasword reset

2. Property Management: Add descriptions, set time availablity, create/edit property listings.

3. Booking System and Browsing: Recommendations, Search listings by name, location, prices, availablity or amenities offered.

4. Payment: Offer secure payment integration via different platforms(e.g debit/credit)

5. Admin Office: Management of listings, users and bookings. Handling of disruptions and complaints. 


"API Security"
1. Authentication and Authorization: Ensures the users with the right pass can access data such as logging into an account to make a booking.

2. Input validation: Scrutinizing user input to prevent entry ofmalicious data

3. Rate limiting and Throtting: Protection from malicious traffic by limiting the number of inputs a user can make in a certain period. An example is allowing only 5 login attempts per minute.

4. Logging and monitoring: Monitoring the frequency of API requests to spot unusual activity such who booked, when was the booking/payment made.


“CI/CD Pipeline”
This is a set of automated processess used in the development of applications to build, test and deploy code changes efficiently and reliable.
1. Github Actions: Used everytime a code change is pushed to Github to automatically run tests, build app and deploy to server.

3. Jenkins: A tool with built in CI/CD to automate building, testing, and deploying code. Also, the developer has full control.

4. Postman: A tool used in testing the functionality of APIs.

5. Docker: An open source platform that allows developers to package their applications and all dependancies in a unit (container) with the aim of consistency across different environments.

6. Kubenetes: An open source platform used for container orchestration.
That is it assist in managing, scaling and autmating the deployment of container applications.   
