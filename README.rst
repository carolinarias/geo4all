Geo4all - OSGeo education and research outreach: how it works and how to join
=================================================================================

Talk for FOSS4G NA 2016:
https://2016.foss4g-na.org/session/geo4all-osgeo-education-and-research-outreach-how-it-works-and-how-join

Online:
http://ncsu-osgeorel.github.io/geo4all

Abstract
--------

Since its establishment in 2011 through MoU between OSGeo and the
International Cartographic Association (ICA) the global network of
academic Open Source Geospatial laboratories has reached over 100 members
from all continents. ISPRS joined the initiative in 2014. This session
describes the mission of the initiative, its current activities and
infrastructure and explains the simple process of joining the network.
Examples of lab collaborations and contributions to open source geospatial
projects will provide inspiration for others to participate.

Author
------

* Helena Mitasova [North Carolina State University]

Getting the manual
------------------

To build the presentation slides with instructions::

    ./build-slides.py title.html template-slides.html plain-slides.html math-slides.html build-slides.html

The open the file ``index.html``.

Building and publishing pages for this repository
-------------------------------------------------

Clone the repository::

    git clone https://github.com/ncsu-osgeorel/geo4all

Navigate to the first clone and build pages::

    cd geo4all

Do your changes, build to a `build` directory::

    ./build.sh

Review the changes, add the changes, commit and push::

    git add -A
    git commit -am "new colors for the website"
    git push

Get the `gh-pages` branch for publishing (clones into the `build`
directory)::

    ./get-gh-pages-branch.sh

Publish (uses the `gh-pages` branch)::

    ./publish.sh

About
-----

Presentation is using on Reveal.js HTML Presentation Framework.

* http://lab.hakim.se/reveal-js/#/
* https://github.com/hakimel/reveal.js/
