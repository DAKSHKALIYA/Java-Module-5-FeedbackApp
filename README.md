# FeedbackApp – Java Servlet Web Application

## Project Overview
FeedbackApp is a Java Servlet-based web application developed using HTML, Java Servlets, and Apache Tomcat. It allows users to submit feedback and displays the submitted information on the screen.

## Technologies Used
- Java
- HTML
- Java Servlet
- Apache Tomcat 10
- Jakarta Servlet API
- web.xml

## Features
1. Accepts user's Name.
2. Accepts user's Email.
3. Provides Feedback Type selection:
   - Complaint
   - Suggestion
   - Compliment
4. Accepts Comments through a text area.
5. Submits feedback using the HTTP POST method.
6. Displays a thank-you message with the submitted feedback.
7. Displays the current date and time.

## Project Structure

```text
FeedbackApp/
│
├── feedback.html
│
├── src/
│   └── FeedbackServlet.java
│
└── WEB-INF/
    ├── web.xml
    └── classes/
        └── FeedbackServlet.class
```

## Servlet Details
**Servlet Name:** FeedbackServlet

The servlet uses `request.getParameter()` to read the submitted form data and generates an HTML response.

## URL Mapping
The servlet is mapped to:

`/submitFeedback`

using the deployment descriptor `web.xml`.

## How to Run
1. Install JDK and Apache Tomcat.
2. Deploy the FeedbackApp folder inside Tomcat's webapps directory.
3. Compile the servlet using the Jakarta Servlet API.
4. Start the Tomcat server.
5. Open the application in a web browser.

Application URL:

`http://localhost:8080/FeedbackApp/feedback.html`

## Expected Output
After submitting the feedback form, the application displays:

- Thank you message with the user's name.
- Selected feedback type.
- Submitted comments.
- Current date and time.

## Assignment
Core Java – Module V  
Java Server Technologies – Servlet  
Practical Home Assignment
