# Jupiter Broadcasting Website Spec

These are notes from JB Website Discussion. Feel free to edit and add things.

## General requirements
* Keep Old URLs/301 Redirect
* Open Source
  * Possibly on GitHub? http://github.com/jupiterbroadcasting
* Centralized place for issue queues and discussion
* Migration from current Wordpress to the new system
  * Note: This does not preclude continued usage of wordpress as an option and only pertains to migration.
* Search?
* Streamline production
* Mobile support
* Different theme? Dark look?
* Simplicity

## Episode listing
* Browse all episodes
* Sort by show
* Output an RSS Feed from the Episode Listing
* Easily change episode order
* Standardize RSS feed types

## Episodes
* Let people watch in HTML5 WebM
* Display the show notes
* Easy editing of show content

## Announcements?
* Provide a news listing along with an RSS feed
* Evaluate whether this is a required feature

## Live Stream
* View the stream in HTML5 WebM video stream
* Display the online IRC client

## Continuous Deployment
* Self-publish posts (streamline production)
* Push from GitHub markdown to the site live
* Deployment directly from GitHub
  * Travis

## Continuous Integration
* Automated building and testing of content
  * Travis

## Calendar
* http://fullcalendar.io/ can pull calendar from Google Calendar but also any source from anywhere that javascript can parse. 
* Like pull data from RSS Feed will also work with some small code base.


# Platform Choice
In selecting a platform, we must consider the following:
* Extensibility
* Community
* Is it currently maintained?
* Can you resize images dynamically?
* Is the content seperate from the View?

# Possible Frameworks
* Stick with Wordpress
  * Custom post type (shows, hosts, appPicks etc) (Easy to index, pull, convert "in site" or for use in apps / API)
  * Custom meta data / Custom fields
  * Manually programmed in the theme or use Advanced Custom Fileds plugin
* PicoCMS
  *  http://picocms.org/
* Jekyll
  * http://jekyllrb.com
* Hexo
  * http://hexo.io
* Middleman App
  * http://middlemanapp.com
* Metalsmith
  * http://www.metalsmith.io
* Nikola
  * http://getnikola.com/
* Nanoc
  * http://nanoc.ws
* Croogo
