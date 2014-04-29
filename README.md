Rails 4.1.x - ActionPack Variants Example
=================================================================================================

This is a standalone Rails 4.1.x application that shows you how
to use ActionPack Variants to render different views depending on
the users device.

This is tremendously useful because you can now serve a much slimer
version of your view to mobile devices, instead of just hiding the
elements using CSS using media queries.

Hidden elements still load and need to come down 'the wire' - using
Variants it's much easier than before to serve up lean and mean views
to mobile devices.


Getting Started?
------------------

Read the official Documentation first and foremost - then dig into
the code in this example application.

http://edgeguides.rubyonrails.org/4_1_release_notes.html#action-pack-variants


How to run locally?
-------------------

Install the bundle and run the rails server:

    bundle install

    rails s

    localhost:3000

You're going to need to use a user-agent switcher to see the various
views. I recommend:

For Firefox: https://addons.mozilla.org/en-US/firefox/addon/user-agent-switcher/

For Chrome: https://chrome.google.com/webstore/detail/user-agent-switcher-for-c/djflhoibgkdhkhhcedjiklpkjnoahfmg
