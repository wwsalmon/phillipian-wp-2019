# Phillipian.net Wordpress Theme 2019

Complete redesign of Phillipian.net by CXLII. Project led by Samson Zhang with contributions from Anthony Kim, Sarah Chen, Jeffrey Pan, and Alex Turk.

## Objectives
- General design
  - Fully mobile responsive
  - Readable, hierarchical typography
  - Better homepage, browsing experience
    - Higher information density
    - Accessible navigation
- Branding
  - Cohesion with print newspaper
- New digital editorial experiences
  - Author pages
  - Digital masthead
  - Digital-first sports coverage
  - "Look of the Week" lookbook

## Technical
The redesigned website will eventually hosted at [phillipian.net](http://phillipian.net/). While in development, [redesign.phillipian.net](https://redesign.phillipian.net/) will serve as a live development/staging environment. Both sites are hosted on Dreamhost and run Wordpress with the theme contained in this repository installed. Changes are deployed to the staging website manually and are not necessarily updated with this repository.

# To Do

## Active / High Priority
- Technical
  - [ ] Make title appear properly
- [ ] Add links to ads

## In Queue
- Page Creation
  - [ ] Join Plip
  - [ ] Sub to newsletter
- [ ] Automate Author Pages (Sarah)
- [ ] Test archive.php pagination
- Technical
  - [ ] Fix multiple categories showing up on article page
    - [X] ~~Featured~~
    - [ ] Look of the week
    - [ ] Sports

## Low Priority / Future Ideas
- Transition
  - [ ] Upgrade to WP 5.1 (wait until install new theme?)
    - [ ] Backup?
    - [ ] Test Visual Composer, etc. in local environment?
  - [ ] Eventually
    - [ ] Install New Theme
    - [ ] Clear out old plugins
- Page Creation
  - [ ] Advertise for Plip
- About
  - [ ] Resources section
    - [ ] Logos, photos
    - [ ] Technical: dev website?
- Homestrip
  - [ ] Swap editorial/video? Downside: editorial has no easy thumbnail
- Single
  - [ ] Sign up for newsletter bigger box
  - [ ] Sign up to write bigger box
- Other
  - [ ] Digital Masthead
  - [ ] Sports dedicated site
    - [ ] Scoreboxes?
  - [ ] Arts Lookbook
  - [ ] small visual changes: related posts, dropdown button, article sidebar, author info, etc.

## Done
- Transition
  - [X] Switch to PHP 7.2
  - [X] Enable SSL
    - [X] Certificate / Dreamhost
    - [X] Wordpress
      - [X] Main Site
      - [X] Redirects
      - [X] Media Links
- General
  - [X] Cleaner home nameplate thing
    - [X] Home horizontal row (homestrip)
      - [X] Eighth Page
        - [X] link up through wp-admin or auto script
      - [X] Join The Phillipian
        - [ ] create page, link up
        - [ ] Make video: life of the paper
      - [X] Subscribe
        - [X] create page, link up
      - [X] Plip Video
        - [X] Figure out thumbnail/image situation
        - [X] link up through wp-admin or YT API?
        - Flip video and editorial?
      - [ ] ~~Social Media (not doing)~~
  - [X] ~~Make navbar~~
    - [X] ~~Sections button on left~~
    - [X] ~~Search button on right~~
    - [X] ~~Responsive~~
    - [X] ~~Build dropdown menu~~
  - [X] Category.php
    - [X] ~~Figure out PHP~~
    - [X] ~~Style~~
    - [ ] Paging? -> needs to be tested
  - [X] Search bar & list
  - [X] Related Posts
  - [X] About Page, Basic Masthead
  - [X] Author pages
    - [ ] Automate (Sarah)
- Technical
  - [X] Tablet Responsiveness
  - [X] ~~Fontface CSS~~
  - [X] ~~Make Dreamhost online test~~
  - [X] Picture credit/size
    - [X] ~~Why is the media-credit shortcode being deleted when imported/~~exported~~? (preserved in the CSV so it's an import problem)~~ It was never an import problem, it just displayed incorrectly in the Visual Editor when trying to render shortcodes.
    - [X] ~~Read and display the credit shortcode using custom code or plugin~~ (ended up using custom code overriding default caption shortcode)
    - [ ] ~~Import photos properly (not doing this b/c just using the old WP)~~
  - [X] Shortcodes in excerpt, single
  - [X] Ads
    - [X] Uploaded from wp-admin
- Homepage
  - [X] General
    - [X] ~~Add date~~
    - [X] ~~Limit # of articles that show up~~
    - [X] ~~Prevent duplicate of featured article~~
  - [X] News
    - [ ] ~~1 col / 2 col split~~ (hard to do and doesn't add much, low priority)
    - [X] Merge w/ commentary layout
  - [X] ~~Commentary~~
  - [X] Eighth Page (in homestrip)
  - [X] Sports
    - [ ] ~~Show specific sport (second-level category) i.e. Boys Varsity Hockey b/c some titles don't specify sport~~
      - They were imported wrong, this isn't possible, second-level tags aren't even showing up. Shelf until reimport
  - [X] Arts
  - [X] See All Posts from this section link
