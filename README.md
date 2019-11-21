# ryanoliveira.me

## TODO
* Make nodes background black -- **DONE**
* Less nodes & make nodes move slower -- **DONE**
* Make Navbar black (same color as the particles-js background) -- **DONE**
* Make Navbar stay at top of screen always -- **DONE**
* Make the bottom edge of the Navbar have a shadow -- **DONE**
* Make Navbar faded & fade in after scrolling down -- **DONE**
  * 1 scroll *tick* from the top is when the Navbar should start fading in/out
* Change Navbar ordering (right align && put name on top left) -- **DONE**
* Turn the Navbar into a Hamburger Menu on mobile (or <600px horizontal res) -- **DONE**
* Center name on node background && choose a name size that fits well across all screen sizes -- **DONE**
  * Make this consistent across all screen sizes
    * Inherently an issue with hardcoded values
* Add titles (student, etc.) under name && make it look pretty -- **DONE**
* Fix scroll-up button position && make it fade in from bottom-right corner -- **DONE**
* Fix scroll-up button anchor OR ~~Make the HOME on the Navbar act as a scroll-to-top button~~ -- **DONE**
* Make resume open on new tab -- **DONE**
* Add a **Hey!** section -- **DONE**
* Add a **Portfolio** section -- **DONE**
  * Have the background of the **Portfolio** be the nodes background
* Include **My top projects** (Can change to **My Current Projects**)
  * Terminal TicTacToe/Chess (make the block black and look like a terminal with white/green text?)
  * Overwatch Data Parser
  * Something not programming related? Maybe a Discord bot? 2 Might be good enough for now.
* Add a dynamic **Timeline**

**<u>
15/17
</u>**

## Optional TODO
* Add a sneaky lenny face -- **DONE**
* Make a nested Footer (top part with info being dark grey AND the copyright thing at the bottom be black)
* Add a profile pic on top of the name at the top of the page
* Make an *Impossible List* section
  * Have the list in a JSON and have it auto-formatted on the page
* Make the sidebar more pretty
  * Possibly have icons beside each list item
  * Different color scheme?
  * Maybe a stretch:
    * Darken the rest of the webpage when active
    * Remove ability to scroll when active
    * Allow user to close sidebar when clicking outside of the nav (to the right)
* On Mobile - make the appearing/disappearing url bar at the top black/same color as navbar instead of default white
* Change font for slogan
* Make Navbar font bigger/bold

**<u>
1/??
</u>**

## NOTES
* particles-js hangs *slightly* below screen height. Not really noticeable, but can be changed to be more precise -- **DONE**
* Bug - Mobile - Particle-js nodes are not working for the entire screen in portrait (Possibly linked to Name not being centered properly) -- (apparently fixed from nothing by accident when working on other things) **DONE**
  * Apparently this is due to device vs resolution? It works properly on mobile, but NOT with a mobile resolution on desktop.
* Bug - wrapper-small div bugs out on mobile when scrolling - most likely due to the appearing/disappearing url bar at the top
* Bug - Mobile - Line break after 'E-' in E-mail when opening and closing nav bar