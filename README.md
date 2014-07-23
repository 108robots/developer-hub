Template Developer Hub 
====================

*Note - This is an effort to make a vanilla version of [CFPB's outstanding API documentation](https://github.com/cfpb/api).  Though many of the references to the agency (and it's HMDA system) have been genericized, a number remain.  In particular, the `Basics`, `Console`, and `Queries` page have mostly been kept intact in order to show how those pages can work.  An agency re-using this would need to fully migrate that material to fit their API.*

----

This is the documentation repository for the [System] dataset.
Check out this API documentation at http://usg-website-templates.github.io/developer-hub/.

Thanks to the CFPB [eRegs](https://github.com/cfpb/regulations-core) and [HMDA](https://github.com/cfpb/api) teams and their documentation work for starting us off with a great codebase.

You can use [DOCter](https://github.com/cfpb/DOCter) to build documentation sites similar to this one.

## Using JavaScript and Bower

If you are going to work on the JavaScript for this site, you need to do the following:

* Run `npm install -g bower` to install Bower.
* Run `npm install -g grunt-cli` to install Grunt.
* Run `npm install` in the directory to install other tools.
* Run `bower install` to install dependencies.

After changing the JavaScript, run `grunt` to rebuild the minified JS.


