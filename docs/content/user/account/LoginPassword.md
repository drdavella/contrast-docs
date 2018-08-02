<!--
title: "Login &amp; Password"
description: "Overview of user login and password"
tags: "user login password manage account"
-->

To log in to Contrast, you must accept an email invitation generated by your Administrator during onboarding. Once you accept this invitation, you're taken to Contrast to log in for the first time. 

<a href="assets/images/Email_Welcome.png" rel="lightbox" title="Email Invitation"><img class="thumbnail" src="assets/images/Email_Welcome.png"/></a>

## Change Password

To change your account password, complete the following steps:

* Log in to the Contrast interface.
* In the dropdown **User menu** in the upper right corner of the page, select **Your Account**. 
* Select the **Change Password** tab in the left navigation.
* In the form fields, enter your current password and new password. Retype your new password in the next field to confirm it. 

> **Note:** Your new password which must adhere to the [Password Policy](admin-systemsecurity.html#pwd) set by your Administrator. Contrast notifies you of their requirements as you type it in the New Password field. 

* Check the box to agree to the [Terms and Conditions](https://app.contrastsecurity.com/Contrast/static/html/tac.htm).
* Click the button to **Save** your changes.

You must use this password the next time that you log in to Contrast. 

>**Note:** Customers using [Single Sign-On (SSO)](installation-setupauth.html#sso-setup) don't have this option.

## Two-Step Verification

If your administrator has enabled two-step verification, you can add an extra layer of protection beyond your username and password. Complete the following steps to enable the feature:

* From the **Your Account** page, select the **Two-Step Verification** tab in the left navigation.
* Use the toggle to enable two-step verification. 
* Use the radio buttons to select your preferred notification method. You can access verification codes through your Contrast-associated email address or the Google Authenticator mobile application, which is available on the following devices:
	* [Android](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en)
	* [iPhone](https://itunes.apple.com/us/app/google-authenticator/id388497605?mt=8)
	* [Blackberry](https://appworld.blackberry.com/webstore/content/29401059/?lang=en&countrycode=US) 
* If you run into issues using either method, use the backup codes provided.

### Verification codes 

If you choose to receive your verification codes by email, Contrast sends you a verification code to enter on the following configuration screen.  

If you select Google Authenticator, Contrast provides QR code with further instructions. You can scan the QR code, enter the code manually or use the provided dropdown to select the device type. Use the Google Authenticator application to obtain a verification code and validate your device.

Before completing two-step verification setup, you can download a set of backup codes in the form of a *.txt* file, which allows you to login if you encounter an error or get locked out of your account. You must download and save these codes in a secure location. 

### Reconfigure notification methods

If you want to change the way you receive verification codes, you can reconfigure notification settings in the **Two-Step Verification**tab. Once you change your selection, Contrast automatically issues a new set of backup codes. It's not necessary to save your changes. 

<a href="assets/images/TSVUserSettings.png" rel="lightbox" title="User Settings"><img class="thumbnail" src="assets/images/TSVUserSettings.png"/></a>

### Learn More 

To learn more about Administrator settings, read the related article in [Organization Settings](admin-orgsecurity.html#security-tsvp). For some helpful tips on verification codes, go to the [Troubleshooting article](troubleshooting-auth.html#tsv-trouble).
