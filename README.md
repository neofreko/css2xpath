css2xpath
=========

Taken from http://james.padolsey.com/scripts/javascript/css2xpath.js

YQL statement to use:

    use 'https://github.com/neofreko/css2xpath/raw/master/data.html.cssselect.xml' as data.html.cssselect;
    select * from data.html.cssselect where url="http://www.animedreaming.tv" and css='#latest_holder .latest_title a'
    
Test on the console [here](http://query.yahooapis.com/v1/public/yql?q=use%0A'https%3A%2F%2Fgithub.com%2Fneofreko%2Fcss2xpath%2Fraw%2Fmaster%2Fdata.html.cssselect.xml'%20as%20data.html.cssselect%3B%0Aselect%20*%20from%20data.html.cssselect%20where%20url%3D%22http%3A%2F%2Fwww.animedreaming.tv%22%20and%20css%3D'%23latest_holder%20.latest_title%20a'&format=json&callback=)
