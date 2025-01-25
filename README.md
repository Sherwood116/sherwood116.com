# Sherwood116.com
The site is currently a very basic html site (using php for [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself))

## Updates
For all changes, create a branch of `main` and make a Pull Request when you are ready for the changes to be reviewed.

## Testing locally
This repo contains a docker container that will allow you to test changes before they are uploaded to the web server.

note: This requires [docker](https://www.docker.com/)

`$ docker-compose up`

Open a browser, and go to `http://localhost:8089/`

## Website
`public_html` contains the actual files for the website. 

Most, if not all, changes will be in this folder.

### Development Ideals
1. Keep your code [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
2. All information should follow the Scout Outh and Law in principles.


### Structure
Special files

`style.css` - Cascading Style Sheet, used for formatting html in the browser.
`*.php` - Hypertext Preprocessor files, used to [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) development of websites (at least here).


The root (`public_html`) of the website contains `<name>.html` files that are found right after `sherwood116.com/`.

 - `index.html` - This is the "landing page" of the site
 - `honor_role.html` - honor_role specific content
 - `calendar.html` - calendar information
 - etc.

#### Folders
Special folders

`js` and `images` are a convention used in html design to group resources like javascript and images.


Folders below the root (`public_html`) of the website will add another layer to the url `sherwood116.com/<folder_name>`

 - `documents` - documents found on the documents/documents.html page
 - etc.


