Instructions from the tutorial


--
meteor create microscope

git init

meteor add mizzao:bootstrap-3
meteor add underscore

rm microscope.css microscope.html microscope.js 
mkdir -p client server public lib
touch client/main.html client/main.js

mkdir -p client/stylesheets
touch client/stylesheets/style.css

sudo npm install -g mu

mkdir -p client/templates
mkdir -p client/templates/posts
touch client/templates/posts/posts_list.html

meteor remove autopublish

touch server/publications.js

meteor add iron:router

mkdir -p client/templates/application
touch client/templates/application/layout.html

touch lib/router.js

meteor add sacha:spin

mkdir -p client/templates/includes
touch client/templates/includes/loading.html
touch client/templates/posts/post_page.html

touch client/templates/application/not_found.html
touch client/templates/application/layout.js 