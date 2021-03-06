<!--
title: "Generic Webhook Integration"
description: "Integrating Generic Webhooks with Contrast"
tags: "Admin organization settings integrations generic webhook"
-->


Contrast supports generic webhook integration, which allows you to receive notifications on any URL that receives POST messages. The simple integration format includes an optional Payload field where you can include a `title` and `message`.

<a href="assets/images/Webhook-integration.png" rel="lightbox" title="Set up Webhook integration"><img class="thumbnail" src="assets/images/Webhook-integration.png"/></a>

## Setup

* Retrieve the URL to which you want Contrast to send notifications.
* Navigate to the **User menu > Organization Settings > Integrations** tab.
* In the row for Generic Webhook, click the button to **Connect**.
* Name the webhook, and paste the URL in the designated field.
* Select the application(s) that you want to filter.
* If you want to complete the Payload field, enter the `title` and `message`. Sample code:

```javascript
{
	'title':   'Contrast Security Notification',
	'message': 'Test User commented on a Insecure JSP Placement vulnerability in WebGoat. \"Fixed in CVE-2015\"'
}
```
You can also add placeholders in the payload so that Contrast will fill in for different notifications - a new application, server, vulnerability, etc. 

The placeholders available for use are:

* Title
* Message

If you were using the Generic Webhook to create a VictorOps integration, the sample payload would be as follows:

```json
{ 
	"message_type":"INFO", 
	"entity_id":"$Title", 
	"entity_display_name":"$Title", 
	"state_message":"$Message" 
}
```
 
Where Contrast data fills in the Title and Message fields, according to notifcation. 

* Click **Save**.

You are connected!

