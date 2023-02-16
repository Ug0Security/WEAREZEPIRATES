title:"Yachtcontrol"

yeah, it is what it is..

found lack of access control on multiples pages

/index.php?profile=tablet&page=menu
/index.php?profile=tablet&page=settings&scherm=maintenance

you can change the maintenance mode to dev with the pin code 1508 it's in /scripts/general_scripts.js (others exist but are less privileged, 1234 - 8051)

some instances even leak the admin password

/index.php?profile=tablet&page=settings&scherm=authorization

seems to have a default admin password : yc8051

![zepirates](https://media1.giphy.com/media/TE3ZlXmfr5psI/giphy.gif)
