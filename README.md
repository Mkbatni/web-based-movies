##Link
https://www.youtube.com/watch?v=WDYv89tG9js

------------------------------------------------

Fabflix is a full-stack, end-to-end web-database application. Users use the website to search through movies, stars, and genres in order to buy the movies they want. A team of two other students and I built the application from scratch over ten weeks. Every other week we had to create a mini-project, each one building off the last and adding more features to the website. The main technologies used were Java, MySQL, Apache Tomcat and ec2-ubuntu instances hosted through Amazon Web Services. I created the servlets and the majority of the code that dealt with the database. One team member did most of the front-end work, creating the JSP pages and designing the look of the website. The other’s job was setting up the AWS instances and taking care of the production side of the project.

The first project involved creating a MySQL database with provided movie info, writing a Java program to connect to and interact with the database using JDBC, and setting up Apache Tomcat to deploy the web app on a free-tier, 64-bit Amazon AWS Ubuntu instance we set up.

The second project involved actually developing the basic full-stack website for customers to use, including user registration, login filters, search/browsing features, and shopping systems. The following image is what we followed when designing the initial website:

The third project dealt with adding reCAPTCHA to the customer login module, parsing a larger XML dataset to expand the movie database, securing Fabflix by adding HTTPS, and implementing an HTTPS-based dashboard that is equipped with stored procedures.

In the fourth project, we added AJAX to Fabflix and added a prefix search MySQL FullText Search feature.

The fifth project had us using connection pooling and adding prepared statements to the code base to optimize performance, and configuring Apache2 for load balancing as well as using MySQL Replication to enable Fabflix to scale. We then used Apache JMeter to measure the performance of the search feature in Fabflix with/without load balancing, with/without connection pooling, and with/without prepared statements as well as various combinations of the three aforementioned variables.
