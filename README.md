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

- had to do a git reset on the the 11th tutorial, as there was a serious bug. 2nd attempt was a success. bower was generating the files out side of the app

- tut 12, the bower animate file was generated outside of the bower file in another bower file outside of the app, causing the problem




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

- up|down sidebar 
  ctrl + 0





