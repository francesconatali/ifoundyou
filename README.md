# ifoundyou
An interesting web app created with ReactJS, JSX, Axios and Google Map.

Given an email address, the app makes use of the Full Contact API to find all the informations available for that user: Avatar, name, current job, company, location, gender, age range and bio.

It works very well especially with company email addresses. Try it with yours!

Moreover, ALL the dependencies are WITHIN the html file, using a simple bunch of URLs.

```
<script src="https://unpkg.com/react@16.0.0/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@16.0.0/umd/react-dom.production.min.js"></script>
<script src="https://unpkg.com/babel-standalone@6.26.0/babel.js"></script>
<script src="https://unpkg.com/axios@0.16.2/dist/axios.min.js"></script>
```

No need for web server, Node, create-react-app, and its zillion dependencies. And if you want to publish it on the web, you can use ANY hosting provider, as no specific server-side configuration is needed.

(just remember to insert your own GoogleMapApi Key and FullContact API Key)

:)

## demo
See it live at https://francesconatali.com/personalprojects/ifoundyou/
