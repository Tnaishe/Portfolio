# portfolio

Deployed website: https://csb-dzxkeh.netlify.app/

Here is one of the methods on how to bootstrap this app:

Add Bootstrap to React using Bootstrap CDN

The Bootstrap CDN is the easiest way, no extra 
installation or download is required. Go to 
"public/index.html", file and insert the following inside a link tag: <hey>

link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">



For using the JavaScript components that ship with Bootstrap, 
such as toggling a modal, dropdown, or navbar, we’ll need to 
link the bootstrap.bundle.min.js file, which comes precompiled 
with Popper.js. Place the following "<script>" tag near the 
end of our entry markup page, right before the closing the 
"</body>" tag:

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

