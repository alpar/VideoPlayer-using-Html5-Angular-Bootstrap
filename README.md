##VideoPlayer-using-Html5-Angular-Bootstrap
This is a videoplayer application develop by Html5, Angularjs and bootstrap.

##Inital Setup
 * Create a project folder. 
 * Go into the folder directory and download and install Bootstrap,Jquery and Darktheme of Bootstrap for the VideoPlayer.
 * To take advantage of functionality as data binding and specialized Angular JS directives to extend HTML elements. 
 * Animate JS is  that works particularly well with the Angular JS NG Animate module. 
 * We download angular-animate.min.js into the Js folder of project directory.
 * There are CSS helper classes that allow us to animate things with the Angular Animate module more smoothly. 
 * To animate we need to install Animate.css into the CSS folder of the project directly.
 * We can use the project directory along with working files into the bracker or sublime text IDE.

##Step 2: Create video element
 *  create a video folder in the project directory.Inside of it there is our mp4 file that we're going to reference for our video playback.
 *  I'll add some space within the body of our HTML document and paste in a video tag snippet.

##Step 3: Making responsive
 * create an actual parent div element that's going to contain the video. 
 * so just declare "div", and wrap our video element within this parent "div".
 * so upon this "div", there are two specific bootstrap classes that going to use to make this responsive.
 * To constrain the ratio to 16 by nine.
##Step 4: Building simple controls
 * we have a class of button, or btn, which is the default Bootstrap button class, and for our styling.
 * we apply btn-default. Which again is the default button skinning used via CSS for Bootstrap buttons.
 * Here we have three buttons, one is play, one is pause, and the other is stop. 
   These buttons are controls but need to have functional.

##Step 5: AngularJS with the application
 * declare all of these as JavaScript variables inside of our HTML. To do this, 
 * create a new script object and I'll make sure to actually create this above our Angular JavaScript.
 * it need to pass in window just like passed in scope right here. 
 * so what wse'll do is, right after scope, its going to pass in $window.
 * This is going to give access to the objects within our DOM inside of our video application here.
 * so anything that is declare outside of this JavaScript file such as videoSource, title, and description,
   its easy to bind them to the scope within the app itself through the controller.

##Step 5: Playback with angularJS
 * specific angular class called "ng-cloak". 
 * ng-cloak does, is it makes sure that none of this stuff is visible until angular is completely loaded in and running.
 * implementing the playback and mute controls.
   formatting time and setting intervals.

##Step 5: Building playlist 
 * building a details panel.
 * playlist data formation.
 * rendering playist selections for the player.
 * animating players contorl.

  
   
   



 
