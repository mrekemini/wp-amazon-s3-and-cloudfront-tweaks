WP Offload S3 Tweaks
========================

This is a WordPress plugin, meant as a starting point for developers to tweak [WP Offload S3](https://wordpress.org/plugins/amazon-s3-and-cloudfront/) using WordPress filters.

Installation
------------

Create a /amazon-s3-and-cloudfront-tweaks/ folder in /wp-content/plugins/ and simply drop the `amazon-s3-and-cloudfront-tweaks.php` file into it. Then go to the Plugins page in your WordPress dashboard and activate it.

Setup
-----

Open the `amazon-s3-and-cloudfront-tweaks.php` file and take a look at the `__construct()` function. You will notice that all the calls to `add_filter()` are commented out. So, at the moment the plugin does nothing even though it's activated. To enable a filter, simply uncomment the appropriate `add_filter()` line.