=== Wordpress UPI QR code Payment Plugin ===
Contributors: upiplugin
Tags: India,Payments,UPI,Wordpress,Payment gateway, BHIM
Donate link: https://kiasa.in/wpdonate
Requires at least: 4.0
Tested up to: 6.2
Requires PHP: 5.6
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This Plugin lets Wordpress website admins (NON WOOCOMMERCE SITES) to receive payments directly without a payment gateway by using UPI applications like Google Pay, Whatsapp, PayTM, PhonePe or any banking UPI application. 

== Description ==

This Plugin lets Wordpress site admins (NON WOOCOMMERCE SITES) to  get payment by using UPI applications like Google Pay, Whatsapp, PayTM, PhonePe or any banking UPI application. 


After this plugin is installed, the site admin can create shortcodes with keyword of kiasa. The shortcode is of this form: [kiasa upivpa="kiasa@upi" price="1" msg="Click to Donate!"]. Kiasa is the keyword and it should always be present. Wordpress admin should put his/her UPI VPA in the upivpa field. Price/Amount to be received is to be specified against "price". The Message on click button can be configured with "msg" option.  

In PCs, it will show a QR code that can be scanned by the UPI application and payment can be made. Payments come to the Wordpress admin's bank account directly.There is no payment gateway involved and saves money for wordpress site owners.

Shortcodes can be put in posts, pages or widgets. But ensure that there is only one shortcode per webpage!

This plugin can be used for donations, voluntary payments, payment of fees, crowdsourcing, collection for a cause, paywalls and so on.

Please register <a href="https://kiasa.in/register"> here </a> for bug fixes, information about new releases and support tips.

NOTE: As of Jan 2021, Government has disabled payment through mobiles. So the
plugin works only on PCs through QR code scan.

== Benefits ==

* Easy to setup
* Completely avoid Payment Gateway Fees
* Instant Settlement
* Money gets credited instantly in your Bank account (No  Wait For Payouts)
* No any documentation or KYC required to use
* Can be used on mobile as well as PCs
* 24×7 Availibility
* Multisite wordpress support
* 100% free
* No Hidden charges
* No KYC, No GST number Required
* Ideal for small merchants, ecommerce shops
   

== Installation ==
1. Upload "wordpress-UPI-payment.zip" to the "/wp-content/plugins/" directory.
1. Activate the plugin through the "Plugins" menu in WordPress.


== Frequently Asked Questions ==

= How does it help me? =
By using the plugin, you avoid the payment gateway charges that are part of every transaction. A non Woocommerce wordpress site can collect payments from its users/customers using UPI 

= What are prerequisites for payee? =
Payee should be in India. This is as per Government requirements for UPI payments.  

= What are prerequisites for Wordpress site owner? =

Wordpress site admin should create a UPI VPA connecting his/her bank account and then use that VPA to create shortcodes.  After that, all payments will come directly to the bank account.  

= How does the Wordpress admin know about payment? =

Wordpress site admin should install BHIM application in his/her mobile.  Whenever a payee makes a payment, wordpress site admin can see the Transactions in BHIM application. The Transacation will be in form raju1122334455, where raju is name of payee and 1122334455 is the mobile number. 

In addition, wordpress admin will get a email giving name, email details of payee.  The wordpress admin then can check in BHIM if indeed the payment has been made.  Checking in BHIM or any other UPI application by Wordpress admin alone confirms the payment.

= What happens if I dont specify the Price in shortcode? =
In this case, UPI app (like PhonePe, Google Pay) will prompt for amount to be paid. This is useful in case of donations, where you want let the payees to determine the amount. If you are collecting a fixed amount like monthly tuition fees of Rs 500, you can mention it.

= What happens if I dont specify the Msg in shortcode? =
In this case, Click button message will be "Click to Donate!"

= What happens if I dont specify UPI VPA?
Well, then it will default to my UPI VPA and I will get payments :)

= Where can I use the shortcode?
You can put it anywhere - pages, posts, in middle of posts, top, side, bottom widgets anywhere

= How do I send receipts to payees? =
Wordpress Admin gets the email address of payee. Admin can then use any third party software to create receipts and send.  

= How is this different from Kiasa Woocommerce UPI Plugin? =
Well, this plugin is for NON WOOCOMMERCE WORDPRESS SITES and uses shortcodes.

= I dont have a Woocommerce site or Wordpress site. I sell through whatsapp, facebook. How do I use this? =
You can try <a href ="https://ezeepaylink.kiasa.in/"> Ezeepaylink </a> for an alternative which allows payment links for such an use case.  

= What are Terms and Conditions? =
This plugin is made available in as-is-where-is and is on free basis and under GPL. The user of plugin understands and agrees that plugin developer is not responsible for any loss of payments made using the plugin. Developer of plugin has no liability whatsoever for any loss, if any, incurred by payee or wordpress admin.  

The Plugin uses the UPI URL services of Kiasa. The service creates a UPI URL based on the user data. The terms and conditions of the service can be found <a href="https://kiasa.in/WP-UPI-payment/TnC.html"> here </a> 

= Is there a demo? =
Yes, there is a demo site where you can see how the plugin works. Please click <a href="http://demo1.kiasa.in/"> here </a>.

= Anything else? =
If you like this software, kindly help us donating to support development. You can see donate button in the page.

= I still have a question! =
Please send your question to raj@kiasa.in. Thank you!

== Contribute ==

* Active development of this plugin is handled on <a href="https://github.com/nagarajanrajagopal/WordPressUPIPayment-Plugin"> GitHub </a>.
* Feel free to fork the project on GitHub and submit your contributions via pull request.

== Screenshots ==
1. Example shortcode
1. Click button
1. Screen on clicking the shortcode
1. Payment screen for mobile and PC/Laptop/Tab


== Changelog ==
= 0.1 =
* Initial release.

== Upgrade Notice ==


