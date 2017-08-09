=== bbPress Ignore User ===
Contributors: Forked by Tony Korologos, original plugin by master5o1
Donate link:
Tags: bbPress, bbPress, ignore user, block user, ignore, self-censorship
Requires at least: WP 4.5 / bbP 2.5.13
Tested up to: WP 4.8.1 / bbP 2.5.13
Stable tag: 0.3

Allow members of the forum to selectively have a user's posts and topics hidden from view.

== Description ==

Users can maintain their own personal ignore user list which is used to hide any posts or topics from that user.
While viewing a topic, the current user can ignore any of the reply authors by clicking an 'Ignore User' link under/near the author name.  This adds the author to the user's ignore list.
On the user's profile, the author can remove entries to their ignore list.

The user can forcibly show all ignored posts or topics by viewing the topic or forum with `?show_ignored_users` applied to the url (a link to show all posts and topics is given when posts are hidden).

Users who can moderate the forum cannot be ignored by any members and members cannot ignore themselves.

== Installation ==

1. Make sure you have bbPress 2.5 (or better) plugin activated.
2. Upload `bbpress-ignore-users` folder to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Question =

Answer

== Screenshots ==

1. Ignore/Unignore User link on the author side of a reply post.
2. Topics hidden from listing.
3. Ignore list can be maintained on the user's profile.

== Changelog ==

= 0.2 =

* Fixes some bugs.

= 0.1 =

* First release.

== Upgrade Notice ==

= 0.1 =

* None
