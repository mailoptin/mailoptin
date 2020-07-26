=== MailOptin - Grow & Engage Your Email List ===
tags: popup, form, newsletter, forms, mailchimp, aweber, constant contact, campaignmonitor, campaign monitor, convertkit, contact form, activecampaign, drip, sendy, hubspot, mailerlite, sendinblue, klaviyo, mailjet, ontraport, constantcontact, verticalresponse, vertical response, zoho, zoho crm, zoho campaigns, moosend, godaddy, getgist, sendlane, myemma, mailster, getresponse, autoresponder, lightbox, modal, emailoctopus, pop up, email, exit intent
Requires at least: 4.6
Tested up to: 5.4
Stable tag: 2.2.29.4
License: GPL-2.0+

Grow and engage your email list.

== Description ==
Best lead Generation, Email Automation & Newsletter WordPress Plugin.

== Frequently Asked Questions ==
See the website for more info https://mailoptin.io

== Changelog ==

= 2.2.29.4 =
* Added Sendfox integration.
* Added box-shadow to all slide-ins.
* Added alert to check if title is filled when creating optin and automations.
* Fixed bug where an A/B tst open still shows a variant even when a variant was subcribed to or closed.
* Fixed bug where optin stats weren't resetted when AB test variants are created.
* Fixed bug where a list ID that is zero stopped optin from adding subscribers.
* Fixed issue where modal to create fb audience wasn’t working.
* Fixed bug where IP address might return ::1.
* Updated rescript inpost screenshot.
* Increased limit of mailjet contact properties fetched.

= 2.2.29.3 =
* Fixed bug where Zoho Campaigns wasn't working for non-us data-centers.
* Fixed bug where sending emails to large subscribers was failing.
* Improved compatibility with jQuery 3.x.
* Show a prompt before deleting any item.

= 2.2.29.2 =
* Fixed leadbank pagination not working.
* Fixed screen option pagination saving bug caused by WP 5.4.2.
* Further DB Query solidification.

= 2.2.29.1 =
* Fixed fatal error in cases where controls were missing when opening the customizer.
* Fixed bug where clicking save changes button doesn't save field mapping data.
* Added filter to disable admin notice ads.
* More improvements to themes compatibility.

= 2.2.29.0 =
* Added email list selection support. Visitors and users can now select lists to subscribe to.
* Fixed error causing builder not to change state after saving.
* Fixed issue where specifying google font for custom fields wasn’t working.

= 2.2.28.2 =
* Added hidden custom field support to optin forms.
* Added option to disable linking to post article in post email automation.
* Improve compatibility with hestia, generatepress and many other themes.
* Fixed a weird z-index issue on optin forms.
* Fixed bug where spam CF7 submissions were saved to ESP.
* Upgraded FB graph API version to 7.0.

= 2.2.28.1 =
* Fixed fatal error caused by missing Ninja Forms integration class.

= 2.2.28.0 =
* Added Gravity Forms integration.
* Added SendGrid email marketing integration.
* DB Query solidification.
* Added option to use post excerpt instead of post content in email automation.
* Fixed object object error when a custom field is required.
* Added filter to delete leads after unsubscription.

= 2.2.27.5 =
* Added Ninja Forms integration.
* Added conversion tracking of custom html.

= 2.2.27.4 =
* Fixed issue were AWeber stopped working.

= 2.2.27.3 =
* Added Contact Form 7 integration.
* Improved UX on renaming optin and email campaigns.
* Upgraded to Fancybox to version 3.

= 2.2.27.2 =
* Added WPForms integration.
* Added shortcode parsing to email content
* Improve compatibility with Divi builder.
* Fixed sendinblue error in fetching lists.

= 2.2.27.1 =
* Swapped out session storage adapter for compatibility with host with session disabled.
* Increased sendinblue list fetched limit.
* Improve multisite compatibility.
* Fixed backupbuddy compatibility issue.
* Added server level disabling of impression tracking.

= 2.2.27.0 =
* Added WooCommerce targeting to optin campaigns.
* Added WPML integration.
* Added option to prefill form with logged in user data.
* Improvement to ensure post content doesn’t breakout of defined width of email templates.
* Fixed issue where submit event wasn’t triggered when optin form is submitted.
* Rewrote and simplified page targeting rule engine.
* Fixed issue where submit event wasn’t triggered when optin form is submitted.
* Fixed submit button styling issue in ios safari.
* Fixed bug where cookie duration was set where success cookie should be set instead.

= 2.2.26.0 =
* Added form width support.
* Added Facebook custom audience support.
* Fixed issue where filter for admin email that receives test emails wasn't working.

= 2.2.25.0 =
* Added Elementor form lead tagging support.
* Added tagging support to GetResponse integration.
* Added custom field support to Gist.
* Added filter to admin email that receives test emails.
* Added GA conversion tracking on CTA click to URL.
* added default attribute for post feature image shortcode.
* Font weight and styling fixes for a number of optin themes.
* Fixed bug where contact without subscription status failed to be subscribed in Mailchimp.
* Fixed bug where ontraport subscription was failing.
* Change AWeber to use the new upsert method (update subscriber if existing).
* Changed GetResponse360 to GetResponse enterprise.

= 2.2.24.0 =
* Added Zoho CRM integration.
* Added youtube-nocookie.com embed support for email.
* Added double optin support for Mailjet.
* Added birthday and date fields support for Mailchimp integration.
* Added support for Campaign Monitor multiselect field.
* Fixed issue with youtube embed to image link not working on some hosting.
* Fixed issue where 2 same form on the same page wouldn’t work.
* Fixed bug where email digest wasn’t working for cloned campaigns.
* Fixed Mailchimp group display bug in liatris optin themes.
* Replaced fontawesome with dashicons in admin dashboard.
* Pikaday date format changed to Y-m-d.

= 2.2.23.1 =
* post-date shortcode in email automation now support format attribute.
* Added mailoptin_controls_helper_get_post_types filter to control post type visibility.

= 2.2.23.0 =
* Added Emma email marketing integration.
* Fixed bug where adding new custom field didn’t work unless on reload.

= 2.2.22.1 =
* Upgraded klaviyo integration to new list API v2.
* Fixed: sendy bug where user subscription wasn’t working for Sendy v4.0.3.3.
* Fixed bug where scheduled forms couldn't be close and ignore display rules.

= 2.2.22.0 =
* Added: New email builder for crafting one-off newsletters to subscribers.
* Post email digest preview now match the criteria selected.
* Fixed custom field reordering in optin not working.
* Fixed title naming for email campaigns.
* Fixed: scheduling now more accurate by forcing strtotime to use UTC.

= 2.2.21.0 =
* Added and made WP HTTP API the default http client.
* Added Leadbank subscribers email automation support.
* Fixed bug with registered users unsubscription.

= 2.2.20.0 =
* Added Zoho Campaigns integration.
* Added date custom field to optin forms.
* Added: Restrict to post authors added in email automation.
* Added system fonts to list of font selection for custom optin fields.
* Fixed bug where Divi backend builder wasn’t triggering new post automation.
* Added nonce check when saving oauth credentials.

= 2.2.19.1 =
* Added display of post meta to email template settings. E.g post author, date published and post categories.
* Added filter to disable emogrify.
* Fix: do not enqueue recaptcha when keys are not present.
* Fixed bug where preview post title wasn’t used when test email is sent
* Removed usage tracking.

= 2.2.19.0 =
* Added reCAPTCHA v2 & v3 support for forms.
* Added honeypot check server-side to prevent spams.
* Added GoDaddy email marketing integration
* Fixed bug where checkbox and radio button when set as required wasn’t working.

= 2.2.18.1 =
* Added Moosend integration.
* Fixed Fatal error Cannot use MailOptin\Core\EmailCampaigns\Newsletter\Newsletter as Newsletter.
* Added support for mapping of elementor fields.
* Added link to disconnect OAUTH connections.

= 2.2.18.0 =
* Added checkbox, select and radio custom fields support.
* Added Hubspot integration.
* Fixed media uploader issue in newsletter creation UI.
* Added {{date}} placeholder support for email subject.
* Fixed issue where sending of test newsletters email had the title skewed.
* Added disabling of new post notification in Gutenberg editor.

= 2.2.17.0 =
* Added Ontraport integration.
* Added Mailjet integration.
* Added Vertical Response integration.
* Updated Mailpoet integration to use it's API for every operation.
* Fixed sender name and email not injected on autoresponder emails.
* Added doc link on how to fix the popular no email list found error.
* Added stripslash support for from name.

= 2.2.16.1 =
* Added option to change optin theme.
* Added never load on this categories rule.
* Added unsubscribe support for emails sent to registered users.

= 2.2.16.0 =
* Added one-off newsletter support.
* Added ninja forms support for custom html feature.
* Fixed: conditional display in optin customizer.

= 2.2.15.1 =
* Added link to view integrations error log.
* Added option to target users by their role.
* Fixed: when click launch is activated, query string section is not hidden.
* Fixed Uncaught TypeError: Cannot read property 'active' of undefined.
* Added customizer option to remove post body in email automation.
* Increase maximum post range slider to 1000 in email automation settings.
* Added split test support for shortcode optin embed.

= 2.2.15.0 =
* Added new optin themes.
* Added ability to replace the default fields with a shortcode and/or HTML content.
* Added query string targeting display rule.
* Added feature to hide optins on urls with the mohide=true query string.
* Added categories and tax support to [posts-loop] email digest shortcode.
* Allow users access to MailOptin with with manage_mailoptin capability.
* Fixed bug where optin theme customizer config override another theme.
* Fixed compatibility with Windows server.
* Fixed bug with replacement of name and address placeholder tags in email automation.
* Only load optin theme dependent script on mailoptin customizer UI.

= 2.2.14.0 =
* New: Disable closing of lightbox on backdrop click.
* Added filter to use excerpt instead of post content in email automation.
* Added Gutenberg block form embedding optin forms.

= 2.2.13.2 =
* Fixed bug with custom taxonomies settings not saving in email automation.
* Fixed issues with email automation custom template shortcode tags not working.
* Fixed bug where post with full content wasn't triggering email automation.
* Fixed issue where ESP with default static fields returned empty because no custom user created field was found.

= 2.2.13.1 =
* Fixed issue where youtube/vimeo embed wasn't correctly showing in email.
* Fixed:  PHP Deprecated:  define(): Declaration of case-insensitive constants is deprecated.
* Core files are now included in parent plugin folder instead of composer vendor directory.

= 2.2.13.0 =
* Design refresh of the dashboard.
* Added option for custom email template for automations (code your own).
* Added tag support to MailChimp optin.
* Added polylang integration.
* Added leadbank only support for Elementor form.
* Added setting to disable impression tracking.
* Fixed bug that could cause custom post types automation from not sending.
* Moved licensing page to Settings.
* Lead bank now has its own settings page.
* Fix for duplicate email problem with digest automation.

= 2.2.12.2 =
* Added device (mobile, tablet or desktop) targeting display rule.
* Added support for windows hosting.
* Added advance settings to name field for ESP mapping.
* Made all tinymce control text/visual.
* Improved contextual panels display in form customizer.
* Added custom field support to leadbank exports.

= 2.2.12.1 =
* Fixed issue where core wasn’t sending new post notification in some rare cases.
* Return error message when trying to map empty custom fields.
* Fixed sendinblue bug where email address belonging to another list failed to be subscribed.

= 2.2.12.0 =
* Removed optin campaigns and coversion limit.
* Added shortcode support for optin forms.
* Added support for custom fields to optin forms with integration mapping.
* Fixed bug where email automation customizer wasn't saving.
* Made headline in optin customizer visual/text.
* Added pushing of notification bar to the top on window resize.
* Added shortcode support to success message.
* Reduced inline js object added to frontend.
* Added better explanation to re-authorize connection button.
* Removed maipoet double optin feature. What it basically did was prevent confirmation email from being sent.
* Subscriber name is now split into name and lastname for Mailerlite connection.
* Updated Convertfox to Gist.
* Fixed bug with mailchimp interest user input.
* Added sendinblue list sync where by user are not removed from their previous joined list.
* Fix for mailchimp GDPR optin consent not working.

= 2.2.11.2 =
* Sendinblue optin fix when automation is active.
* Remove IP address from ActiveCampaign payload if ip is not ip4.
* More tighter customizer cleanup for improve compatibility with most themes and plugins.
* Fix support for youtube and vimeo embed.
* Made description wysiwyg to be text/visual.
* Notification top bar now pushes content to the bottom.

= 2.2.11.1 =
* Fixed bug with click-launch shortcode not working.
* Responsive font size fixes for optin forms.
* Fixed a number of PHP notice errors.
* Added filter to disable sending optin errors email.
* Added support for post tag display rule in optin.

= 2.2.11.0 =
* Added support for custom post type to email automations.
* Optin branding now disabled by default.
* Better control over google fonts to load when not necessary.
* Added class attribute support to [mo-click-launch] shortcode.
* Improve optin themes compatibility with most WP themes.

= 2.2.10.1 =
* Fixed bug with Mailerlite subscription not working.
* Fixed bug where hiding note wasn’t working.
* Fixed bug where effects wasn’t working in customizer preview.
* Fixed: Uncaught TypeError: Cannot read property 'scrollHeight' of undefined.
* Fixed bug with scripts not being cleaned up in customizer.

= 2.2.10.0 =
* Added support for changing optin font sizes.
* Added support to inherit theme font in optins.
* Added support for MailChimp GDPR tool for saving consent.
* Optin no longer load an external css stylesheet.
* Fixed bug with post digest not sending.
* Remove quoted slash from campaign names.
* Some performance enhancements.

= 2.2.9.0 =
* Added Mailster Integration.
* Moved effects control to Design panel.
* Added support for double optin in EmailOctopus integration
* Added new switch customizer loader method.
* Added confirmation prompt before deleting optin and email campaigns.
* Added after main content control to email template.
* Added easy google font plugin compatibility.
* Added support for categories and tags in post email digest.
* Fixed issue where email automation was sending multiple times in same interval when incidentally there is a new post.
* Fix issue of having to save draft first before publishing when custom fields are added to post edit screen.
* Fix bug with leadbank not working.
* Fixed issue with urlencode happening to urls in email campaign.
* Deactivate cloned optin and email campaign by default.
* If global optin is set, let never load rules also kick in.
* Test mode now ignore display rules.

= 2.2.8.2 =
* Only return untrashed and default type list for mailpoet.
* Now obfuscating sendlane hash field.
* Added timeout to MC HTTP client instance

= 2.2.8.1 =
* Fixed bug with curl not working on some host
* Fixed bug with MailChimp email automation not sending

= 2.2.8.0 =
* Added headers to email customizer.
* Metabox settings to skip a post from being included in new post notification.
* Click launch: If optin-uuid data attribute is not set, use the ID to get the optin uuide
* Added support for retrying email digest.
* Call sendchecklist API method before sending MailChimp automations.
* Added: you can now send to MailChimp list segment.
* Added Sendlane integration.

= 2.2.7.1 =
* Fixed bug with sendinblue not adding contact to list
* Displays email template un-emogrified in customizer so custom css ish can be targeted and used.
* Filter for adding custom page targeting rules added.
* Fixed mini headline preview not working in some themes.
* Added compatibility with flatbase theme
* Ensure optin_type exist for the campaign before adding to DB to prevent PHP error.

= 2.2.7.0 =
* New dashboard redesign. Yay! Connections is now called integrations.
* New: Email digest of published post.
* You can now edit automation campaign name.
* Improve optin customization option.
* Bug fix where name field required wasn’t hidden when name field is set to hidden.
* Fixed issue with duplicate campaign name error in some connections.
* Improve compatibility with nextgen gallery.

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
