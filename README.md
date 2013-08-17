exalted-platform
================

Discussions about functionality for an exalted platform. Both somewhat technical discussions and just "good to have".

Feel free to add ideas on things, etc.

You can help! We're going to need quite a few different kind of characters to test out code on, so here's how to put
those in:

1. [Install Anathema](http://anathema.github.io/)
2. In theory, [this folder on Dropbox](https://www.dropbox.com/sh/httj4f1lxv2k43r/RNJvAiBYje) should be shared to upload
named zip-files (I'd suggest your name and something unique, to avoid clashing)
3. To export characters, create a new on in Anathema and then *close it* before you try to use the menu to export. It 
will save as a zip-file called Export.zip, so rename that

**Some notes**

## Platform #
Written in PHP and Ember. JavaScript is used when things are dynamic, as in can
be altered on the spot (through some means or another)

### User profile #
* Ability to pick blocks to show!
    * List of characters
    * Weather widget
    * Date/Time widget
    * List of associated players and the time in their timezones + last login
    * Current Moon widget
    * Latest news/occurances
* By allowing players to pick/choose their own profile/something, a lot of
screen realestate can be free
* Pick on the widget if you want it to be viewable by all, by yourself, or only visitors

### Combat helper #
* Tick counter
* Dice roller
* Mass combat statifier
* List of weapons/armour from character sheet with stats
* Option to show charms

### Characters #
* Written in Ember
* Consumes an Anathema exported file
* Exports to an Anathema file
* Password-protected to allow others to view sheet, possibly with connections
such as "my circle can view my sheet", "these selected people can view my sheet"
* XP requests should take place in the same area as the viewing of the character
* Character sheet should save while working on it, and show it in some way?
* Even if it does little, a "save all" button feels comforting
* Specialized character sheets, not generalized over all splats
* Charms/etc should show in the level that you have access to them, potentionally
with a way to state that you want to see the future-available things
* Tabs to flick through the various areas
* Explicit "publish my character" button, both on sheet and next to name in list

### Weather/Date/Moon widgets #
* Weather forecast
* Date with current time in SCT (Standard Chat Time) and IC time of day (SCT to
make it easier to plan)
* Conversion between RL/IC dates, only fully reliable between Calibrations as feature
* Current phase, time until full moon

### Diary #
* Notes written from perspective of either player or character, likely marked
up with those in some way
* Also, bluebooking, public or private depending on fancy

### News #

### Broadcasts/Notifications/Announcements #

### Inter-player Messaging #
* STs can send to many
* Groups can be sent to similarly

### XP-requests #
Both the kind that is automatically approved (option of "use justification from diary") and the kind that needs approval by the ST (Backgrounds, I'd imagine)

### Forums #
* Many-to-many conversations
* "chat rooms" that keep the conversation easily accessible (IE circle/pack forums)

### Calendar #
* Should be available for scene planning/etc
* Export as iCalendar
* Doesn't care about clashes, up to players/STs to figure out
* ST/Player can set "available time slots"
* ST/Player can set "booked scene"
* Invitations to specific scenes, messages to make players aware of them
* Planning is in Standard Chat Time
