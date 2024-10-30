=== Hide Real Download Path ===
Contributors: deepaks
Donate link: http://xlab.co.in/hide-download-path-of-file-wordpress-plugin/
Tags: hide real download path, hide download path, secure file, hot linking, disable direct download
Requires at least: 3.5
Tested up to: 4.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin help to hide real download path of your files on server and allow file downloading using a common URL. Also maintain log of your downloads on server in a log file as well restrict hot linking.

== Description ==

Plugin helps you to hide real/direct path of files hosted on your server for download and make your files secure from unauthorized download. It also maintains a log of all downloads done using it and provide capability to disallow direct linking (hot linking) to your files from other website.

<strong>You can:</strong>
<ul>
<li>Allow or restrict hotlink (direct download) of your files from other website/external links.</li>
<li>Restrict 'download only' from link on your website</li>
<li>View log of individual download</li>
</ul>

It support multiple files extensions including:
zip / pdf / doc / xls / ppt / exe / gif / png / jpg / jpeg / mp3 / wav / mpeg / mpg / mpe / mov / avi / xlsx

*<strong>Step by step configuration guideline</strong> in Settings sections of plugin after activation

<strong>Version 1.5 changes:</strong>
- Corrupt file bug fixed
- Easy step by step guide added in admin to configure plugin
- Generate Root path dynamically
- Support for xlsx added

== Installation ==

1. Unzip plugin in `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
2. Go to Settings -> 'Hide Download Link'
3. Enter Root path of your download directory where all files are hosted. (it should be something as /home/public_html/yourdirectoryname depending on your host)
4. Enter referred (if you want to restrict direct download using link from other wesbites)
5. Save and you are done !!

Now create a page and enter shortcode [download_page]. You are files are now secure!

Download link of your all files will be http://YourSiteName.com/YourPageName/?f=YourFileName.extension

Example:
If you created page with name 'Download' and added shortcode in it, Path for your download file (assuming its name is test.zip) will be:
http://yoursitename.com/download/?f=test.zip

== Frequently Asked Questions ==

= How can I view download log? =

A file 'downloads.log' is created on root of your server, open it in text editor and you can view details Time/Date/IP address and Downloaded file name in it.

= what should I enter in 'Allowed Referred'? =

'Allowed Referred' is not mandatory but if you want to allow download of your files from specific websites only then enter name of site in allowed referral textbox.
For example if you want to allow download of files from your website only, enter your site name (without http://www.) in allowed referral. Now users will be only able to download file by clicking link on your website.

= Where do I report bugs? =

In the WordPress forum (http://wordpress.org/support/plugin/hide-real-download-path) or contact using form <a href="http://xlab.biz/get-in-touch/">here</a>