=== MailOptin - Grow & Engage Your Email List ===
tags: popup, form, newsletter, forms, mailchimp, aweber, constant contact, campaignmonitor, campaign monitor, convertkit, contact form, activecampaign, drip, sendy, hubspot, mailerlite, sendinblue, klaviyo, mailjet, ontraport, salesforce, constantcontact, verticalresponse, vertical response, zoho, zoho crm, zoho campaigns, moosend, godaddy, getgist, sendlane, myemma, mailster, getresponse, autoresponder, lightbox, modal, emailoctopus, pop up, email, exit intent
Requires at least: 4.9
Tested up to: 6.3
Stable tag: 2.2.64.0
License: GPL-2.0+

Grow and engage your email list.

== Description ==
Best lead Generation, Email Automation & Newsletter WordPress Plugin.

== Frequently Asked Questions ==
See the website for more info https://mailoptin.io/

== Changelog ==

= 2.2.64.0 =
* Added [Fluent Forms](https://mailoptin.io/article/fluent-forms-email-marketing-crm/) integration.
* Declared WooCommerce High-Performance Order Storage support.
* Added WP user's merge tags support for email campaigns.

= 2.2.63.0 =
* Added [Tutor LMS](https://mailoptin.io/integrations/tutor-lms/) integration.
* WooCommerce checkout optin integration: Added order-pay checkout support.
* Added filter to enable postmeta storage facility instead of using woo order metadata.
* Added filter for adding custom HTML attributes to optin form fields.
* Fixed bug with range-control slider not updating input value.
* Fixed bug in detecting Sendy integration connection status.

= 2.2.62.0 =
* Added [WooCommerce Memberships Optin](https://mailoptin.io/article/woocommerce-memberships-mailchimp-aweber-more/) integration.
* Added ability to send test emails of draft posts.
* Fixed bug with disabling double optin in WooCommerce integration not working.
* Fixed bug with undoing field mapping not working in WooCommerce subscribe integration.

= 2.2.61.0 =
* Added [Microsoft Dynamics 365](https://mailoptin.io/article/create-microsoft-dynamics-365-wordpress-forms-capture-leads/) integration.
* Fixed conflicts with the OceanWP theme.

= 2.2.60.0 =
* Added [Salesforce](https://mailoptin.io/article/create-salesforce-wordpress-forms-capture-leads/) integration.
* Added [Benchmark Email](https://mailoptin.io/article/create-benchmark-email-wordpress-forms/) integration.
* PHP 8 compatibility improvements

= 2.2.59.0 =
* Added [Omnisend](https://mailoptin.io/article/create-omnisend-optin-forms-wordpress/) integration.
* Improved {{date}} usage in email campaigns.
* Fixed bug with formidable forms integration not working.
* Fixed VTI bug.

= 2.2.58.2 =
* Fixed bug where actual mailchimp api error was missing during error logging.
* Renamed Sendinblue to Brevo.
* Added debug mode to postEmailDigest.

= 2.2.58.1 =
* Fixed bug where WooCommerce custom field data wasn't retrieved during WC optin.
* Fixed bug with falsey error emails going out.
* Fixed bug with sendgrid api failing when creating campaigns.
* Fixed issue with checkbox not showing correctly in forminator addon settings page.
* Fixed bug where forminator conversion page data was invalid.
* Fixed double optin issue and conversion page url bug in forminator integration.
* Ensure conversion page is correctly populated with Gravity forms, Formidable Forms & WPForms integration.

= 2.2.58.0 =
* Added integration with new MailerLite platform.

= 2.2.57.0 =
* Added [Restrict Content Pro](https://mailoptin.io/integrations/restrict-content-pro/) integration.
* Added filter to flag a sendinblue field as boolean.
* Added filters to sort mailchimp interests and groups.
* Fixed a couple of PHP Warning: Undefined array key.
* Fixed bug with error reporting.

= 2.2.56.0 =
* Added [GiveWP](https://mailoptin.io/integrations/givewp/) integration.
* Added preheader support when creating email automations and broadcasts.
* Removed unsuported WP_User properties in sync integrations.
* Added lagacy label to old Constant Contavt integration.
* Fixed issue with license activation when staging is pushed to production.

= 2.2.55.1 =
* Added [email support to LifterLMS](https://mailoptin.io/article/send-wordpress-emails-lifterlms-students/).

= 2.2.55.0 =
* Added [Paid Memberships Pro](https://mailoptin.io/integrations/paid-memberships-pro/) integration.
* Improved [Easy Digital Downloads email campaign](https://mailoptin.io/article/send-emails-edd-customers-wordpress/) integration.
* Improved [MemberPress email campaign](https://mailoptin.io/article/send-wordpress-emails-memberpress-members/) integration.
* Improved [WooCommerce Membership email campaign](https://mailoptin.io/article/send-emails-woocommerce-memberships/) integration.
* Improved [WooCommerce Subscriptions email campaign](https://mailoptin.io/article/send-emails-woocommerce-subscriptions/) integration.
* Fixed bug where some hubspot properties were missing in fetch.

= 2.2.54.1 =
* Added WPML compatibility.
* Fixed bug where emails to membership users was sent to all users regardless of membership status.
* Ensure email is valid before attempt to subscribe.
* Fixed couple of XSS on admin settings page
* Restrict admin notices to only administrators.

= 2.2.54.0 =
* Added sending emails to [LearnDash users](https://mailoptin.io/article/send-wordpress-emails-learndash-users/?ref=prochangelog)
* Fixed bug where empty images when post doesn't have feature image was in email.
* Fixed email content with broken html.
* Fixed bug where VTI was including p tag in matching link.
* Added missing error log link for MailPoet, Mailster, FCRM.

= 2.2.53.0 =
* New: [send emails to Easy Digital Downloads customers](https://mailoptin.io/article/send-emails-edd-customers-wordpress/).
* PHP 8 compatibility improvements.
* Converts relative image URLs to absolute URLs.
* Fix PHP Fatal error with Forminator quiz integration.
* Fix deprecation errors from Elementor forms integration.
* Fixed bug with gridgum optin css not working.

= 2.2.52.1 =
* Added OPT_IN Sendinblue contact attribute support.
* Fixed bug with woo integration double optin not working.
* Fixed: TypeError thrownCannot access offset of type string on string
* Fixed bug where mailoptin_disable_send_optin_error_email filter didn’t work in some cases.
* Increased email campaign title DB limit
* Added tool to install missing Mailoptin missing DB tables.

= 2.2.52.0 =
* Added [LifterLMS integration](https://mailoptin.io/article/lifterlms-mailchimp-aweber-more/?ref=prochangelog).
* Added error handling output on failed email campaign creation.
* Added [post-author-avatar-url] support to email campaigns.

= 2.2.51.1 =
* Extended cache clearing to also clear ESP related data.
* Fixed PHP warning: Invalid argument supplied for foreach() in ../src/Admin/Customizer/CustomControls/WP_Customize_Chosen_Select_Control.php

= 2.2.51.0 =
* Added [WooCommerce](https://mailoptin.io/article/send-emails-woocommerce-customers-wordpress/?ref=prochangelog) email support.
* Added [WooCommerce Subscriptions](https://mailoptin.io/article/send-emails-woocommerce-subscriptions/?ref=prochangelog) email support.
* Added [WooCommerce Memberships](https://mailoptin.io/article/send-emails-woocommerce-memberships/?ref=prochangelog) email support.
* Added sending emails to all [memberpress members](https://mailoptin.io/article/send-wordpress-emails-memberpress-members/?ref=prochangelog).
* Added to New post notification, support for MemberPress author restriction.
* jQuery syntax update.
* Fixed bug where select2 repopulation didn’t work for some fields.

= 2.2.50.0 =
* Added [Easy Digital Downloads integration](https://mailoptin.io/article/edd-mailchimp-aweber-more/?ref=prochangelog).
* Added [Cookie Optin Targeting](https://mailoptin.io/article/target-visitors-based-browser-cookies/?ref=prochangelog) support.
* Added capability and nonce check to optin cache clearing.
* Fixed: Implicit conversion from float 1.0E+20 to int loses precision.
* Added filter to campaign error email address.

= 2.2.49.0 =
* Added [Comment Form Optin](https://mailoptin.io/article/wordpress-comment-form-email-subscription/?ref=prochangelog).
* Added [User Registration Optin](https://mailoptin.io/article/user-registration-optin-mailchimp-aweber-more/?ref=prochangelog).
* Added [MemberPress email campaign](https://mailoptin.io/article/send-wordpress-emails-memberpress-members/?ref=prochangelog) support.
* Fixed PHP notice caused by WP_User_Query being called with an argument that is deprecated.
* Added Japan Zoho DC support.
* Fixed NewsMan email campaign bug with encoding.

= 2.2.48.0 =
* Added [MemberPress integration](https://mailoptin.io/article/memberpress-mailchimp-aweber-more/?ref=prochangelog).
* Fixed bug where not all zoho list were retrieved.
* Fixed bug with Newsman optin not working.
* Added better error reporting for wp_mail deliveries.
* Removed unused cron job.

= 2.2.47.1 =
* Removed the Full Site Editing callout in customizer.
* Fixed bug where VTI was matching in a link.

= 2.2.47.0 =
* Added LearnDash to ESP integration.
* Added GA4 support to our GA integration.
* Fixed CleverReach double-optin not working.
* Fixed bug where woo integration didnt work when set to automatic subscription.
* Added filter to hubspot properties.

= 2.2.46.1 =
* Added filter to the admin email that receives optin error messages
* Added shortcode optin embed support for all display rules.
* Added topicID support to zoho campaigns.
* Fixed fatal error conflict with Astra theme.
* Fixed fatal error: Uncaught Error: Call to a member function get_meta() on bool.

= 2.2.46.0 =
* Added newsman integration.
* Added email automation support to zoho campaigns.

= 2.2.45.2 =
* Improved the reliability of the new Constant Contact authentication.

= 2.2.45.1 =
* Move to a new authentication system for Constant Contact v3 integration. [Learn more](https://mailoptin.io/article/connect-mailoptin-with-constant-contact/#v3)
* Increased Mailchimp segment limit.

= 2.2.45.0 =
* Added support for new Constant Contact v3 integration endpoints - REAUTHORIZE URGENTLY.
* Added feature to set custom field value during field mapping.
* Added new sidebar and inpost optin themes
* Fixed optin sound issue.

= 2.2.44.0 =
* Added syncing WooCommerce customers to ESP support after a purchase.
* Added Moosend segment support for email campaigns.
* Added filter to disable gutenberg block.
* Fixed undefined error when Optin Sound is enabled.

= 2.2.43.0 =
* Added WPML support to new publish post and email digest automations.
* Added Polylang support to new publish post and email digest automations. 
* Added new optin themes.
* Fixed bug where not all AWeber list were retrieved.
* Fixed bug with background image change not reflecting in customizer.
* Added filter to post collection function.
* Added alt when optin image is present.

= 2.2.42.2 =
* Improved CCv3 oauth connection.
* Fixed bug where field mapping didn't work in elementor.
* Switched hubspot to more v3 endpoints.

= 2.2.42.1 =
* Fixed bug with HubSpot integration not working for some users.

= 2.2.42.0 =
* New feature [optin sound effect](https://mailoptin.io/?p=32472).
* Added 'mo-optin-success-state' class to optin form when a user subscribes.
* New HubSpot app for premium users introduced.
* Increased HubSpot cache expiration time.
* Fixed range slider customizer control.

= 2.2.41.0 =
* Added comma separated CSS Selector when content locker is active.
* Added tagging support to Constant Contact v3.
* CleaverReach referrer parameter fix.
* HubSpot improvement: lead status, ownership and lifecycle stage settings added.
* Improved caching efficiency of integrations data.
* Reduced Cleverreach access token expiration by 2 weeks to avoid refresh error.
* Remove empty paragraph tags and visual composer tags in email campaigns.
* Show feature image alt of posts on email campaigns.

= 2.2.40.1 =
* Added ACF field support for custom email templates.
* Added caching to expensive ESP API calls.
* Fixed Forminator fatal error.
* Fixed view in browser not working for sengrid email marketing.

= 2.2.40.0 =
* New: [WooCommerce Added to cart](https://mailoptin.io/woocommerce-targeting/?ref=changelog) trigger.
* New: [WooCommerce Conditions](https://mailoptin.io/woocommerce-targeting/?ref=changelog) display rule.
* Enhancement: Only send email after user registration if password isn't set.
* Updated JS libraries.
* Fixed bug where all mailerlite groups weren’t returned.
* Fixed bug where mailchimp merge tags weren’t working in custom email template.
* Added filters to disable email notification to user and admin after registration.
* Added filter to disable VideoToImage.

= 2.2.39.2 =
* Added support for changing facebook API version from a UI.
* Fixed broken images in email body.
* Improved handling of mailjet API errors.
* Nuked every optin campaign ID that is 0 data retrieval.
* Fixed wp listing UI issue.
* Fixed bug where some Sendinblue list was missing.

= 2.2.39.1 =
* Fixed bug where mailoptin broke many ajax requests.
* Cleanup WPbakery shortcodes and empty paragraphs.
* Added is error checking to token refreshing.

= 2.2.39.0 =
* Added Webhook integration.
* Fixed PHP 8.0 issue with http_build_query.

= 2.2.38.1 =
* Added autologin option to user registration integration.
* Fixed PHP index error causing elementor forms not to work.
* Fixed Fatal error in WPForms integration.
* Fixed VTI issue where file without extension was failing.
* Fixed bug where inline css was shown in email message.
* Upgraded league/csv library to v9.
* Added more filters to email campaigns templatifiers.

= 2.2.38.0 =
* Added: Convertkit emailing support.
* Improvements to Constant Contact v3 token refreshing.
* Fixed before&after content editor in email campaign not working.
* Fixed incompatibility with upcoming WP 5.8.
* Made custom email template shortcodes for new post notification available everywhere.
* Added filter for adding post author as email sender.

= 2.2.37.2 =
* Improved accuracy of detecting when cron is not working.
* Made cron admin notice dismissible.

= 2.2.37.0 =
* New feature: Content locker.
* Detect when cron isn’t working and display admin notice to that effect.
* Improved click launch to work with WordPress menus.

= 2.2.36.3 =
* Fixed bug where plus (+) in post content was replaced with space.
* Fixed bug where sendinblue elementor integration forces DOI.

= 2.2.36.2 =
* Added double optin support to external form integrations.
* Added showing of group category name to mailchimp groups selection.
* Now Update mailchimp tags evenwhen subscriber already exist.
* Fixed IS "Only 1000 Contact Ids can be sent to with a single request" error.

= 2.2.36.1 =
* Fixed required fields validation in Constant Contact email integration.
* Fixed bug where leads where accidentally deleted.
* Forminator integration bug fixes.

= 2.2.36.0 =
* Added Forminator integration.
* Fixed bug where our Gutenberg integration broke the editor.
* Fixed cleverreach tagging not working for external forms.
* Added option to send test email to custom email addresses.
* Fixed issue where {{date}} wasn’t getting parsed in email campaigns.
* Fixed the splitting of multiples names into firstname and lastnames.
* Fixed Zoho Campaigns token refresh not working.

= 2.2.35.4 =
* Fixed issue where names with more than two words wasn't correctly synced to ESP.
* Fix potential issue where {{date}} wasn’t getting parsed in email campaigns.
* Fixed issue where Elementor field mapping wasn't working for Sendinblue.

= 2.2.35.3 =
* Added primary key to stat table.
* Fixed slider not working in email dnd builder.
* Improved email template for outlook.

= 2.2.35.2 =
* Fixed security issue in our Elementor integration.
* Extra security hardening.

= 2.2.35.1 =
* Added double-optin support to CleverReach integration.
* Fixed CleverReach email automations and broadcast not sending.
* Fixed settings page conflict Analytify.
* Fixed issues with Firefox browser.

= 2.2.35.0 =
* Added CleverReach integration.
* Increase moosend email list number to 1k.
* Fixed bug where Ontraport only retrieved the first 50 tags.
* Switched to mailoptin handle for localization js script.
* Do not set pageview cookie in lite or when mailoptin_enable_init_js_cookies filter is false.
* Fixed: preg_replace_callback() Compilation failed: invalid range in character class at offset.
* Removed code from Exception trigger in abstractConnect.

= 2.2.34.4 =
* Added CSV leads import.
* Added missing integrations to Ninja Forms.
* Fixed fatal error when integration not found in Ninja Forms.
* Fixed issue causing post formatting in email campaign to be skewed.
* Fixed fatal error caused by emogrify incompatibility with other plugins.
* Fixed issue with oauth refresh failing.
* Fixed liatris theme color for mini-headline.
* Added timestamp to error logging.

= 2.2.34.3 =
* Change oauth integrations nonce key to prevent error in connecting integrations.
* Fixed bug where images wasn’t included in automation emails.
* Fixed adblock detection not working.
* Fixed bug where notification bar was covering header on mobile.
* Upgraded Facebook graph API to 9.0.

= 2.2.34.2 =
* Added featured image size filter to posts.
* Fixed bug where split test variants was hidden even when state after conversion is set to optin shown.
* Change default optin success message to exclude "Please check your email for further instructions."
* Use enqueue_block_editor_assets instead for block registation instead of init.
* Fixed bug where split test pausing wasn’t working when there's more than one variant.
* Implement filter to remove new and returning visitors cookies.

= 2.2.34.1 =
* Added conversion page, referrer url and IP address data to ESP custom fields.
* Fix layout breakage caused by unclosed p tag.
* Fixed issue where elementorjs would result to undefined function error.
* Fixed sendinblue timezone error when sending email campaigns.

= 2.2.34.0 =
* Added more first/last name sendinblue contact attributes.
* Added Selected Users to WordPress Registered Users Integration.
* Switched to using wp_after_insert_post hook for new post notification automation.
* Lazy-load chosenjs customizer options.
* PHP 8 compatibility improvements.
* Resolve css conflicts with other plugins eg shortpixel.

= 2.2.33.1 =
* Fixed bugs with double optin in Sendinblue integration.
* Added filter "mo_optin_form_set_font_families_to_inherit" to make all optin font families a theme font.

= 2.2.33.0 =
* Added middle of content optin placement.
* Added double-optin support to Sendinblue.
* Email digest: Added support for start (and implicitly end) day of a week configured in WordPress settings
* Use the more reliable wp_timezone_string to get timezone/offset.

= 2.2.32.0 =
* Added Constant Contact API v3 which include support for custom fields.
* Fixed issue where custom html forms caused customizer saving to fail.
* Fixed issue where sendinblue view in browser and unsubscribe links weren't working.
* Added email notification when there is an email campaign error.
* Flag GA events as nonInteractive.

= 2.2.31.4 =
* Fixed fatal error that caused customizer not to work.

= 2.2.31.3 =
* Added missing tagging support.

= 2.2.31.2 =
* Added FluentCRM integration.
* Switched from wp_redirect to wp_safe_redirect for 302 redirects.
* Improve oauth integrations token refreshing.

= 2.2.31.1 =
* Added weMail integration.
* Fixed bug where customizer preview wasn't showing changes being made.
* Fixed bug where country field wasn’t showing unless an alpha code type is selected.

= 2.2.31.0 =
* Added Formidable Forms integration.
* Added Woocommerce product tag page-targeting rule.
* Fixed bug where a non-admin account in AC was showing not connected.

= 2.2.30.6 =
* Switched from using wp_cache_* to static variable for non-persistent cache.

= 2.2.30.5 =
* Layout adjustments to lucid email template.
* Fixed bug in videotoimg where regex captured > in opening p tag and < in closing p tag.

= 2.2.30.4 =
* Added Jilt integration.
* Renamed GetResponse Enterprise to GetResponse MAX.
* Fixed bug where google fonts were disabled by default.
* Fixed bug where GDPR eraser wasn't returning a response.

= 2.2.30.3 =
* Added option to disable google font loading.
* Fixed issue where vimeotoimg wasn’t working for Vimeo.
* Added filters to all post_content email campaign functions.
* Added cache implementation on expensive queries.
* Renamed newsletter to broadcast.
* Improved conversion tracking accuracy.

= 2.2.30.2 =
* UI compatibility with WP 5.5

= 2.2.30.1 =
* Added country custom optin field.
* Fixed issue where fetching tags via ajax wasn’t working.
* Renamed Infusionsoft label.

= 2.2.30.0 =
* Added Infusionsoft integration.
* Added user registration integration.
* Added a new panel to clearly show embed shortcode, widget and block.
* Added password custom field.
* Fixed multiple undefined index PHP errors.
* Improved optin conversion counter accuracy.
* Fixed: only show fb audience access token expired notice if integration is connected.
* Added missing Ninja Forms ESP integrations.

= 2.2.29.4 =
* Added SendFox integration.
* Added box-shadow to all slide-ins.
* Added alert to check if title is filled when creating optin and automations.
* Fixed bug where an A/B tst open still shows a variant even when a variant was subcribed to or closed.
* Fixed bug where optin stats weren't resetted when AB test variants are created.
* Fixed bug where a list ID that is zero stopped optin from adding subscribers.
* Fixed issue where modal to create fb audience wasn’t working.
* Fixed bug where Zoho Campaigns wasn't working for US data-center users.
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
* Swap out previous bulk activation of 
