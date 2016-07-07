# First Day at Work

My personal workflow on the first day working on a new project. Please feel free to add
and edit.

### Fork/clone repo

### Check package.json
* What file is our entry point?
* What's listed under engines?
* What dependencies do we currently have?
* What starts our app?
* What test suite are we using?

### Run npm install
I usually run npm install after I check package.json. Don't want any surprises :)

### Run Tests for First Time
* Are all the specs passing (probably not)
* Make note of any specs that are failing... move on

### Exploration Phase
* Look at the folder structure
* Checkout
* Check out the models, views and controllers
* Are there any magic numbers (i.e. constants, etc) that I don't fully understand
* Is there a database? Is there an ORM? What kind of relationships currently exist within the models
if any?

### Diagraming (Optional)
For more complex apps, I diagram the app's structure and associations

### Run the Local Version
Run the local version for the first time. Since some tests will be failing, this might be traumatic.

### Comment out all the passing specs
I usually commend out any specs that pass or any specs I'm not currently working on

### Make spec pass one by one
Work on each spec individually

### Sanity Check: Uncomment all the specs
Uncomment all the specs and run the whole test suite. All tests should pass.

### Check Local Version Again
Is our local version doing everything it needs to do? If so, time to deploy

### Check any todos
Are there any pending todos or not working/needs to be changed comments. If so, time to tackle those.

### Check Deployment Options
How are we deploying this app? Heroku, azure, AWS?

### Check if a Procfile and Gruntfile exist
Set up our procfile and grunt file. Minify/concat/ugilify any assets.

### Deploy
Fingers crossed, deploy the app.


