# Heraldry-Books

This repository contains Jekyll source files for HTML versions of various Books about Heraldry. The original source of these books
are OCR scanned versions of paper originals provided by Archive.org or Google Books. They are out of copyright.

## Description

Each folder contains a separate book. Books that are largely narrative in nature are split into files by chapter; 
Reference books are split into individual entries, with sub-folders for each initial letter.

Each file has a YAML header containing the following fields:

- **pageTitle:** Title of the page.

- **up:** Full name (including suffix) of a file which should be considered the "parent" of this file.

- **next:** Full name (including suffix) of a file which should be considerd as coming next file in reading order.

- **prev:** Full name (including suffix) of a file which should be considered as coming before the current file in reading order.

- **layout:** The name that Jekyll will use to look for a template file in its \_layouts folder. This is different for each book.

Files may contain cross reference links and image links which assume that the folder structure remains as shown here, so 
each folder should be considered as a "block" and not re-arranged.

## Usage

All these files are ready for use with the Jekyll Static Site Generator. Prior to use you will need to provide an appropriate
template. This needs to provide a HTML type declaration, the &lt;html>, &lt;head> and &lt;body> elements, and (optionally) a &lt;h1> element
containing the page title. Obviously, the page contents will go within the &lt;body> element provided by the template.

You can also skip all this faffing about with Jekyll and just read the books in HTML format by going to https://drawshield.net/reference
I have provided the files here in case anything should happen to me, or my website; and in case they are useful to any one
else who wishes to incorporate them into their own work. Please, no commercial use attribution is always welcome, and 
contributions to the "coffee and cake fund" even more so! https://paypal.me/drawshield/USD10
