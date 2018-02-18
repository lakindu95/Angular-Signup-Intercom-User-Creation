# Angular-Signup-Intercom-User-Creation
This is a simple application which integrates intercom with the angular 4 app and create an intercom user instantly when the user signup from angular 4 application.

# Install

Step 1: Install the modules

```npm install```

Step 2: Add Intercom APP_ID to index.html and environments/environment.ts and environment.prod.ts

``` <script>
            var APP_ID = "Your_APP_ID";
          
           window.intercomSettings = {
              app_id: APP_ID
            };
          </script>
    <script>
```
```
export const environment = {
  production: false,
  APP_ID: 'Your_APP-ID'
};
```

Step 3: Run the project

```ng serve```


This application is using the following angular application with modifications to implement the cause http://jasonwatmore.com/post/2016/09/29/angular-2-user-registration-and-login-example-tutorial
