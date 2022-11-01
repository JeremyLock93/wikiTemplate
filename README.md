This is the creation of the base of a new project to be updated in the near future.
It is a wiki page that can save and edit information from testing page.

To use you need to have the lastest go verison of 1.19*.
In order to run, have Go installed, and open your terminal. CD to the wikiGo folder.
./wiki is the command to run the code, if there is any errors 
Then use the command go build wiki.go to build the code and should correct the issue

For testing purposes the code is on the localhost:8080
Within the code you have handlers for saving, editing, and viewing
To view the page test, use localhost:8080/view/test
To view the editing page use localhost:8080/view/ANewPage,
when presented with the new page there should be a form where you can add text to a page and save it.

TODO

Create navigation between new pages via links (This requires CSS and HTML)
Give the wiki a homepage for landing and make it responsive (Same as above and some web design)
Link the pages for redirects (Requires Go coding)
Make the pages have uniform color scheme (This is more CSS, bootstrap to help with more complex framework)
