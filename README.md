# Introduction to ArcGIS Online workshop
We host our workshop materials through GitHub, a free and open-source software hosting platform. Here you'll find the backend of our workshop. 

To change background images, banners, icons, maps and more, go to '_img'. 

To change the main page go to 'index.md'. 

To make changes to the template itself, a good place to start is the [`_layouts`](/_layouts), [`_includes`](/_includes) and [`css`](/css) directories. These directories contain all the layout and style files used.

Questions? Ask on P2PU's [Community Forum](https://community.p2pu.org/c/tech/course-in-a-box/78).

# Running locally
- [install docker](https://docs.docker.com/engine/install/) 
- Run ```docker run -i -t --rm -u 1000:1000 -p 4000:4000 -v `pwd`:/opt/app -v `pwd`/.bundler/:/opt/bundler -e BUNDLE_PATH=~/opt/bundler -w /opt/app ruby:2.7 bash -c "bundle install && bundle exec jekyll serve --watch -H 0.0.0.0"```
