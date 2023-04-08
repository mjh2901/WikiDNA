## WikiDNA Update##

WikiDNA is going through a simplification.  After working on wikidna for a number of years I have decided to remove a number of plugin dependices and in the process remove HTML.  New users will be welcome to add ckgedit and use the enhanced html formatting in their docs but the base installation will be initially setup using markup.  This will allow the docs to be moved more easily to other platforms.  Future releases will have two catagoires "Prerequisites" which will house the only true dependancy Indexmenu and "Optional Plugins" which will include all the nice to have features.

## Welcome to WikiDNA

WikiDNA is a set of templates designed to create proper network documentation for any small or large enterprise network.  These templates are a starting point for documenting your network.  

WikiDNA is designed to be dropped into a DokuWiki install allowing any person or team to secure and start documenting.  It is possible to cloan this into any standard webserver, however all editing would have to be done by hand.

For installation simply clone the WikiDNA repository into your /dokuwiki/data/pages directory and you are ready to go.

### Required Prerequisites:
Working Dokuwiki install & the following DokuWiki extensions
  - Indexmenu, Creates the menu in the sidebar and index pages

### Optional Prereqisies:
  - ckgedit, WikiDNA can be edited with this visual inline HTML editor
  - Lastmod Plugin, Places the last modifed date on the pages for purposes of printing out and updating physial binders.
  - Copy Page Plugin, Allows quick duplication of a page especially usefull in sections where a template is used to create many pages.


### Install
1. Clone this repository into the dokuwiki:data:pages (yes this replaces the pages directory)
2. Go to your point browser at your wiki
3. Start editing every page to document your infrastructure

### Specific Settings
1.  In config/dokuwiki.php change the defer_js setting from 1 to 0 (This allows the menu to work)
2.  In config/dokuwiki.php change the useheading setting from 0 to 1 (This allows the menu to to show page headers intead of namespace)

### Standards:
1. Header Size
	
	- Start Page ==== Heading ====
	- Main Section Page **Heading2**	
	- Regular Page within section **Heading2**
  
### Notes:


### Demo:
[https://wikidna-demo.bigdoglabs.com](https://wikidna-demo.bigdoglabs.com)

### How To Use:
Navigate to a page click edit and enter the your information.

Sections where a Template File is going to be used several times (such as servers) select the template and use the "Copy this page" button.  When asked to Enter new-age's ID, only change the word template leave the numbers and colons alone (example 900:901:template) The preceding numbers and colons represent the folder structure changing them will move the file into a different location.  Once the page is created click edit change the header and add your information.  The menues will automatically update themselves to reflect the new page.

### WikiDNA Webiste:
[https://wikidna.bigdoglabs.com](https://wikidna.bigdoglabs.com)