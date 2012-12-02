The Hackerscout Handbook
========================

The coder's guide to community building.

## Getting Started:

This site is powered by [Jekyll](http://jekyllrb.com/), because it's awesome.
To get setup with Jekyll, head on over to the
[github page](https://github.com/mojombo/jekyll) to install the gem and read up
on the documentation. It's simple, I promise. Then, you should be good to go!

To contribute, fork and pull request to your heart's content. Also, feel free
to open any "issues" for page requests, other info you think we should include,
and necessary bugs to squash.

## Adding New Pages:

1. Does the page fit into an existing category? If so, go to step 2. If not,
   add a new folder for that category in the root folder. Folder names should be
   hyphenated, just for consistency.
2. Add a new page in the appropriate folder. Page file names should be
   hyphenated, again for consistency. Pages can be written in markdown or
   regular-type HTML. Add a heading to the file like so and type away:

   ```
    ---
    layout: default
    title: YOUR PAGE TITLE GOES HERE
    ---
   ```

3. Open `index.html` and add a link back to the page you just created under the
   appropriate category. File types are stripped in routing, so a link to the
   page should look like `/category/page-name/`. If you've created a new
   category, first add a `<h2>` with the category name and a `<ul>` for pages.
   This page functions as our *Table of Contents*.
4. That's it! Submit a pull request and give yourself some karma points.
