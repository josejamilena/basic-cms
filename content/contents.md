# Basic CMS

## Concept

For many microsites, a single page is enough. The thought is to have a web presence — a type of personal pinboard for a few images and some text. A public facing toy, if you will.

![mode-destockage.png](uploads/mode-destockage.png)

This _Basic CMS_ tries to be as "web natural" as possible— the website consists of a single markdown page that is translated through simple css. _Basic CMS_ exploits existing html structures (specifically the h1-p tags) to allow for a modular page. One can give each tag different typographic parameters that, when added together, create a fluid typographic landscape.

## Structure

_Basic CMS_ is built out in basic php. The existing backend is currently found at www.url.com/modify and is protected by simple htaccess and htpasswd files. These need to be updated for any install. 


Content iterations are archived with each save. 

This build currently uses local versions of Parsedown, dropzone, clibboard.js, and ImageResize to manage the website's markdown and image uploading/resizing. 

## Install

- Download or clone this page. 
- place contents into a directory of your choice. 
- Make sure you reveal your [hidden files](http://ianlunn.co.uk/articles/quickly-showhide-hidden-files-mac-os-x-mavericks/).
- In the /modify folder, edit the .htaccess and .htpasswd files to reflect the proper filepath and username/password. (I'd recommend this [site](http://www.htaccesstools.com/htpasswd-generator/) to generate your .htpasswd and .htaccess files)

