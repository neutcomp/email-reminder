=== Email Reminder ===
Contributors: pogidude
Donate link: http://pogidude.com/donate/
Tags: email reminder, reminder
Requires at least: 3.0
Tested up to: 3.2
Stable tag: 0.1

Schedule email reminders. Enter your reminder, where you'd like to email the reminder to, and when you'd like the reminder to be sent.

== Description ==

This plugin allows you to send email reminders to any email address on the date and time that you specify. So, basically, all you have to do is to enter your reminder, enter the email address you'd like to send the reminder to, and when you'd like the reminder to be sent. 

That's it.

[Email Reminder Plugin Page](http://pogidude.com/email-reminder/)

If you enjoyed using Email Reminder and find it useful, please consider [__making a donation__](http://pogidude.com/donate/). Your donation will help encourage and support the plugin's continued development and better user support.

== Installation ==

1. Download the zip-archive and extract it into your computer.
2. Upload the entire email-reminder folder to the /wp-content/plugins/ directory in your web site.
3. Activate the plugin through the 'Plugins' menu in your WordPress administration page.

You will find a new "Email Reminder" sub-menu under the "Dashboard" menu at the very top.

== Frequently Asked Questions ==

= The reminder does not get sent on the exact date and time or the reminder is not sent at all =

The plugin uses WordPress cron scheduler (WP Cron) to periodically check for reminders to be sent. Unfortunately, WP Cron is not a real cron scheduler like the one found in Linux operating systems which can run commands and scripts on time. WP Cron depends on users visiting your web site in order to trigger WP Cron. This means that by default, reminders won't always get sent on the exact time you want. This is most noticeable on sites with very low traffic.

But, there is a way to work around this problem by leveraging real Linux cron instead. Find out how by [reading this tutorial](http://pogidude.com/2011/use-linux-cron-to-trigger-wordpress-cron-scheduler/)

== Screenshots ==

1. Screenshot of email reminder interface
2. Screenshot of list of scheduled reminders

== Changelog ==

= 0.1 =
* Original Version.

== Upgrade Notice ==
Original Version.
