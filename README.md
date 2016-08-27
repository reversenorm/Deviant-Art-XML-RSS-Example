This repository is to demonstrate a method for importing data from a gallery on the Deviant Art website into another webpage. You can view a functioning version of this code at http://technecreative.com under the Art section or a stand alone version at http://technecreative.com/DeviantArtBasicLoader.html.

While Deviant art does have an API, unless you want to change userdata it is simpeler to use the build in RSS feeds from the Deviant Art website. In this example I chose to grab a specific gallery within my Deviant Art page to import to my second website. The Deviant art backend will output an XML document contaning the relevent information for a gallery. A typical URL would look like this:

http://backend.deviantart.com/rss.xml?type=deviation&q=gallery%3A{USERNAME}%2F{Gallery ID}

With this as the URL it is rlatively easy to put the data from the URL into a variable using .ajax as show in the document. From there the tree is pretty straight forward; however the path to get a particular element can get rather long so these are stored in local variables when constructing the page.

Hope this is helpful

~Reversenorm



