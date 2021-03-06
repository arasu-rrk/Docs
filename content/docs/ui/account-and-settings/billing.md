---
layout: page
weight: 0
group: billing
title: Billing
seo:
  title: Billing
  description: Manage your SendGrid billing settings
  keywords: billing, contacts, email credits, refund, plans, cancel, upgrade, downgrade
navigation:
  show: true
---

You can update your plan and billing details on the [Account Details page](https://app.sendgrid.com/account/billing) in the UI.

For more information about understanding your bill, see [Reading your invoice]({{root_url}}/ui/account-and-settings/reading-your-invoice/).

When you create or upgrade to a paid account, you add a credit card in for automatic payments. This will allow SendGrid to make the recurring package charges for your account without having to notify you each month of the bill. SendGrid relies on a PCI-DSS compliant 3rd party billing provider to store, process, and manage payment card processing.

##     Payment methods

SendGrid accepts credit or check cards. We charge accounts on a monthly basis; we do not offer pre-payment, quarterly billing, or annual billing at this time. We don’t accept PayPal, wire transfer, checks, or any card requiring a PIN.

You can update your card information, retry a failed payment, and export past invoices for your business on the Plan & Billing tab of your [Account Details]( https://app.sendgrid.com/account/billing) page. It is also possible to change your package type and cancel your account from this page.

##     Marketing Campaigns Contacts

Each email sent using the UI or API costs one credit - this counts towards your monthly plan volume, just like the messages you already send. In addition to this normal charge, if you are using Marketing Campaigns to store contacts, you are charged for storing those contacts:

**Your first 2,000 contacts are free. After 2,000 contacts, we charge $10.00 per 10,000 stored contacts per month.**

We charge based on the highest number of contacts stored in the preceding month. Think of it as a high-water mark, so even if you reduce your contacts before your next bill rolls around (the 1st of each calendar month), we charge for whatever upper limit was reached.

 ###     Subusers

Each subuser may store up to 2,000 contacts for free before we charge the same rate of $10.00 per 10,000 contacts each month. Any additional charges due for storing contacts on a subuser account will appear in the parent account's monthly invoice.

<call-out>

We bill the parent account for each unique contact, regardless of how many lists or segments that contact appears on. However, if there are one or more subusers under a parent account, we bill the parent account for all unique contacts stored on each account, even for the same contacts stored on multiple subuser accounts.

</call-out>

##     Billing frozen and billing warned

**Billing warned - “You have unpaid invoices. Please update your payment details or retry payment.”**

This is a warning that your service may be interrupted unless you settle any outstanding balance on your account. This warning may occur if the card on file for your account gets declined when we attempt to process payment on the first of the month.

To update your account, please update your credit card on file by logging into the SendGrid UI and going to the Plan & Billing tab on your [Account Details page]( https://app.sendgrid.com/account/billing). Update your card information and then click **Save**. Once you update the card on file, the payment processes automatically, and your account is unfrozen.

**Billing Frozen**

If you find your account suddenly unable to send mail within the first week of the month, your account could be in a billing frozen state. This state occurs when the card on file for your account gets declined when we attempted to process payment on the first of the month.

To reactivate your account, please update your credit card on file by logging into the SendGrid UI and going to the Plan & Billing tab on your [Account Details page]( https://app.sendgrid.com/account/billing). Update your card information and then click **Save**. Once you update the card on file, the payment processes automatically, and your account is unfrozen.

##     Email credits

Every email processed by SendGrid uses an email credit. Free, Essentials, Pro, and Premier accounts will see their email credits reset the 1st day of each month at 12:01 Pacific Time.

##     Overages

Depending on your package, you will be charged a small amount per-email for each email that you send beyond the credit limit of your current package. Any overage charges get added to the invoice of the month _after_ the over-limit sending occurred.

<call-out>

Upgrading your account does NOT absorb overage charges already incurred, so make sure you are using the right package for your use case.

</call-out>

##     Requesting a refund

You must meet both criteria below for a refund to be considered:

- You have not used your account in the current calendar month.
- You have no overages, and you have no contacts stored in Marketing Campaigns.

SendGrid packages operate off of a monthly subscription model, not direct usage. We will not issue a refund if you have used your account in the same calendar month as your request. Instead please cancel your account to avoid any future subscription charges.

Refunds are only applicable to the subscription charge on your account, not for overage or contact storage charges from the prior month. We hold our customers responsible for managing their account credit limits and contact storage.

If you meet these conditions, please respond directly to the invoice email you have received, or email billing@sendgrid.com to begin the discussion about a possible refund.

##     Changing your plan

You can change your plan under the Plan section on the Plan & Billing tab of the [Account Details page]( https://app.sendgrid.com/account/billing).

##     Cancel your account

To cancel your account, go the bottom of the Plan & Billing section of your [Account Details page]( https://app.sendgrid.com/account/billing), click **Cancel Account**, and follow the prompts.

<call-out>

When you cancel an account, it changes to a [free](https://sendgrid.com/free?mc=SendGrid%20Documentation) plan.

</call-out>

##     Additional Resources

- [SendGrid Pricing](https://sendgrid.com/pricing/)
- [Reading your invoice]({{root_url}}/ui/account-and-settings/reading-your-invoice/)
