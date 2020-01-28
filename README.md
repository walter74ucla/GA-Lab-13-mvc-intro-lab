# https-git.generalassemb.ly-WebDev-Connected-Classroom-mvc-intro-lab-blob-master-README.md

# Lab - REST: Index/Show

## Part 1: Superheroes

### Basic Express App

1. Clone **(do not fork)** this.
1. Write a basic express app that will listen on port 3000
    - Once it's listening, log "Here to save the day..."
1. Test it by going to http://localhost:3000

### Routes

1. Create a variable called superheroes and set it to `['batman', 'superman', 'hulk']`
2. Create a route to `/superheroes`
    - The route should send the entire superheroes array
3. Create a route to `/superheroes/:index`
    - The route should send the superhero that is at the `:index`th index in the superheroes array. Look up how to access route parameters in order to use the index requested by the user.
4. You should test everything you build to make sure it's working.
5. Then you can test whether your app meets these specifications by running the automated testing file! <code>npm install</code> to install the necessary packages, <code>npm test</code> to run the tests.  If you're interested in how testing works, read the file in the `test` directory to get a feel for it.  Lots of new devs start with jobs that involve a lot of testing!

## Part 2: Fruits

1. Extend the app we've built in class so that the index route uses EJS to render all the fruits into HTML.
    - Each fruit that is displayed should have a link to that fruit's show page
    - Each fruit's show page should have a link back to the index page



