# Submitting Bulk

When running multiple entries for ACO checkouts, each profile must appear unique to the retailer’s system. Retailers often cancel orders when duplicate information is detected, so every entry must use **distinct account details**.

{% hint style="info" %}
Create a copy of this Bulk Sheet [**Click Here**](https://docs.google.com/spreadsheets/d/1MoieUlVuSgxSydDNvzZ1bTiAVPB67zdKMFa2tWe-vFY/edit?usp=sharing)
{% endhint %}

> **Four main elements: unique cards, emails, addresses, phone numbers.**

## **Step-By-Step Guide**

{% stepper %}
{% step %}
#### **Unique Payment Cards**

* Each entry should use a **different card number**. Using the same card across multiple profiles significantly increases the chance of cancellations.
* Multiple physical cards, if available.
* Virtual Card Numbers **(VCCs)** from providers like AMEX and Capital One Eno.
{% endstep %}

{% step %}
#### **Unique Emails**

* Every profile must use a **different email address** when creating retailer accounts.
* Catchalls, iCloud HME, Outlook Aliases, and real Emails are all applicable.&#x20;
{% endstep %}

{% step %}
#### **Jigged Addresses**

* Retailers often detect duplicate orders based on identical addresses.
* Address jigging slightly modifies the address while keeping it deliverable.
{% endstep %}

{% step %}
#### **Unique Phone Numbers**

* Using unique phone numbers prevents retailers from linking multiple checkouts.
* Most retailers do not SMS verify so random phone numbers will work.
* Make sure your area code matches.
{% endstep %}
{% endstepper %}

***

## **IMAP Setup for Bulk Entries**

When submitting bulk ACO entries, retailers often send **verification codes, login confirmations, or order confirmations** to the email associated with each account. IMAP allows the ACO system to automatically read these verification emails so checkouts can be completed without manual input.

If you are running **a large number of accounts (for example, 100–500 Walmart accounts)**, manually configuring IMAP for every single email would be extremely time-consuming. Instead, a much simpler and more efficient approach is to **forward all emails to a single master inbox** and configure IMAP on that one email.

## **Master Inbox**&#x20;

Using email forwarding allows you to manage verification emails from hundreds of accounts in one place.

* Setup IMAP on your main email which will be the central inbox for all verification codes.
* Enable email forwarding for each account email to the master inbox.

#### **Benefits**

* Only one IMAP setup is required
* Faster setup for bulk entries
* Easier monitoring of orders and verification emails
* Reduces invalid configuration across multiple accounts
