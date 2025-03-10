=== Paid Memberships Pro - CCBill Add On ===
Contributors: strangerstudios
Tags: paid memberships pro, payment gateway, ccbill
Requires at least: 5.5
Tested up to: 6.2
Stable tag: 0.2

Adds the ability to accept payments using the CCBill Payment Gateway

== Description ==

Adds CCBill as a payment gateway to your list of accepted payment gateways. CCBill makes use of an off-site payment method process. This Add On is currently in Beta. 

[Read the full documentation for the CCBill Add On](https://www.paidmembershipspro.com/add-ons/ccbill-payment-gateway/)

= Official Paid Memberships Pro Add On =

This is an official Add On for [Paid Memberships Pro](https://www.paidmembershipspro.com), the most complete member management and membership subscriptions plugin for WordPress.

== Installation ==

1. Make sure you have the Paid Memberships Pro plugin installed and activated.
1. Upload the `pmpro-ccbill` directory to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.

Navigate to Memberships > Settings > Payment Gateways & SSL and select the CCBill payment gateway. You will then need to fill out the required account credentials to connect your website to the payment gateway.

== Frequently Asked Questions ==

= I found a bug in the plugin. =

Please post it in the GitHub issue tracker here: https://github.com/strangerstudios/pmpro-ccbill/issues

= I need help installing, configuring, or customizing the plugin. =

Please visit our premium support site at http://www.paidmembershipspro.com for more documentation and our support forums.

== Changelog ==
= 0.2 - 2023-04-09 =
* BUG FIX: Only cancel relevant URL on sub cancellation.
* BUG FIX: Fixed calculation of the initialPeriod value passed to CCBill.
* BUG FIX: Fixed errors in the webhook code.

= 0.1 - 2022-10-05 =
* Initial Release