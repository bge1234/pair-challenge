##This exercise is meant to bring everything together.

######There are multiple steps that you must work through and after each one is completed, `you must check in with an instructor.`  

####Sage and Scribe!
You and your pair will work together to complete all of the objectives.

`Sages` will articulate the problem, use their vocabulary to tell the scribe what to write.  It is imperative that you communicate effectively so that the scribe knows what to do!

`Scribes` will listen to the sages and follow instructions.  They are not allowed to speak unless the instructions are not clear. They must not write at will.

####Pair Programming! - This is for the later half of the day - skip these instructions and come back to them when we switch modes.

You will work together to solve each problem so that once the exercise is completed, each of you has a deep understanding of what the problem was, the many different approaches that you could take, and why you chose the approach you did.

Identify the problem, discuss different approaches and solutions and then work together to solve each problem.  `If one of you does not understand how to reach a solution, it is your job as a team to get on the same page. Worth together!`

##Stage 1.

* Work together to build the website from
[this repo](https://github.com/gSchool/website-homework)
* Pay attention to details!
* Follow the rules outlined in the readme.md. Once you are done, don't forget to check in with an instructor.

##Stage 2. - Git Commit and push!

#####Let's add some function to the navigation bar.

* Add a dropdown menu for the About link.
* When the user moves the mouse over the About link, a dropdown menu should show.
* The dropdown menu should have 3 links: Contact, Blog, and Services
* Do not use Javascript to reveal the dropdown menu
* Get rid of those three main nav sections and replace with a search bar
* Check in with an instructor

##Stage 3 - Git Commit and push!

* Wire up an API: Here is where you should use your creativity!
* When the user enters a search, you should return some higher level data(title/headline/link) to the main section(630x300)
* Choose what data gets sent to the other main section but make it relevant and useful to the right main section
* When the user clicks “Read More” they should be taken to an external link that is relvant to the data
* Populate the 3 article sections with data that is also relevant  
* When the user clicks “Read More” They are taken to that article

###List of API's without authorization - Use one of the API's listed or one of your choosing, as long as you can navigate the JSON comfortably!

* [Wikipedia](https://en.wikipedia.org/w/api.php?)
* [BBC1 Radio Playlist](http://www.bbc.co.uk/radio1/playlist.json)
* [Google Books](https://www.googleapis.com/books/v1/volumes?q=isbn:0747532699)
* [Google Location](https://maps.googleapis.com/maps/api/geocode/json?address=Oxford%20University,%20uk&sensor=false)
* [Twitter URL Count](http://urls.api.twitter.com/1/urls/count.json?url=http://www.bbc.co.uk/news/technology-26879185)
* [iTunes](https://itunes.apple.com/search?term=beyonce&entity=musicVideo)

###List of static 'mocked' API end points in case any of the above cause rate limit errors:

* Google Books https://apimocking.firebaseapp.com/googlebooks.json
* Itunes https://apimocking.firebaseapp.com/itunes.json
* Wikipedia https://apimocking.firebaseapp.com/wikipedia.json
* Google Location https://apimocking.firebaseapp.com/googlelocation.json
* BBC1 Radio https://apimocking.firebaseapp.com/radio1.json




##Stage 4 - Git Commit and push!

* Use jQuery to change something on the page, it is up to you what changes but make it either fun or useful but make it unique
* When clicking ‘read me’ show more info and make the area take up the width of the page
* When clicking ‘read me’ again the article hides

##Stage 5 - Git commit and push!

* If they click on “Contact” They are taken to another page Where they must fill out a form:
	* Name:
	* Email:
	* Phone:
	* Message:
	* Submit Button
* When the user submit’s the form the values the user has inputed in each field show along with a message stating “Your message has been recieved” and redirects to the home page

##Stage 6: Deploy to firebase!
