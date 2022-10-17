# Api-Documentation


## Making your first API call

We've written a quick step-by-step guide to walk you through how to login on Biot User account, make your first API call, and interpret the results.


## Introduction

This Api service will help users to synchronize their data & fetch whatever data they want. For this we have created various Api services where user can purchase services as per their requierment and get acccess towards it. To learn more about this we have created step by step guide where user will get to learn how to integrate this Api towards their application. To learn more about Api Services, [Please Contact Our Sales Team](https://biotworld.in/general-inquiry-biot/).


### How it works

### Step 1: Login inside Biot User panel: 
When a user sends a request with payload (mobile_number & password)an authentication token is generated which you will receive in a response as well as you will receive authentication-key via mail. 

### Step 2: Pass Authentication Token:
Now you will need to pass that authentication token & authentication-key to receive any response without that you will not be able to fetch data.



 ### All Api Request & Response are shown below:
 #### 1.) Authentication API:
          Method: POST
          URL: https://biotworld.in/api/external/login
          Header: 

### Request:
 User will Send a request with Mobile Number & Password
```
{
   "mobile_number": "9586722584",
   "password": "12345",
}

```

### Response
```
{
"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE2NjgzMzM3NjMsImlkIjoxODQxLCJpYXQiOjE2NjU3NDE3NjN9.s6MoReMqc_29hXErb1YuzhZdc5w0plyAyQIjB1k7i3A"
}


```



