Notes

- in order for the page to work correctly, 
	start the server and make sure that it runs on the url,
	local:8000 for example 

- using ngSrc prevents the browsers from making an http request 	to an invalid location





----------------------------------------------------------------
Bugs


- had serious issues installing Bower, had to force it with 
  sudo npm install-g bower and make sure that the node version
  was up to date
    https://blogs.oracle.com/geertjan/entry/angularjs_seed_bower_and_netbeans


- was missing css, had bugs with the display/view







----------------------------------------------------------------
Clips

Note that the phones.json file contains unique ids and image urls for each of the phones. The urls point to the app/img/phones/ directory.

app/phones/phones.json (sample snippet):

[
  {
    ...
    "id": "motorola-defy-with-motoblur",
    "imageUrl": "img/phones/motorola-defy-with-motoblur.0.jpg",
    "name": "Motorola DEFY\u2122 with MOTOBLUR\u2122",
    ...
  },
  ...
]

----------------------------------------------------------------
Sublime 

- sidebar 
  cmd + k and cmd +b

- skip to line
  ctrl + g and number 
 
- move tabs 
  opt+cmd  and arrow key







