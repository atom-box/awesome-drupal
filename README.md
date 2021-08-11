# Working with Drupal

A list of demos, templates, docs, books.  Forked from [MrSinguyen](https://github.com/mrsinguyen/awesome-drupal)


### Running Drupal in Docker

* [Uninstall Docker](https://askubuntu.com/questions/935569/how-to-completely-uninstall-docker)  More important than it sounds: Docker is quite an invasive species on your machine.
* [Uninstall Docker 2](https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes)  Again, no joke to remove completely
* [Docker at Digital Ocean](https://docs.docker.com/machine/drivers/digital-ocean/)
* [Digital Ocean v2](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04)
* [Rootless](https://docs.docker.com/engine/security/rootless/#prerequisites) Run the Docker daemon as a non-root user
* [Getting Started](https://docs.docker.com/get-started/)
* [Install Drupal with Docker Compose](https://www.digitalocean.com/community/tutorials/how-to-install-drupal-with-docker-compose) Not "PHP Composer", this is a docker thing
* [Install and use DDev](https://github.com/drud/ddev) DDev is a better version of XAMP: plays well with Docker
* [More DDev setup](https://www.ostraining.com/blog/tools/setting-up-ddev-in-linux/)
* [Official DDev documentation](https://ddev.readthedocs.io/en/stable/users/faq/) Just okay. I had some trouble setting up permissions for ddev in Docker and these docs were just so so for fixing that.

### Composer

* [Update vs Install; Lock vs Json](https://daylerees.com/the-composer-lock-file/) Dayle Rees clarifies some best practices
* [Composer Cheatsheet](https://devhints.io/composer)
* [Lullabot blog](https://www.lullabot.com/articles/drupal-8-composer-best-practices)


### Headless and JAMstack

* [Gatsby with Decoupled Drupal Pt 1](https://www.gatsbyjs.com/docs/glossary/decoupled-drupal/#gatsby-skip-here) Headless Drupal
* [Gatsby with Decoupled Drupal Pt 2](https://www.gatsbyjs.com/guides/drupal/) Official Gatsby docs
* [Intro to CMS Headless Concepts](https://buttercms.com/blog/headless-drupal-the-what-why-and-how)
* [Droptica Blogpost on Choosing a CMS](https://www.droptica.com/blog/why-drupal-best-headless-cms/)
* [Getting Started](https://atendesigngroup.com/articles/decoupled-drupal-gatsby-getting-started) Video. From Aten Design Group.
* [Shane Thomas Interview](https://www.mediacurrent.com/blog/decoupling-drupal-shane-thomas-gatsby/)  Podcast with transcript
* [Intro to Content Mesh](https://frontendmasters.com/courses/gatsby/the-content-mesh/) Six minute free video preview of paysite.  No Drupal specific content.
* [City of Sandy Springs 2019](decoupled CMS, Drupal replaced the city’s existing WordPress site.) Case study where MediaCurrent helped Sandy Springs, GA shift Content Management away from the front end of their website by going to headless Drupal with Gatsby CMS


### Hosting

* [Hosting review](http://www.kristen.org/content/first-impression-drupal-9-managed-hosting-providers) 2020. Drupal focused.
* [InMotion](https://www.inmotionhosting.com/support/edu/drupal/) cheap
* [Acquia](https://www.acquia.com/products-services/acquia-cloud/drupal-hosting) robust; managed
* [1&1](https://www.ionos.com/) cheap
* [Code Enigma](https://www.codeenigma.com/our-services/drupal-hosting) very robust
* [Pantheon](https://pantheon.io/) robust; managed
* [Amazee](https://www.amazee.io/) Third most popular Drupal host
* [Platform.sh](https://platform.sh/marketplace/drupal/)
* [Cloudways](https://www.cloudways.com/en/drupal-hosting) claims to be much faster, less opinionated than WP Engine
* [Woodpeckr](https://www.woodpeckr.io/services/managed-drupal-hosting/)

### Tutorials

* [Symfonycast](https://symfonycasts.com/tracks/drupal) Awesome teacher, awesome interface.
* [Drupalize Me](https://drupalize.me/)  Just okay.  Lots of content and is up to date.  Not much value added compared to the regular docs from Drupal Org
* [Debug Academy](https://debugacademy.com/event/drupal-course-fall-2021/sun-2021-09-12)  Three month class for Fall 2021
* [DrupalEasy](https://www.drupaleasy.com/tutorials) Smallish set of lessons.  Good.
* [DrupalCamp](https://drupal.tv/curated-playlists) Drupal TV curated playlists from LOTS of conference talks.  Many.  Many, many.
* [The Drupal 8 Theming guide](http://sqndr.github.io/d8-theming-guide/index.html)
* [Free Drupal 8 Tutorials – An Exhaustive List](http://redcrackle.com/blog/drupal-8/free-tutorials-list)
* [Drupal Headless Architecture with Inferno.js [Live Demo]](https://snipcart.com/blog/drupal-headless-architecture-tutorial)
* [Some Drupal Tutorials](https://www.youtube.com/c/AkshayKalose/search?query=drupal)
* [Drupal Camp Asheville 2018 Training](https://www.youtube.com/playlist?list=PL8xTPkdstN3GyL0LjpZwAR_b0CttG_aZ2)
* [Drupal 8 Module Development Course](https://www.youtube.com/playlist?list=PLpVC00PAQQxHi-llE9Z8-Q747NYWpsq6t)


### Books

* [Learning Drupal ](https://www.goodreads.com/book/show/28902292-learning-drupal-8?from_search=true&from_srp=true&qid=RRrPHHGfOb&rank=4) by Nick Abbot, Richard Jones
* [Drupal 8 Module Development: Build and customize Drupal 8 modules and extensions efficiently](https://www.goodreads.com/book/show/36615927-drupal-8-module-development?from_search=true&from_srp=true&qid=RRrPHHGfOb&rank=5) by Daniel Sipos
* [List 1](https://www.goodreads.com/search?utf8=%E2%9C%93&q=drupal+8&search_type=books&search%5Bfield%5D=on) - List from Goodreads
* [List 2](https://www.drupal.org/books) - List.from Drupal Org

### Tools

* [drush & drupal developer](https://www.youtube.com/watch?v=QkRF1hc51QE) video from WebWash
* [drupaltools.github.io](https://drupaltools.github.io/) - A list of open source tools that can help people accomplish Drupal related tasks.
* [check_drupal](https://github.com/cytopia/check_drupal) - Nagios drupal plugin to monitor the state of a drupal site for security updates, core errors and more.

### Integration

- [Integration Applications](https://drupalintegration.com/app-list?app=) - List of integration with third party services


### Drupal 8
* [overview of Drupal](https://www.youtube.com/watch?v=HI2_PEewtQY) 44 min, Nicaragua
* [Drupal 8 User Guide](https://www.drupal.org/docs/user_guide/en/index.html) - This guide was written mainly for people with minimal knowledge of the Drupal content management system.
* [Evaluator Guide](https://www.drupal.org/docs/official_docs/en/_evaluator_guide.html) - This guide provides instructions for creating a temporary Drupal demo application that can be used to evaluate Drupal on your local machine.
* [Drupal 8 Guide](https://www.drupal.org/docs/8) - A catch-all guide for Drupal 8.
* [Drupal 8 APIs](https://www.drupal.org/docs/8/api) - Drupal 8 introduces many new APIs and keeps only some of the Drupal 7/6 API. This section details the APIs in Drupal 8.
* [Drupal 8 API Reference](https://api.drupal.org/api/drupal) - This site is an API reference for Drupal, generated from comments embedded in the source code. More in-depth documentation can be found at https://www.drupal.org/developing/api.

## Developer Guides

Documentation for developers about tools, processes, and standards that are not specific to a major version of Drupal.

* [Develop for Drupal](https://www.drupal.org/docs/develop) - Work with the API, JavaScript, and databases. Learn the Drupal coding standards. Audience: developers.
* [API Reference](http://api.drupal.org/) - Search the complete Drupal API including forms, menus, node access, theme system, etc.
* [Examples for Developers](http://drupal.org/project/examples) - Examine a standard repository of sample modules that can be used to learn module development, or are referenced on handbook pages.
* [Glossary](https://www.drupal.org/docs/7/understanding-drupal/glossary) - Find definitions of Drupal terminology and acronyms.
* [Code snippets](https://www.drupal.org/documentation/customization/snippets) - Reuse chunks of Drupal code that people have shared with the community.
* [Troubleshooting](https://www.drupal.org/troubleshooting) - Identify and solve problems with servers, page display, permissions, logins, etc.
* [FAQs](https://www.drupal.org/drupal-faq) - Learn about documentation, licensing, the Drupal Association, community, etc.
* [Tutorials and recipes](https://www.drupal.org/node/627198) - Find miscellaneous information contributed by other Drupal users.
* [Resource guides](https://www.drupal.org/resource-guides) - A collection of resources and tools for building Drupal websites.
* [Local Development Guide](https://www.drupal.org/docs/official_docs/en/_local_development_guide.html) - The purpose of this guide is to assist you with creating and installing a new Drupal application on your local machine for the purpose of development.

## Distributions

Distributions are complete templates, usually specialized for various end users: restaurant, school, non-profit, blog, farm, ...

* [Droopler](https://www.droptica.com/blog/how-build-website-without-coding/)
* [Gatsby Templates](https://www.gatsbyjs.com/starters/smakosh/gatsby-portfolio-dev/) Not Drupal.  But something to keep in mind.
* [Envato](https://elements.envato.com/cms-templates/drupal)  Pay site for templates.
* [ELMS](http://www.elmsln.org) - ELMS Learning Network.
* [Julio](https://www.drupal.org/project/julio) - Julio is a distribution targeted for schools, school districts, small colleges, and academic departments within universities.
* [Open Academy](https://www.drupal.org/project/openacademy) - OpenAcademy is a Drupal distribution that brings the best in web publishing for higher education on a customizable Drupal platform. This distribution is a flexible, extendable package that lets university departments run fully functional, polished websites straight out of the box.
* [Open Scholar](http://theopenscholar.org) - OpenScholar is an open source SaaS platform built as a Drupal distribution. A single OpenScholar install hosts thousands of easy, self-service, custom websites. Features multiple domain names, dozens of built-in themes, drag-and-drop layout, best-practice presets and "apps" that solve virtually every use case.
* [Panopoly](https://www.drupal.org/project/panopoly) - Panopoly is powerful base distribution of Drupal powered by lots of Chaos Tools and Panels magic. The distribution is designed to be both a general foundation for site building and a base framework upon which to build other Drupal distributions.
* [NodeStream](http://www.nodestream.org) - NodeStream gives your organisation a standardized platform for online solutions.
* [OpenPublish](http://openpublishapp.com) - OpenPublish is a flexible and powerful solution designed for the online news industry. It is built for customization and extension – a powerful CMS to help publishers focus on the thing that matters the most: their content.
* [Drupal Commons](https://www.drupal.org/project/commons) - Drupal Commons is a ready-to-use solution for building either internal or external communities. It provides a complete social business software solution for organizations.
* [Open Atrium](http://openatrium.com) - Open Atrium is open source collaboration software that enables organizations to securely connect their teams, projects, and knowledge. A powerful solution, Open Atrium’s framework allows your organization to easily integrate your existing software, while remaining flexible enough to change as your organization grows. With Open Atrium, you can better communicate, educate, and inform your organization by creating solutions such as an intranet, social collaboration platform, web portal, or learning management system.
* [Drupal Rooms](http://www.drupalrooms.com) - Drupal Rooms is a Drupal 7 booking & room management solution for hotels and other accommodations - anywhere rooms reservations are required, including conferences, hospitals, vacation rentals, B&B's & more.
* [Commerce Kickstart](https://www.drupal.org/project/commerce_kickstart) - Commerce Kickstart is the quickest way to get up and running with Drupal Commerce. It includes the latest versions of Drupal core, Drupal Commerce, and the other modules it depends on. It also gives you a set of options to create a fully-featured demo store out of the box complete with an attractive theme, catalog and search configuration, and a custom back office interface.
* [Open Deals](https://www.drupal.org/project/opendeals) - Open Deals is a Free Deals Site distribution, based on Drupal 7, Drupal Commerce and other modules.
* [Spark](https://www.drupal.org/project/spark) - Spark is a Drupal distribution which aims to work out solutions to authoring experience problems in the field and apply to latest development versions of Drupal. Therefore our work started implementing improvements as modules on Drupal 7 and then our focus shifted to working on incorporating and enhancing them in Drupal 8 for core inclusion.

## Security

* [Hacked!](https://www.drupal.org/project/hacked) - This module scans the currently installed Drupal, contributed modules and themes, re-downloads them and determines if they have been changed. Changes are marked clearly and if the diff module is installed then Hacked! will allow you to see the exact lines that have changed.
* [Security Review](https://www.drupal.org/project/security_review) - The Security Review module automates testing for many of the easy-to-make mistakes that render your site insecure.
* [Drupalgeddon](https://www.drupal.org/project/drupalgeddon) - Drupalgeddon (with an "L") checks for backdoors and other traces of known Drupal exploits of "Drupageddon" (no "L"), aka SA-CORE-2014-005 SQL injection.
* [Site Audit](https://www.drupal.org/project/site_audit) - Site Audit is a Drupal static site analysis platform that generates reports with actionable best practice recommendations.

## Javascript libraries

## Modules
### Administration

* [Navbar](https://www.drupal.org/project/navbar) - A very simple mobile friendly navigation toolbar introduced as part of the Spark project to solve mobile editing problems with the Drupal 7 shipped toolbar, that is not very friendly to small screen sizes.
* [Administration menu](https://www.drupal.org/project/admin_menu) - Provides a theme-independent administration interface (aka. navigation, back-end). It's a helper for novice users coming from other CMS, a time-saver for site administrators, and useful for developers and site builders.
* [Features](Features) - The features module enables the capture and management of features in Drupal. A feature is a collection of Drupal entities which taken together satisfy a certain use-case.

### Developers

* [php_error](https://www.drupal.org/project/php_error) — Error reporting done right!
* [Backup & Migrate](https://www.drupal.org/project/backup_migrate) - Back up and restore your Drupal MySQL database, code, and files or migrate a site between environments. Backup and Migrate supports gzip, bzip and zip compression as well as automatic scheduled backups.
* [Devel](https://www.drupal.org/project/devel) - A suite of modules containing fun for module developers and themers ...
* [Drush + drush make](https://github.com/drush-ops/drush) - Drush is a command-line shell and scripting interface for Drupal, a veritable Swiss Army knife designed to make life easier for those who spend their working hours hacking away at the command prompt.
* [Stage file proxy](https://www.drupal.org/project/stage_file_proxy) - Stage File Proxy saves you time and disk space by sending requests to your development environment's files directory to the production environment and making a copy of the production file in your development site. You should not need to enable this module in production.
* [Diff](https://www.drupal.org/project/diff) - This module adds a tab for sufficiently permissioned users. The tab shows all revisions like standard Drupal but it also allows pretty viewing of all added/changed/deleted words between revisions.
* [Environment Indicator](https://www.drupal.org/project/environment_indicator) - This module will help you to keep sane while working on your different environments by adding a configurable color bar to each one of your environments.

### Site building

* [Address Field](https://www.drupal.org/project/addressfield) - Address Field defines a new field type to store international postal addresses, implementing a subset of the top-level address elements defined in the xNAL standard (see the glossary below).
* [Administration Views](https://www.drupal.org/project/admin_views) - Replaces administrative overview/listing pages with actual views for superior usability.
* [Views Bulk Operations (VBO)](https://www.drupal.org/project/views_bulk_operations) - This module augments Views by allowing bulk operations to be executed on the displayed rows. It does so by showing a checkbox in front of each node, and adding a select box containing operations that can be applied. Drupal Core or Rules actions can be used.
* [Date](https://www.drupal.org/project/date) - This package contains both a flexible date/time field type Date field and a Date API that other modules can use.
* [Email Field](https://www.drupal.org/project/email) - This module provides a field type for email addresses.
* [Entity Reference](https://www.drupal.org/project/entityreference) - Provides a field type that can reference arbitrary entities.
* [Relation](https://www.drupal.org/project/relation) - Relation is an API module and storage model for both simple and the most complex relations between entities. The module can handle both directional and symmetrical relations very well.
* [Field collection](https://www.drupal.org/project/field_collection) - A field collection is internally represented as an entity, which is embedded in the host entity. Thus, if desired field collections may be viewed and edited separately too.
* [Field Group](https://www.drupal.org/project/field_group) - Fieldgroup will, as the name implies, group fields together. All fieldable entities will have the possibility to add groups to wrap their fields together. Fieldgroup comes with default HTML wrappers like vertical tabs, horizontal tabs, accordions, fieldsets or div wrappers.
* [File Field Sources](https://www.drupal.org/project/filefield_sources) - FileField Sources is an extension to the FileField module. The FileField module lets you upload files from your computer through a CCK field.
* [Image Link Formatter](https://www.drupal.org/project/image_link_formatter) - This module is the result of the discussions around a requested feature to allow an image field to be displayed with a link to a custom URL.
* [Link](https://www.drupal.org/project/link) - Allows you to add ‘link’ fields to content and has Views integration.
* [Media](https://www.drupal.org/project/media) - The Media module provides an extensible framework for managing files and multimedia assets, regardless of whether they are hosted on your own site or a 3rd party site - it is commonly referred to as a 'file browser to the internet'.
* [Menu block](https://www.drupal.org/project/menu_block) -  It provides configurable blocks of menu trees starting with any level of any menu.
* [Module Filter](https://www.drupal.org/project/module_filter) - The modules list page can become quite big when dealing with a fairly large site or even just a dev site meant for testing new and various modules being considered.
* [Panels](https://www.drupal.org/project/panels) - The Panels module allows a site administrator to create customized layouts for multiple uses. At its core it is a drag and drop content manager that lets you visually design a layout and place content within that layout. Integration with other systems allows you to create nodes that use this, landing pages that use this, and even override system pages such as taxonomy and the node page so that you can customize the layout of your site with very fine grained permissions.
* [Panelizer](https://www.drupal.org/project/panelizer) - The panelizer module allows you to attach panels to any node in the system. It is similar to the panels_node module that ships with Panels, which provides a single node type that is a panel. Panelizer, however, allows this to work for many entity types. It works by using the Page Manager template to take over the page rendering of the node.
* [Pathauto](https://www.drupal.org/project/pathauto) - The Pathauto module automatically generates URL/path aliases for various kinds of content (nodes, taxonomy terms, users) without requiring the user to manually specify the path alias. This allows you to have URL aliases like /category/my-node-title instead of /node/123. The aliases are based upon a "pattern" system that uses tokens which the administrator can change.
* [Rules](https://www.drupal.org/project/rules) - The Rules module allows site administrators to define conditionally executed actions based on occurring events (known as reactive or ECA rules). It's a replacement with more features for the trigger module in core and the successor of the Drupal 5 workflow-ng module.
* [Search API](https://www.drupal.org/project/search_api) - This module provides a framework for easily creating searches on any entity known to Drupal, using any kind of search engine. For site administrators, it is a great alternative to other search solutions, since it already incorporates facetting support and the ability to use the Views module for displaying search results, filters, etc. Also, with the Apache Solr integration, a high-performance search engine is available for this module.
* [Smart Trim](https://www.drupal.org/project/smart_trim) - Smart Trim implements a new field formatter for textfields (text, text_long, and text_with_summary, if you want to get technical) that improves upon the "Summary or Trimmed" formatter built into Drupal 7.
* [Views](https://www.drupal.org/project/views) - This is the reason why you are using Drupal. Views in now in Drupal 8 core.
* [Views RSS](https://www.drupal.org/project/views_rss) - This module allows users to take control of their feeds by providing a fields-based views style plugin for RSS.
* [Entityform](https://www.drupal.org/project/entityform) - The Entityform module enables you to create front-end forms (fieldable entities), which contain fields that you define! These forms use the standard Drupal fields.
* [Webform](https://www.drupal.org/project/webform) - Webform is the module for making surveys in Drupal. After a submission, users may be sent an e-mail "receipt" as well as sending a notification to administrators. Results can be exported into Excel or other spreadsheet applications. Webform also provides some basic statistical review and has and extensive API for expanding its features.

### Content

* [Feeds + Feeds Tamper + Feeds Xpath Parser](https://www.drupal.org/project/feeds) - Import or aggregate data as nodes, users, taxonomy terms or simple database records.
* [Flag](https://www.drupal.org/project/flag) - Flag is a flexible flagging system that is completely customizable by the administrator. Using this module, the site administrator can provide any number of flags for nodes, comments, users, and any other type of entity. Some possibilities include bookmarks, marking important, friends, or flag as offensive.

### E-Commerce

* [Commerce](https://www.drupal.org/project/commerce) - Drupal Commerce is used to build eCommerce websites and applications of all sizes. At its core it is lean and mean, enforcing strict development standards and leveraging the greatest features of Drupal 7 and major modules like Views and Rules for maximum flexibility.
* [Ubercart](https://www.drupal.org/project/ubercart) - Ubercart is the most popular Drupal E-Commerce platform for your website. It implements everything you need to start selling products online. Web Developers from all skill ranges can use it to support a variety of E-Commerce industries-- including physical goods, digital downloads, or even subscription based billing services.
* [Commerce Square](https://www.drupal.org/project/commerce_square) - Square is the payment / POS company making commerce easy and accessible to everyone. This module integrates with their eCommerce API for online payments into Drupal Commerce.

### Publishing

* [Nodequeue](https://www.drupal.org/project/nodequeue) - The Nodequeue module allows users to collect nodes in an arbitrarily ordered list.
* [Entityqueue](https://www.drupal.org/project/entityqueue) - The Entityqueue module allows users to create queues of any entity type. Each queue is implemented as an Entityreference field, that can hold a single entity type.
* [Linkit](https://www.drupal.org/project/linkit) - Linkit provides an easy interface for internal and external linking with editors and fields by using an autocomplete field. Linkit links to nodes, users, managed files, terms and have basic support for all entities by default.
* [Wysiwyg](https://www.drupal.org/project/wysiwyg) - Allows the use of client-side editors to edit content. It simplifies the installation and integration of the editor of your choice. This module replaces all other editor integration modules. No other Drupal module is required.

### SEO

* [Global Redirect](https://www.drupal.org/project/globalredirect) - A helpful SEO-based module that helps Drupal not appear to have duplicate URLs so that your site isn’t penalized by search engines.
* [Google Analytics](https://www.drupal.org/project/google_analytics) - Adds the Google Analytics web statistics tracking system to your website.
* [Metatag](https://www.drupal.org/project/metatag) - The Metatag module allows you to automatically provide structured metadata, aka "meta tags", about a website. In the context of search engine optimization, when people refer to meta tags they are usually referring to the meta description tag and the meta keywords tag that may help improve the rankings and display of a site in search engine results. In addition, the module provides support for meta tags (Open Graph Protocol from Facebook, Twitter Cards from Twitter) that allow control of how content appears when shared on social networks.
* [Redirect](https://www.drupal.org/project/redirect) - This module is critical for providing 301 redirects on your site.
* [XML Site Map](https://www.drupal.org/project/xmlsitemap) - The XML sitemap module creates a sitemap that conforms to the sitemaps.org specification. This helps search engines to more intelligently crawl a website and keep their results up to date. The sitemap created by the module can be automatically submitted to Ask, Google, Bing (formerly Windows Live Search), and Yahoo! search engines. The module also comes with several submodules that can add sitemap links for content, menu items, taxonomy terms, and user profiles.
* [Page Title](https://www.drupal.org/project/page_title) - This module is deprecated, all functionality is being moved into the Metatag module, an upgrade process is available and is being improved.

### Social Media
* [Facebook OAuth (FBOAuth)](https://www.drupal.org/project/fboauth) - This module provides authentication services and an API to perform actions against Facebook. This module allows users to login to Drupal through the service commonly known as "Facebook Connect". This module is built with simplicity and flexibility in mind, it provides login services (and does it well), and an API for performing any other actions you may want to write yourself to query against Facebook's APIs.
* [Twitter Block](https://www.drupal.org/project/twitter_block) - Twitter Block is a lightweight module which allows administrators to create
  blocks which display embedded timelines.
* [Twitter](https://www.drupal.org/project/twitter) - This module provides API integration with the Twitter microblogging service. Out of the box, it allows users to: Associate one or more Twitter accounts with their Drupal user account. List tweets in different ways thanks to Views. Post to their own Twitter account or a site-wide Twitter account whenever they create new content or based on Drupal Actions or Rules. Log in to your Drupal site via Twitter. Format twitter @usernames and #hashtags as links to Twitter.com. Search and post to Twitter via Drush commands. View embedded images media from tweets (not in 7.x-6.x branch yet).
* [AddThis](https://www.drupal.org/project/addthis) - Provides an AddThis.com button or toolbox to let your users share your content to social network sites.

### Theming

* [jQuery Update](https://www.drupal.org/project/jquery_update) - Upgrades the version of jQuery in Drupal core to a newer version of jQuery.

### Users

* [Redirect 403 to User Login](https://www.drupal.org/project/r4032login) - Very handy module for access denied pages.

### Utility / API Modules

* [Chaos tool suite (ctools)](https://www.drupal.org/project/ctools) - This suite is primarily a set of APIs and tools to improve the developer experience. It also contains a module called the Page Manager whose job is to manage pages. In particular it manages panel pages, but as it grows it will be able to manage far more than just Panels.
* [Entity API](https://www.drupal.org/project/entity) - This module extends the entity API of Drupal core in order to provide a unified way to deal with entities and their properties. Additionally, it provides an entity CRUD controller, which helps simplifying the creation of new entity types.
* [Entity cache](https://www.drupal.org/project/entitycache) - Entity cache puts core entities into Drupal's cache API.
* [File entity (fieldable files)](https://www.drupal.org/project/file_entity) - File entity provides interfaces for managing files. It also extends the core file entity, allowing files to be fieldable, grouped into types, viewed (using display modes) and formatted using field formatters. File entity integrates with a number of modules, exposing files to Views, Entity API, Token and more.
* [Libraries API](https://www.drupal.org/project/libraries) - The common denominator for all Drupal modules/profiles/themes that integrate with external libraries.
* [Strongarm](https://www.drupal.org/project/strongarm) - Strongarm gives site builders a way to override the default variable values that Drupal core and contributed modules ship with. It is not an end user tool, but a developer and site builder tool which provides an API and a limited UI.
* [Token](https://www.drupal.org/project/token) - Tokens are small bits of text that can be placed into larger documents via simple placeholders, like %site-name or [user]. The Token module provides a central API for modules to use these tokens, and expose their own token values.
