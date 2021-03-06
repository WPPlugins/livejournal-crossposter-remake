=== Livejournal Crossposter Remake ===
Contributors: tygernach
Donate link: https://github.com/tygernach/wp_lj_crossposter_remake
Tags: livejournal, lj, text, rss, post, posts, crosspost
Requires at least: 2.5
Tested up to: 3.4
Stable tag: 1.3.1
License: GPLv2 or later

Automatically copies all posts to a LiveJournal or other LiveJournal-based blog. Optionally adds link to crossposted LiveJournal entry.

== Changelog ==
Differences from LiveJournal Crossposter Remix:
1. Crosspost privacy depends on 'ljxp_privacy' custom field or (if not set) on  original WP post visibility.
2. Add option to show link to crossposted LJ entry.


== Description ==

Automatically copies all posts to a LiveJournal or other LiveJournal-based blog (exclude text in shortcode [nocrosspost]smth[/nocrosspost] - buttons for it added in visual&html editors). Editing or deleting a post will be replicated as well.
Crosspost entry privacy depends on:
1. WP custom post field 'ljxp_privacy' value. It can be 'public', 'friends' or 'private'.
2. If 'ljxp_privacy' not set, plugin will use post visibility settings: public = public, password protected = friends only, private = only me.
Please notice that by default private entries wouldnt be crossposted at all.
Optionally adds link to crossposted LiveJournal post.

Original plugins by Arseniy Ivanov, Evan Broder and Sergey M.


== Installation ==

1. Upload plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin 'Livejournal Crossposter Remake' through the 'Plugins' menu in WordPress

== Changelog ==
v.1.3.1:
Small fix - may save you if you've recieved "couldn't open socket error" error. Or may not - the reason for  this error can be different.

v.1.3:
Fix post LJXP meta properties block (you can find it at the bottom of the page).

v.1.2:
In case of crosspost errors will show id and link to 'wrong' post.
Fix links to tinymce editor.

v.1.1:
Fix php error described here http://wordpress.org/support/topic/php53-and-fastcgi-on-iis-with-wordpress
