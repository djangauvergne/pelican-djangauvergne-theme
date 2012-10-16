DjangAuvergne Theme for Pelican
===============================

This theme has been designed for Pelican 3. It is used for the [DjangAuvergne community blog](http://djangauvergne.github.com/djangauvergne-blog/)

For more information about the pelican project, please refere to the project page: [http://getpelican.com](http://getpelican.com)

## Install

To install this new theme for your pelican's blog, first you need to have a fully functional pelican installation. A simple `pip install pelican` should do the trick, but refer to the [pelican documentation](http://docs.getpelican.com/latest/) for complete instructions.

One pelican installed, clone this theme and make it available for you pelican's blog

    git clone https://github.com/djangauvergne/pelican-djangauvergne-theme.git
    cd pelican-djangauvergne-theme
    pelican-themes -i $PWD/djangauvergne

You are now able to select this theme for your blog, by modifying your pelican's blog `pelicanconf.py`

    THEME = 'djangauvergne'

## Develop

Pelican offers the opportunity to have a develop mode for themes. Hence, if you plan to adapt this theme for your own needs, instead of installing it, symlinks it via:

    pelican-themes -s $PWD/djangauvergne

