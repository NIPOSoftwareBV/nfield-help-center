# Nfield Help center

A website project designed to provide useful and timely information for customers of the Nfield ecosystem.

This is a [Jekyll-based site with a theme based on the Google Material Design Lite library](https://github.com/gdg-managua/jekyll-mdl).

## Post Options

All the post, require an image and maybe an author and declare if the post is highlighted or not, the image are used in the cards and the autor used for the footer in the cards, the highlighted post is used for make this 12 cols and not a card, if you want to use the custom images and set the author and the highlight post, just add a new key in the post config, something like this:

    ---
    layout: post
    title:  "Welcome to jekyll-mdl"
    date:   2015-07-11 11:34:20
    categories: jekyll
    highlight: true
    image: http://www.wchs4pets.org/wp-content/uploads/2015/03/cat_1-jpg.jpg
    author: Google Developers Group Managua
    ---

## Layout Configuration
You can setup 4 types of layout

- Fixed Nav + Simple Card Grid
- Fixed Nav + Highlight Post + Card Grid
- Drawer Nav + Simple Card Grid
- Drawer Nav + Highlight Post + Card Grid

For use this in the [_config.yml](https://github.com/gdg-managua/jekyll-mdl/blob/master/_config.yml) select the type of layout, rebuild the website and voilà :smile:

## Contributing
If you want to contribute to this project, please read the [CONTRIBUTING](https://github.com/gdg-managua/jekyll-mdl/blob/master/CONTRIBUTING.md) file and perform the following steps

    # Fork this repository
    # Clone your fork
    jekyll serve --watch

    git checkout -b feature_branch
    # Implement your feature and tests
    git add . && git commit
    git push -u origin feature_branch
    # Send a pull request for your feature branch

## License
Licensed under the Apache 2.0 license.
