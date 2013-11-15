Font Awesome Migrator
=====================

This is a script to help you migrate your project from Font Awesome 3 to 4.

To use it:

    font-awesome-3-to-4 path/to/your/files/*.html path/to/your/files.*less ...

It edits your files *in place* so be careful!

I use it like this on my project:

    find webclient/app/ -type f | xargs font-awesome-3-to-4

After running this tool be sure to review and test the chagnes it made. There will
still be hand editing required. You've been warned.

Where it fails
--------------

* If you have embedded `<style>`s in your HTML with `icon-*` classes, this script
  will not migrate them correctly.

Contributing
------------

Pull requests welcome!
