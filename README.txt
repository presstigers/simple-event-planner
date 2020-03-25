### Simple Event Planner

The plugin is available in English, Russian(Русский), German(Deutsch), Polish(Polski) and Serbian(Српски језик).

Simple Event Planner by <a href="https://www.presstigers.com">PressTigers</a> is a next generation, lightweight event management plugin that list WP events and calendar to your WordPress website.

This plugin is used to manage & display various events within the site. It has various options, including events from different categories. Whether you have; a single event or multiple events, you can display it as a list or in calendar format by simply inserting shortcode i.e. [event_listing], [event_calendar]. 

### Event Listing Shortcode
```
[event_listing]
```

### Event Calendar Shortcode
```
[event_calendar]
```

### Plugin Features

* Create Events Quickly
* Time Zone Settings for Events
* Unlimited Event Segments
* Show/Hide Event's Options
* List View
* Grid View
* Calendar View
* Search Event by Title (List View)
* Search Event by Location (Calendar View)
* Events Categories (Taxonomies)
* Responsive Layout
* Localization (Translation Ready)
* Unlimited Color Combinations
* Shortcode Builder
* Google Maps for Event Location
* Template Layout Settings
* Image Enable/Disable
* Time Format Settings
* Date Format Settings
* iCal Calendar
* Google Calendar
* Visual Layout Settings

## Installation

1. Upload `simple-event-planner.zip` to the `/wp-content/plugins/` directory to your web server.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Add a standard WordPress page or post and use [event_listing] shortcode in the editor to make it events list.
1. Add a standard WordPress page or post and use [event_calendar] shortcode in the editor to make it event calendar.

### Event Planner Templating

With event planner templating exciting feature you can change the following file templates.

* content-wrapper-start.php
* content-wrapper-end.php
* event-listings-start.php
* event-listings-end.php
* content-event-listing.php
* content-no-events-found.php
* content-single-event-listing.php
* event-schedule.php
* event-description.php
* event-details.php
* event-venue.php
* single-event-listing.php
* event-search.php
* calendar-search.php
* archive-event-listing.php
* event-pagination.php

1. To change a template, please add "simple_event_planner" folder at default theme root directory.
1. Add above mentioned file from plugin simple-event-planner > public > partials folder keeping the same file directory structure (as mentioned in the header of each file) and customize it based on your needs.

= Can you contribute? =
If you are an awesome contributor to translations or plugin development, please contact us at support@presstigers.com

### Frequently Asked Questions

How to create event list?
In your WordPress admin panel, go to "Event Planner" menu and add a new event. All the event listing will be shown in the admin panel and on the front-end.

How to show event list on the front-end? 
To list all the event list, add  [event_listing] shortcode in an existing page or add a new page and write shortcode anywhere in the page editor.

How to change the layout of event listing using a shortcode? 
To change the event listing view, add [event_listing events_layout="grid"] or [event_listing events_layout="list"] shortcode in an existing page or add a new page and write shortcode anywhere in the page editor.

How to show event calendar on the front-end?
To list event calendar , add [event_calendar] shortcode in an existing page or add a new page and write shortcode anywhere in the page editor.

Can I display event list for particular "category" using a shortcode? 
Yes, you can use shortcode on post/page i.e [event_listing event_category="category-slug"]

Can I show event list of Calendar for particular "category" using a shortcode?
Yes, you can use a shortcode on post page i.e , [event_calendar event_category="category-slug"]

Can I show only 5 latest events on front-end with pagination?
Yes, you can show any number of events on your website with pagination feature by using shortcode with "events_limit" attribute i.e. [event_listing events_limit="5"]

Can I show only 5 latest events of a calendar on front-end? 
Yes, you can show any number of events on your website by using shortcode with "events_limit" attribute i.e [event_calendar events_limit="5"]

Can I turn off calendar search bar?
Yes, you turnoff search bar with "search" attribute i.e [event_calendar search="false"]

Can I turn off event list search bar?
Yes, you can turn off search bar with "search" attribute i.e [event_listing search="false"]

### Changelog

= 1.5.0 =

* Feature - Added custom option to add a custom date format.
* Feature - Added custom option to add a custom slug for events.
* Feature - Localize the event calendar strings.
* Tweak - Fixed typo issues.
* Tweak - Fixed padding issues on mobile devices.
* Fix - Fixed the start and end date language for event listing.
* Fix - Removed event counter for past events.
* Fix - Fixed the Site Health issues.
* Fix - Fixed the plugin jQuery issues with Twenty Nineteen and Twenty Twenty theme.
* Tweak - Fixed the "GMAP API key" string in all .po files.
* Note - Removed the Facebook feature.
