## Mobile Intelligence Laboratory Homepage

This is the homepage of [Mobile Intelligence Laboratory](https://mint-lab.github.io/) (so-called _MINT Lab_) in [SeoulTech](https://en.seoultech.ac.kr/), Korea.

The homepage has forked from [Steve's No-Good-Very-Bad Jekyll Theme](svmiller/steve-ngvb-jekyll-template). The MINT Lab contents were added with little modification of the original theme. What I did are as follows:
* Edit `_config.yml` and `_data/menu.yml`
* Add my contents in Markdown at `mint-lab/*.md`
* Remove unnecessary contents files for an example
* Optional) Change main colors and style little bit

I wish that my repository will be an useful example for you to use [Steve's No-Good-Very-Bad Jekyll Theme](svmiller/steve-ngvb-jekyll-template) for your homepage.

The following is the original `README.md` of [Steve's No-Good-Very-Bad Jekyll Theme](svmiller/steve-ngvb-jekyll-template).



---
### Steve's No-Good-Very-Bad Jekyll Theme

This is my custom Jekyll theme, which is basically [Joel Glovier](http://joelglovier.com/)'s `jekyll-new` theme smashed with [Alex King](http://www.alexking.org)'s [Favepersonal](https://crowdfavorite.com/favepersonal/) theme for Wordpress. I used Favepersonal for my Wordpress site before abandoning it. You can see my site at [svmiller.github.io](http://svmiller.github.io).

Much of what is contained in here is derivative of those two works. That said, do observe the `embedpdf.html` and `image.html` files in the `_includes` directory. `embedpdf.html` uses Google Docs to allow for embedding of PDF files hosted on Dropbox. `image.html` provides fancier images than what is standard for Markdown. An example use of `embedpdf.html` can be observed in the `cv.md` file. An example use of `image.html` can be observed in the `about.md` file.

I use data-driven navigation, which you can see in the `menu.yml` file in the `_data` directory. There's also a `nav.html` file in the `_includes` directory with modified `header.html`.

Mobile support is clearly functional, though some white-spacing could be improved. Feel free to offer improvements if you'd like.

`css` and `_sass` directories also functional, if a bit cluttered. Do observe new colors I created for `$clemson-orange` and `$clemson-purple` in `css/main.scss`.

Feel free to contact me at svmille@clemson.edu. Send along some cheers too if you find it useful.
