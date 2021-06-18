## Welcome to WikiDNA

WikiDNA is a set of templates designed to create proper network documentation for any small or large enterprise network.  These templates are a starting point for documenting your network.  

WikiDNA is designed to be dropped into a DokuWiki install allowing any person or team to secure and start documenting.  It is possible to cloan this into any standard webserver, however all editing would have to be done by hand.

For installation simply clone the WikiDNA repository into your /dokuwiki/data/pages directory and you are ready to go.

### Prerequisites:
Working Dokuwiki install & the following DokuWiki extensions
  - ckgedit, WikiDNA is edited with this inline HTML editor
  - Lastmod Plugin, Places the last modifed date on the pages for purposes of printing out and updating physial binders.
  - HeaderFooter Plugin, Places the Header and Footer on all pages
  - Copy Page Plugin, Allows quick duplication of a page
  - SubPages, Creates teh page listing within folders
  - Indexmenu, Creates the menu in the sidebar

### Install
1. Clone this reposity into the doluwiki:data:pages:wikidna
2. Go to your point browser at your wiki
3. Start editing every page to document your infrastructure

### Specific Settings
1.  In config/dokuwiki.php change the defer_js setting from 1 to 0 (This allows the menu to work)
2.  In config/dokuwiki.php change the useheading setting from 0 to 1 (This allows the menu to to show page headers intead of namespace)

### Standards:
1. Header Size
	
	- Start Page **Heading**	
	- Main Section Page **Heading2**	
	- Regular Page within section **Heading3**
  
### Notes:
Footer text is specific to each section, within the section folder you will find a _footer.txt file.  Edit this file to change the footer on every page within that section.  In order to change all the footers globaly you must edit each of the 10 _footer files within the numbered section folders.

### Demo:
[https://wikidna.bigdoglabs.com](https://wikidna.bigdoglabs.com)

### How To Use:
Navigate to a page click edit and enter the your information.
Most of the templates are single use, in cases where a templage needs to be used several times, go into the webserver find the page in the coresponding numbered folder, duplicate and rename generally by simply upping the three digit number at the start of the filename by one digit, then retrun to the sections navigation page and add a link to the new page.
