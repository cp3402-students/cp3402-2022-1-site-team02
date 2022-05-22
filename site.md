# Site Development Overview

## Site Overview 

To allow for ease of future modification of this Wordpress site, the following overview will attempt to outline the site's layout,
logic, widgets, and other features. The site itself is composed of pages and posts, each allowing for different kinds of customisation.
The following main sections (PAGES) and their subsequent posts and features are listed here:

### Pages

1. **HOME**: The home page is the landing page of your website. It is where new viewers will come by default. The current home page 
contains a welcome message and image (added as a BLOCK text/image combination), and the button inside this BLOCK is linked to your
SIGN-UP page, and can be relinked as needed via the Wordpress editor. The image is pulled from the NexGen gallery plugin and can be changed from there.
The home page, as with most other PAGES, contain the various sidebar PLUGINS that provide some custom features to the site.
2. **EVENTS**: The events page comes from a specific plugin, "The Events Calendar", and shows a full-sized monthly calendar listing whatever
events you have currently created with a clilckable link should users require more information. The actual events can be added and editing inside the plugin itself.
If you would rather EVENTS to be a seperate page and the calendar to be added as a POST, you can edit the events page "slug" to be something other than "events".
3. **MEMBERSHIP**: The membership page is relatively basic, containing a text BLOCK containing your membership information and a call-to-action button that links
to your sign-up PAGE. The sign up PAGE is hidden from the main menu otherwise.
4. **ABOUT**: The about PAGE is your content-heavy page, containing a large BLOCK that contains a number of POSTS. These POSTS contain image galleries, jazz information,
and band information. Clicking on any of these linked icons will take you to the corresponding POST.
5. **CONTACT**: Your contact page contains a block of text and various images and icons situated in a BLOCK. These can be edited
directly from Wordpress. The displays your location, members, and contact details. The map image links to Google Maps.
6. **Sign-Up**: Your sign-up page is hidden by default, but can be added to the main menu if desired. It contains a post that is a registration
form created via the "User Registration" plugin. Users can fill out the form found here and a subsequent email will be sent to the registered mailbox.

### Posts

For this site, your posts make up the majority of your "About" page content. Each band, article, and photo gallery is a separate post, each of which can be 
modified and added to the page using the BLOCK editor or various plugins. On this site, posts have their own category to easily differentiate them from one
another and allow for easy sorting. The current post categories are:
1. **ARTICLE**: The Article is (so far) only used for the Jazz Radio information, but the category itself is for any posted information that does not currently
align with any of the existing categories. In the future, use articles for any long-written commentary or advertisements on the site.
2. **BANDS**: The Bands category is currently used in the About page and contains information regarding current bands, their history
with the club, and contains a short informational blerb and embedded video. If any bands join later on, create a Band post and attach it to the
existing space on the About page.
3. **Events**: The Events category (and its posts) are only used when not using the Events Calendar plugin. A test post has been provided in this category
for reference, but at this all events should be created within the plugin itself.
4. **History**: Posts in the History category are used on the About page for jazz history and club history posts.
5. **PHOTOS**: Posts with the Photos category are done by year and contain a single NextGen Gallery album (also for that year). You can use
this category for the yearly albums or create them for special events.

### Plugins
Wordpress uses Plugins to gain additional functionality, features, and tools that are not theme-specific, meaning you could use the
same theme and end up with entirely different sites in terms of function and potential. It is important to note that much of the functionality and plugins can be found in the sidebar widget area. For this site we took advantage of a number of useful plugins
to enhance the site. Each plugin, its use, and any useful details can be found below:

1. **All-in-One WP Migration**: This plugin offers a quick way to export and import both site files and database files, making it a great way to update your site from the DEV space to LIVE; simply 
export your files on DEV and import them using the matching plugin on the PROD (live) site. Different versions of the plugin can handle different payloads; the one currently loaded works with 512mb of data.
You can find more information on the plugin and extra features for premium use here: https://wordpress.org/plugins/all-in-one-wp-migration/
2. **Elementor**:
3. **Elementor Header & Footer Builder**:
4. **Forminator**:
5. **Git Updator**:
6. **NextGEN Gallery**: NextGEN Gallery is used a secondary media manager for the site is used to create and build image galleries on the About page. Within the plugin space, add images to galleries, then add those
galleries to albums. You can create Galleries for certain years, events, bands, and similar then wrap all of them into the album. In this case, we simply created a gallery for each year. Gallery styles, how thumbnails are displayed,
and other features are also managed within the plugin. More information on NextGEN and possible premium features can be found here: https://wordpress.org/plugins/nextgen-gallery/
7. **Online Radio Box**: Online Radio Box was used to add the radio player for the Jazz station to the sidebar. It uses an embed code (currently found in the sidebar widget) that can be put in any post, block, or other area. It is currently set
to the same radio station from the initial TSVJazz website. It opens up a secondary player that users/visitors must click to play the music. It is not set to autoplay on loading the website. Full information on the player can be found here: https://onlineradiobox.com/widgets/#player-au-triplet
8. **Smash Balloon Custom Facebook Feed**: Smash Balloon's facebook feed plugin was used to attach the TSVJazz facebook page to the sidebar widget, allowing visitors to see recent posts, photos, and other information from the facebook page's timeline. It is important to note that the plugin requires administrator
access to the facebook page, so a demo page was used in this instance until handover. Once handover is complete, the site administrator would simply need to update the page URL and sign in to facebook to complete the change. Premium versions of this plugin can show other features of the facebook page
and could have potential to link events and featured comments to visitors. Premium features and other information can be found here: https://wordpress.org/plugins/custom-facebook-feed/
9. **The Events Calendar**: Events Calendar is used to create events, venues, hosts, and locations to add to the Events page. Currently, a few events (both real and demo) have been added and can be updated for future events. Creating an event is simple, with the ability to select from pre-created event details (hosts, times, locations, price, host)
and automatically feature them in the calendar. Featured events can be marked and all recent events are added to the "recent events" section of the sidebar widget. Important premium features have the ability to add ticket purchasing to events and the ability to create reoccurring events (perfect for the junior jazz session). Information regarding Events
Calendar can be found here: https://wordpress.org/plugins/the-events-calendar/
10. **User Registration**:
11. **WP Pusher**: