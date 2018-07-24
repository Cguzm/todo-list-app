# Setup Instructions

- Start your mongo daemon `mongod` in a separate terminal tab
- Install `nodemon` globally (if you don't already have it installed) with `npm i -g nodemon`
- Run your application in its own terminal tab with `nodemon`
- Navigate to `localhost:3000` in your browser

*Note: If you're working from c9 then see below:
- Change the following lines at the bottom of app.js:

```JS
app.listen(process.env.PORT, process.env.IP, function(){
    console.log("The server has started!");
});
```
