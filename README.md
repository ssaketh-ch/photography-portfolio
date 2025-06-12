Run the website locally to test
$ cd photography - go to the project directory
$ bundle install - install gems
Change the baseurl in _config.yml
$ bundle exec jekyll serve - start/run the website
Build the website
$ cd photography - go to the project directory
$ npm install - install all npm dependencies
$ gulp - minify css, js, resize images, etc.
Note: You only need to build the website if you make changes such as replacing the images, modifying the css styles, etc.

ProTips
Resize Images
I have made this as a npm package with gulp to automate image resizing and thumbnail generation. So if you're lazy like me then you can just do the following before you push your images to github.

Fork and clone the project to your computer
Go inside the project $ cd photography
Install all dependencies by $ npm install
Copy all your pictures (possibly jpg, the largest size available, straight from your camera) and put it inside images directory
Run $ gulp resize to resize the images and to generate thumbnails automatically
Push your changes to github.com by $ git add --all and $ git commit -m "a nice commit message" and then finally $ git push origin master
