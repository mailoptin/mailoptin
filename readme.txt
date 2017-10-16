=== MailOptin - Grow & Engage Your Email List ===
Contributors: MailOptin
Tags: popup, optin forms, newsletter, mailchimp, aweber, constant contact, campaign monitor, convertkit, activecampaign, drip, sendy, mailerlite, mailerlite form, top bar, wordpress popup, getresponse, getresponse360, lightbox, modal, optin, optin form, subscribe, email list, after post optin form, lead capture, sidebar widget, sidebar form, emailoctopus, email octopus, exit-intent, pop up, exit intent, elementor, mailchimp form, mailchimp newsletter, mailchimp plugin, mailchimp signup, mailchimp signup form, mailchimp optin form, mailchimp widget, widget form, subscribe form, new post notification, constantcontact, mailpoet, aweber form, aweber forms, aweber signup form, lead generation, sendy form, mailing list, opt-in, hello bar, hellobar, scrolltrigger, scroll trigger, new post notification, elementor form, newsletters, optinmonster, icegram, slide box, slide in, slidein
Requires at least: 4.0
Tested up to: 4.9
Stable tag: 2.1.6.0
License: GPL-2.0+

Grow and engage your email list.

== Description ==
Best lead Generation, Email Automation & Newsletter WordPress Plugin.

== Frequently Asked Questions ==
See the website for more info https://mailoptin.io

== Changelog ==

= 2.1.6.0 =
* Added: GetResponse and GetResponse360 integrations.
* Added: optin campaign schedule.
* Changed all checkbox control to toggle switch.
* Fixed bug where TinyMCE field preview wasn’t working in form/template builder.
* Fixed bug where clearing local cookies didn't clear that of successful optin conversion.
* Fix compatibility issues with upcoming WordPress 4.9

= 2.1.5.0 =
* Added after conversion actions feature: close optin, close optin and reload page, redirect to URL.
* Added Action hook triggered after optin subscription.
* Reverted change to limit_text() from wp_trim_words.
* Removed older hide_logged_in rule from form builder.
* Added: toggling of optin form close button.
* Burst connection email list cache after every settings change.
* Optimized all image assets.
* Added class_exist check to MailPoet API class before usage to prevent any PHP error.
* Added missing semi-colon to optin template tag code copy in form builder.

= 2.1.4.0 =
* Added MailPoet 3 integration.
* Added support for tags to Aweber subscribers.
* Optin background image and logo support land in customizer.
* listing of optin and email campaign now in descending order
* Fixed bug where undefined webfont js function causes optin not to display.
* Fixed bug that prevent highlighting of active tab in settings page.
* Added: shortcode and template tag embed of optin.
* replace custom function for trimming text with wp one
* All text-shadows be gone from every submit buttons in optin forms.
* Simplified connections composer packaging.
* Loads of performance enhancements
* Code improvements.

= 2.1.3.0 =
* Added ActiveCampaign integration.
* Listing of optin and email campaign now displays the newest to oldest.
* Added styling to pre tag in email template..
* Added switch to toggle optin campaigns activation.
* Global success and interaction cookies rule implemented. Was previously missing.
* New display rule: Optin display can now be determined based on whether users are logged in or not.
* Added support for click triggered (2-step optin process).
* Added refreshing styling to customizer controls.
* "Footer Description" changed to "mailing address" in optin customizer.
* Added check to ensure jQuery.MailOptin and jQuery.MailOptin.track_impression is defined to prevent any error.
* Fixed bug where custom fields associated with a connect/esp do not show on initial customizer UI page load.
* Loads of performance enhancements
* Code improvements.

= 2.1.2.0 =
* Added integration for Drip (Email Marketing Automation Software).
* Added ConvertKit integration.
* Added EmailOctopus integration.
* Added button to clear optin caches.
* Added settings to change optin branding url with affiliate link.
* Added impression tracking to inpost optin forms.
* Missing close icon now display on all optin types after subscription success.
* Fixed js bug that affected safari browsers when customizer is opened.
* Connections now implement the features_support() interface contract.
* Code improvements and performance enhancements.

= 2.1.1.1 =
* Improve compatibility with MySQL versions less than 5.6.5
* Fixed bug where MailChimp subscription wasn't working.

= 2.1.1.0 =
* Added Elementor form element integration.

= 2.1.0.1 =
* Fixes to some internal APIs.

= 2.1.0.0 =
* the genesis.
