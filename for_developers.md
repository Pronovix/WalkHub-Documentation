# For developers

WalkHub creates a framework for integrated tutorials that guide users through an interface, one step at a time.

The Walkthrough technology uses the Selenium testing format, an open standard widely used for regression testing in browser-based software projects. WalkHub itself is built on top of Drupal. For the actual player we have developed a custom solution that displays the bubbles, it's part of the WalkHub client JS.

You can use WalkHub through a proxy on the walkhub.net site, or install your own WalkHub components:

* [WalkHub distribution](https://github.com/Pronovix/WalkHub): Install the WalkHub distribution to create your own WalkHub.
* [WalkHub client](https://github.com/Pronovix/WalkHub): Install the WalkHub client to play walkthroughs on your site without using the proxy feature.
* WalkHub JS: Use the WalkHub JavaScript on your non-Drupal site.

## Installing WalkHub

WalkHub is a Drupal distribution to store your walkthroughs.

**Retrieve the code**

To install the WalkHub distribution, first check out the code:

	$ git clone --recursive git@github.com:Pronovix/WalkHub.git
	$ git checkout release/2014-07-05
	$ git submodule init
	$ git submodule update

**Install the distribution**

You can install the distribution as any other Drupal distribution. Either by hitting install.php and installing the Walkthrough profile or using drush:

$ drush site-install walkthrough

For more information see the [Drupal installation guide](https://www.drupal.org/documentation/install/).


## Installing the WalkHub client

If you are not using WalkHub.net as your WalkHub where a proxy service injects the Walkthrough javascript in your page, you will need the WalkHub client Drupal module installed to play Walkthroughs.

**Download the WalkHub client**

Either get the tarball from the [WalkHub client drupal.org project page](https://www.drupal.org/project/walkhub_client), or use git to retrieve the module

	$ cd sites/all/modules/contrib
	$ git clone git@github.com:Pronovix/Drupal-WalkHub-client.git --branch=7.x-1.x

**Install the module**

Go to admin/modules and enable the Walkhub Client module.

For more information see the [Drupal.org guide for installing modules](https://www.drupal.org/documentation/install/modules-themes/modules-7).

**Connect to WalkHub**

Go to admin/config/services/walkhub_client and set up your WalkHub url.

_IMPORTANT: As you added the module, the proxy is not needed any more. However, it's not possible to turn it off when you start the process from the red REC button. To disable the proxy you should start the recording process from the recorder page: [http://walkhub.net/walkthrough/record](http://walkhub.net/walkthrough/record)_ 

## Using the WalkHub JS

To record and play Walkthroughs without using the proxy, use the WalkHub JavaScript on any non-Drupal site directly.

Add this code to the <header> section on each page of your site:

	<script type="text/javascript">
	window.Walkhub = window.Walkhub || {};
	
	Walkhub.Origin = function () {
    	return "http://walkhub.net";
	};
	</script>
	<script type="text/javascript" src="http://walkhub.net/resources/compiled.js"></script>
	<link rel="stylesheet" type="text/css" href="http://walkhub.net/resources/walkthrough.css" />





