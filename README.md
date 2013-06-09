LayoutViewer
============

A Magento module that dumps layout information via query string.

This extension's functionality has been supplanted by <a href="http://store.pulsestorm.net/products/commerce-bug-2">Commerce Bug</a>, but it's kept here for historical and educational purposes. 

###Layout Viewer

Implements a query string based way to view layout information for a particular request. 

Original Blog Post: http://alanstorm.com/layouts_blocks_and_templates

###Build Instructions

The `build_layout_viewer.bash` file is a bash script that will create a simple tar archive of the extension files. 

    $ ./build_layout_viewer.bash
    
This script assumes the existence of a `var` folder.    