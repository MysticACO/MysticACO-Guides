# Target Cancellations

This guide explains how to check why a Target order was cancelled and what the cancellation reason means.

Understanding the reason behind a cancellation can help you adjust your setup and avoid similar issues in future checkouts.

***

## **How To Check**

{% stepper %}
{% step %}
#### **Login to your Target account**

* The steps below will **NOT** work unless you are already signed in.
{% endstep %}

{% step %}
#### **Copy the link below**&#x20;

* Replace **PUTYOURORDERNUMBERHERE** with your cancelled Target order number.
* [https://api.target.com/guest\_order\_aggregations/v1/PUTYOURORDERNUMBERHERE?key=f5e5f35b610d54dff3f3c9087c837f479f22686e](https://api.target.com/guest_order_aggregations/v1/PUTYOURORDERNUMBERHERE?key=f5e5f35b610d54dff3f3c9087c837f479f22686e)
{% endstep %}

{% step %}
#### Once the page loads

* CTRL + F&#x20;
* Search for `reason` to view the internal cancellation message
{% endstep %}
{% endstepper %}

## **Item Demand**

Item demand is the most common cancellation and typically reflects how many checkouts are coming from your profiles during a release. After a few checkouts, your profiles are more prone to Item Demand cancellations. It is crucial that you use as many unique addresses as possible.

#### **Common Fix**

* Aged Accounts with Order History
* Diversify your Jigs
* Using different cards (Hard Cards / Red Card)

## **Reseller**&#x20;

A reseller flag usually happens when too many orders are placed from the same zip code within a short period of time. While Target does not publicly confirm an exact threshold, it is recommended to wait 24 hours before placing any additional orders from the same ZIP code. Reseller isn't always permanent. You can always test this by placing manual orders on everyday household items. If you are still getting reseller cancellations, it is best to use a new account.

#### **Common Fix**

* Apply strong Jigs
* Swap payment method
* Create a new account

## **Quantity Limit**

Target typically limits "High Demand" items to 2 orders maximum. This cancellation isn't necessarily bad, as it just means that the account has reached the purchase limit for that specific product. These limits usually reset after 24 hours, allowing the account to attempt to checkout again.

***

## **When an Account Is Likely Burnt**

In extreme cases, an account may become heavily flagged

#### **Signs of a Burnt Account:**

* Orders are cancelled instantly with Reseller Reason
* Inability to successfully checkout manual
* Repeated cancellations after changing Jigs / Payment Method
