=== MailOptin - Grow & Engage Your Email List ===
Contributors: MailOptin
Tags: popup, wordpress popup, popup, newsletter, mailchimp, aweber, constant contact, campaign monitor, convertkit, activecampaign, drip, sendy, mailerlite, mailerlite form, lead generation, sendinblue, convertfox, optin form, top bar, getresponse, getresponse360, lightbox, modal, optin, subscribe, email list, lead capture, sidebar widget, sidebar form, emailoctopus, exit-intent, pop up, exit intent, elementor, mailchimp form, mailchimp newsletter, mailchimp plugin, mailchimp signup form, widget form, subscribe form, new post notification, constantcontact, mailpoet, aweber form, aweber forms, aweber signup form, sendy form, mailing list, opt-in, hello bar, hellobar, scroll trigger, newsletters, optinmonster, drift, icegram, slide box, slide in, slidein, call to action, calls to action, cta, list building, ab test.
Requires at least: 4.5
Tested up to: 4.9.4
Stable tag: 2.2.2.0
License: GPL-2.0+

Grow and engage your email list.

== Description ==
Best lead Generation, Email Automation & Newsletter WordPress Plugin.

== Frequently Asked Questions ==
See the website for more info https://mailoptin.io

== Changelog ==

= 2.2.2.0 =
* Added ConvertFox integration.
* Added SendinBlue integration.
* Added AdBlock Detection (PRO plan)
* Added New vs Returning visitors targeting (PRO plan)
* Added Referrer Detection (PRO plan)
* Fixed bug where GetResponse optin without name field was failing.
* Remove all custom media button added by plugins and core to wp_editor.
* Re-arrangement of display rules and page-level targeting.
* Moved controls for hiding of note, headline, description to their panels.
* All display triggers are now supported in all optin types.
* Added close optin and close & reload page options to CTA actions
* Added check to prevent sidebar <aside tag> from being included in markup when state after conversion is optin form hidden.
* Added filters to optin form components.
* Ensure customization save changes is publishing and not saving draft. Fixed bug in wordpress.com hosting.

* Fixed bug in OptinCampaignsRepository::get_optin_campaign_ids() working incorrectly.
* Fixed bug where columbine inpost field get overly long when CTA is activated with onclick to reveal optin.
* Fix styling for email campaign schedule control in customizer.
* Rebuilt how optin form style are inlined.
* Fixed bug where configuration of an optin clashes with another of same theme.
* Fixed bug where broadcast was failing because of presence of boolean payload eg 'click_tracking_enabled'
* Added a link to dismiss the leave review admin notice forever.
* Small design change of the form builder.
* Remove load_plugin_textdomain from core to main plugin file.
* Reworked honeypot implementation.
* Optimized images and added margin:0 to form optin tag.
* MailChimp Group label is only shown if at least a group has been selected for display.
* Removed http requests for convertkit tags and sequences in admin_init.
* Fixed bug where new post notification wasn’t sending if constantcontact account is US due to missing postal code data.
* Moved MC group validation script to mailoptin.js file
* Code and performance improvements. MailOptin is now 10x faster.

= 2.2.1.0 =
* New: A/B Testing of optin campaigns.
* More optin themes added.
* Fixed bug where impression wasnt counting for sidebar/inpost optin forms.
* Fixed bug where impression count was doubling for popups, notification bar and slide in optins.
* Added activation of email camapign as toggle switches.
* Added support for background color for optin form fields.
* Fixed bug in OptinCampaignsRepository::get_optin_campaign_ids() working incorrectly.
* Fixed bug where columbine inpost field get overly long when CTA is activated with onclick to reveal optin.
* Fix styling for email campaign schedule control in customizer.
* Rebuilt how optin form style are inlined.
* Fixed bug where configuration of an optin clashes with another of same theme.
* Fixed bug where broadcast was failing because of presence of boolean payload eg 'click_tracking_enabled'
* Added a link to dismiss the leave review admin notice forever.
* Small design change of the form builder.
* Remove load_plugin_textdomain from core to main plugin file.
* Reworked honeypot implementation.
* Optimized images and added margin:0 to form optin tag.
* MailChimp Group label is only shown if at least a group has been selected for display.
* Removed http requests for convertkit tags and sequences in admin_init.
* Fixed bug where new post notification wasn’t sending if constantcontact account is US due to missing postal code data.
* Moved MC group validation script to mailoptin.js file
* Code and performance improvements. MailOptin is now 10x faster.

= 2.2.0.3 =
* Removed test files that raised security warning by VaultPress.
* Slide-in optin form now full width and full heigh on mobile/small screens.
* Cleanup assets added to customizer preview frame by other plugins/themes.
* Fixed issue where sendy connection wasn't saving.
* Added index.php to all folders to prevent directory browsing.
* Removed close optin and close optin and reload in non-popup, slide in and notification bar types.
* Code and performance improvements.

= 2.2.0.2 =
* Tweak mailerlite to resubscribe user who previously unsubscribe and then opt-in again.
* Reposition mailchimp group selection to before submit button for themes that supports it.
* Code and performance improvements.

= 2.2.0.1 =
* Fixed bug where AWeber connection settings page wasn't showing up.

= 2.2.0.0 =
* Added: Call-to-action button in place of signup fields.
* Added: MailChimp interest group segmentation.
* Added: connected status added to all connections.
* Added: state after conversion feature.
* Added: Close Optin On Note Click in optin form completed.
* Added: missing form_background_color control.
* Fixed bug where lightbox impression count doubled.
* Define background-color for all form fields.
* Added switch to activate/deactivate optin campaigns.
* Added shortcode support to headline, description and note
* Redesigned the connection settings page to be sidebar tabbed.
* Elementor now added as a connection.
* Conenction's API key/token now obfuscated on display.
* Fixed bug in leads subscription that already exist in mailpoet from failing in other language WP installs eg German.
* Revamped single chosen field as well as date time and ace editor.
* Successfully added moment requires dependency to MailOptinjs.
* Rearranged menu such that optin menus comes first before that of email menus.
* Added missing text-domain in strings.
* Fix textareas control with long height.
* Added filter to list of optin form fonts list.
* All form fields in optin form now captured during form submit.
* Added an event that is triggered after core optin form validation.
* An event is now triggered when optin form validation kicks in.
* Added styling to builder control descriptions.
* Replaced optin actions buttons with icon font. Tooltip added to describe the action.
* Replaced email automation actions text descriptions with icons. Tooltip added to describe the action.
* Ensure OptinConversionsRepository:: month_conversion_count() return integer.
* Fixed bug with dashdot bar optin theme lacking default css values.

= 2.1.7.0 =
* Added: form background image customization for optin themes that support it.
* Added: shortcodes in email campaigns are now parsed before they are processed for delivery.
* Added collapse and expand buttons to connection and settings’ admin pages.
* Email campaigns label changed to email automation.
* Log changed to Email Log.
* Plugin menu re-arranged.
* Added Primrose sidebar theme.
* Added dahlia notification bar theme.

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
