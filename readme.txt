=== FrankenCookie ===
Contributors: itthinx
Donate link: http://www.itthinx.com/plugins/frankencookie
Tags: bureaucracy, compliance, cookie, cookie law, cookies, eu, eu cookie directive, eu cookie law, nonsense, law, privacy, regulation, stupid, useless 
Requires at least: 3.5.1
Tested up to: 3.8
Stable tag: 1.0.2
License: GPLv3

FrankenCookie provides a widget that offers visitors an explanation about cookies being placed on their computer.

== Description ==

FrankenCookie provides a widget that offers visitors an explanation about cookies being placed on their computer.
The widget provides a default text which can be customized. It also provides a button that visitors can click so that the widget does not appear again as long as the FrankenCookie is found when the visitor browses the site.

_"Beware, for I am fearless and therefore powerful."_ - the monster

### Feedback ###

Feedback is welcome!

If you need help, have problems, want to leave feedback or want to provide constructive criticism, please do so here at the [FrankenCookie plugin page](http://www.itthinx.com/plugins/frankencookie/).

Please try to solve problems there before you rate this plugin or say it doesn't work. There goes a _lot_ of work into providing you with free quality plugins! Please appreciate that and help with your feedback. Thanks!

#### Twitter ####

[Follow @itthinx on Twitter](http://twitter.com/itthinx) for updates on this and other plugins.

### Translations ###

* If you would like to help translate the plugin, please get in touch at the [FrankenCookie plugin page](http://www.itthinx.com/plugins/frankencookie/).

== Installation ==

1. Upload or extract the `frankencookie` folder to your site's `/wp-content/plugins/` directory. You can also use the *Add new* option found in the *Plugins* menu in WordPress.  
2. Enable the plugin from the *Plugins* menu in WordPress.
3. Drag the FrankenCookie widget under *Appearance > Widgets* to a sidebar.
4. Customize the widget's text if you want to.

== Frequently Asked Questions ==

= I have a question, where do I ask? =

You can leave a comment at the [FrankenCookie plugin page](http://www.itthinx.com/plugins/frankencookie/).

= Does it work with caching plugins? =

Yes. FrankenCookie renders the content of the widget and hides it with Javascript that checks if the `frankencookie` cookie (*yummy*) is present.
If it is found, it hides the widget's content.
As what is rendered does not change, it doesn't matter whether a caching mechanism is used or not.
What changes is the behaviour based on the cookie. Of course this will only work if the visitor has Javascript enabled.
Those that don't will always see the message.

= How does this impact my site's performance? =

Tests with [P3](http://wordpress.org/extend/plugins/p3-profiler/) show that the plugin's execution time is about 1-2% of WordPress' core.
Well, still a small price to pay compared to the abysmal nonsense of *some* regulations.

= How can I style the widget? =

The widget can be styled quite easily using CSS rules.

- the widget's CSS class is `frankencookie` 
- the message is wrapped in a `div` with class `message`
- the link to hide the message is also in a div with class `hide`

Example - show the message at a fixed position at the bottom of the page:

`.frankencookie {
    font-size: 11px;
    margin-top: 2px;
    text-align: center;
    position: fixed;
    bottom: 0;
    color: #f0f0f0;
    background-color: #000;
    z-index: 10000;
}
.frankencookie .message,
.frankencookie .hide {
    display: inline;
    margin: 2px;
}
.frankencookie .hide a {
    color: #fff;
    padding: 2px;
    font-weight: bold;
}
.frankencookie .hide a:hover {
    background-color: #999;
    color: #111;
}`

== Screenshots ==

1. FrankenCookie Widget Settings
2. Example FrankenCookie Widget Appearance

== Changelog ==

= 1.0.2 =
* WordPress 3.8 compatibility checked

= 1.0.1 =
* WordPress 3.6 compatibility checked

= 1.0.0 =
* Initial release.

== Upgrade Notice ==

= 1.0.2 =
* WordPress 3.8 compatibility checked

= 1.0.1 =
* WordPress 3.6 compatibility checked

= 1.0.0 =
* Initial release.

