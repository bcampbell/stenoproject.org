Web site for http://stenoproject.org

Build using [Glod](https://github.com/bcampbell/glod) ('The new glod standard in static site generation').

- `skel` - the skeleton of the site, dir structure and static files
- `template` - templates for formatting the site
- `content` - individual pages in markdown format, to be processed through the templates.

To build the site:

    $ cd stenoproject.org
    $ glod

The result will be placed in `www`, ready for upload.

For local testing, run as:

    $ glod -server

Then browse to http://localhost:8080
Glod will automatically rebuild if any of the source files are altered.

