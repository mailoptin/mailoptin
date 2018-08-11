=== MailOptin - Grow & Engage Your Email List ===
Contributors: MailOptin
Tags: popup, wordpress popup, popup, newsletter, mailchimp, aweber, constant contact, campaign monitor, convertkit, activecampaign, drip, sendy, mailerlite, sendinblue, klaviyo, convertfox, ab test, a/b, split test, autoresponder, mailerlite form, lead generation, optin form, top bar, getresponse, lightbox, modal, optin, subscribe, email list, lead capture, sidebar widget, sidebar form, emailoctopus, exit-intent, pop up, exit intent, elementor, mailchimp form, mailchimp plugin, mailchimp signup form, widget form, subscribe form, new post notification, constantcontact, mailpoet, aweber form, aweber signup form, sendy form, mailing list, opt-in, hello bar, hellobar, scroll trigger, newsletters, optinmonster, icegram, slide box, adblock, referrer, referrer detection, email notification, adblock detector, slide in, slidein, call to action, cta, list building, google analytics, autochimp
Requires at least: 4.5
Tested up to: 4.9.8
Stable tag: 2.2.7.0
License: GPL-2.0+

Grow and engage your email list.

== Description ==
Best lead Generation, Email Automation & Newsletter WordPress Plugin.

== Frequently Asked Questions ==
See the website for more info https://mailoptin.io

== Changelog ==

= 2.2.7.0 =
* New dashboard redesign. Yay! Connections is now called integrations.
* New: Email digest of published post.
* You can now edit automation campaign name.
* Improve optin customization option.
* Bug fix where name field required wasn’t hidden when name field is set to hidden.
* Fixed issue with duplicate campaign name error in some connections.
* Improve compatibility with nextgen gallery.

* Added before main content body editor control to email automation
* Send test email feature is now retried without header.
* Contextual naming of connection service list label re-added.
* Added contextual display of some controls in email campaign customizer
* Enhance compatibility with more themes such as the popular Newspaper theme.

= 2.2.6.0 =
* Added tabs to sort controls into General and Style.
* Added option to remove feature image from email campaign
* Added before main content body editor control to email automation
* Send test email feature is now retried without header.
* Contextual naming of connection service list label re-added.
* Added contextual display of some controls in email campaign customizer
* Enhance compatibility with more themes such as the popular Newspaper theme.

= 2.2.5.0 =
* New repeater integration field in optin form builder.
* GDPR consent now switched to new consent flag added to CM API.
* Sort connections in alphabetical order.
* Fixed bug where gdpr checkbox note was showing when CTA is activated.
* Fixed bug where contextual CTA control wasn’t working.
* Fixed bug with ab test variant display

= 2.2.4.2 =
* Added filter sorting to connections.
* Added Google Analytics support [Agency].
* Performance improvements.

= 2.2.4.1 =
* Fixed bug where rescript sidebar theme wasn’t showing description control in form builder.
* Restricted removal of admin notice from other plugin to just mailoptin settings pages.
* Updated success conversion script triggered to new JS execution.
* Name and email placeholders now available in success triggered script.
* Fix for IP address getter.
* [GDPR] Consent is now passed to MailChimp as custom field.
* [GDPR] Consent is now passed to EmailOctopus as custom field.

= 2.2.4.0 =
* [GDPR] Added checkbox to optin form and save consent in ESP mostly as tags and custom field.
* [GDPR] Added control to make name field in optin required or not
* [GDPR] Leadbank now hook to WordPress core GDPR tools for export and erasure of personal data
* [GDPR] Added searching support to leadbank.
* [GDPR] Added checkbox to "Optin Campaign settings" to toggle leadbank on and off.
* Fixed incorrect IP address label for Klaviyo integration
* Fixed bug where Klaviyo included segment in list fetch
* Form and email template builder URL now shortened.
* Improve button to add new campaigns to be more visible.
* Added notice when no connection is available in optin form builder.
* Added optin type flag to optin name.
* Fixed bug where sepcifying custom listing number in wp list wasn’t working.

= 2.2.3.0 =
* Added Klaviyo integration
* Added Autoresponder feature. Send welcome email after user signup.
* Added contextual opening of controls when optin elements are clicked.
* Added custom css option to email template builder.
* Added some toast notifications to the form builder to remind you of things to do.
* Added filtering of new post notification by post tags and categories.
* Added auto-detect and convert vimeo & youtube embed to image link.
* Added: New post notification can now be sent to users with specific roles.
* Sendy optin subscription now include leads ipaddress and referrer.
* Improved compatibility with most WP themes in customizer.
* Fixed bug where contextual display of integrations wasn’t properly working.
* Fixed usage tracking not dismissing.
* Moved success message to after conversion panel.
* Update tinymce control to use the latest API.
* Added filter customize/edit url.

= 2.2.2.1 =
* Fixed bug where 'Globally load optin' wasn't kicking in.

= 2.2.2.0 =
* Added ConvertFox integration.
* Added SendinBlue integration.
* Added Email notification after conversion completed.
* Added AdBlock Detection (PRO plan)
* Added New vs Returning visitors targeting (PRO plan)
* Added Referrer Detection (PRO plan)
* Switched from wp-admin-ajax to a custom ajax handler.
* Fixed bug where GetResponse optin without name field was failing.
* Fixed bug where AWeber broadcast was failing.
* Remove all custom media button added by plugins and core to wp_editor.
* Re-arrangement of display rules and page-level targeting.
* Moved controls for hiding of note, headline, description to their panels.
* All display triggers are now supported in all optin types.
* Added close optin and close & reload page options to CTA actions
* Added check to prevent sidebar 'aside' tag from being included in markup when state after conversion is optin form hidden.
* Added filters to optin form components.
* Ensure customization save changes is publishing and not saving draft. Fixed bug in wordpress.com hosting.
* Swap out previous bulk activation of optin and automation to new queue system.
* Added filter to disable optin impression count.
* Added filter to optin form shortocde structure.
* Added: send email to admin when optin is failing to subscribe leads.
* Rebuilt settings setting page with tab.

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
