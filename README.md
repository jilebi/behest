# Behest
Behest: CI/CD automation helpers

This project will build endpoints that can be leveraged via webhooks to perform CI/CD automation tasks such as automated code quality checks etc. on pending merge requests and enforcing mandatory approval workflows.

# Running the app
## 1. Install dependencies:
```
$ git clone git@github.com:jilebi/behest.git
$ cd behest
$ npm install
```
## 2. Running the app
On MacOS or Linux, run the app with this command:

```
$ DEBUG=behest:* npm start
```

On Windows, use this command:

```
> set DEBUG=behest:* & npm start
```

Then load http://localhost:3000/ in your browser to access the app.
