# Wellington-Heritage-Week.github.io

Welcome to the Wellington Heritage Week website! Here's some quick info to get your started.

## How is this website built?
This website is hosted on [GitHub pages](https://pages.github.com/), due to the relatively low traffic it received (as of 2022).

It uses a [Netlify CMS](https://www.netlifycms.org/) to manage its blog posts, events, hotels, and some other content around the site.

The pages are built using [Jekyll](https://jekyllrb.com/).

The CSS is created using [SASS](https://sass-lang.com/).

## How do I update the branding for a new year?
Wellington Heritage Week has a habit of updating its branding every year, which means new logos and text to use around the site. Here's a quick list of things you may need to update:

1. Create a new logo from the SVG file stored with our other WHW files. You can use Adobe Illustrator to update its colours, or something free like [InkScape](https://inkscape.org/).
2. Create a new date banner, much the same as the SVG file above, to reflect the new dates for your years festival.
3. Update the site settings in the CMS:
    * Change the [site settings](https://wellingtonheritageweek.co.nz/admin/#/collections/settings/entries/site) by updating the description and the default social media image
    * Update the author image on the [about page](https://wellingtonheritageweek.co.nz/admin/#/collections/settings/entries/about)
    * Publish these changes in the [Workflow](https://wellingtonheritageweek.co.nz/admin/#/workflow). Wait for Netlify to figure itself out, then update your local git copy of this repository once the changes have come through
4. Update the site logo and date banner (the image on the right of the header) by changing the old images for your new ones in the header.html file. Make sure your logos are in the /assets/img folder like the old ones are
5. Update the theme colours around the site. There's three mentions of the colour (likely in hexcode form like "#103636") in the head.html file and one in each of the site.webmanifest, \_sponsors.scss file, and main.sass files
6. Update the favicon for the website - it's basically a different version of the logo with a circular background instead of a square one. You can update the SVG file and export it as a PNG for this. Take that PNG and upload it to [this website](https://favicon.io/), which will give you some files and instructions on how to use them. Delete the old Favicon files and replace them with your new ones.

All going well, that should be all the changes you need to make. It is also worth updating the profile photos and banners of the social media pages, such as our Facebook, Instagram, and LinkedIn.

Keep an eye out for any other dates and logos that may have been missed, and update those too! Good luck.