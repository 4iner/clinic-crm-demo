# clinic-crm-demo
A public demo for the CRM application

### Usage
The application can be accessed from [here](https://d15ju2xcsjey0j.cloudfront.net/).
The username `Demo` and password `ClinicAppDemo` can be used to access the application as an admin, while credentials `User` and `ClinicAppUser` sign you in as a regular user. The difference between these roles is the admin can view and upload photos to the app, while a regular user can only edit patient/visit data. 
> **Note: Please allow up to 30 seconds to sign in, as the backend server may require some time to start up, if it has not already.** 

### Technology used
The backend is running on a heroku dyno, using a Spring Boot application. The frontend utilizes ReactJS, and is being hosted from an AWS S3 bucket. AWS CloudFront combines these two into one domain to allow for proper cookie setting. 

> **Note: This version of the app is a public demo, therefore, photo management has been removed and replaced with static images, for the sake of demonstration**
