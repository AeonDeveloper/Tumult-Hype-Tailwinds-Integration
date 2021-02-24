# Tumult-Hype-Tailwinds-Integration
Example file that brings TailwindCSS and Font Awesome together in Hype

Some important keys - in the Hype File, make sure to uncheck the option to protect from external styles.

To pull in TAILWINDS CSS,  I changed this method and the HYPE document may not reflect it.
A couple of ways to pull in TAILWINDS.  I did a mixdown with npx on the command line the first time, and then played with
embedding in the documents.  I have found its best right now to get the full minimized verison of tailwinds by the method
you are comfortable with, and then make sure its in the same directory as you index.htmil file (or whatever file points to the hype resource)

I am using a version of tailwinds that is referenced externally from the hype file to save space.  Check the Head HTML of the hype
for a reference on how to do this:
	link href="tailwind.min.css" rel="stylesheet"
  
Referencing font awesome is similar to this:

link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.2/css/all.css" integrity="sha384-vSIIfh2YWi9wW0r9iZe7RJPrKwp6bG+s9QZMoITbCckVJqGCCRhc+ccxNcdpHuYu" crossorigin="anonymous"


