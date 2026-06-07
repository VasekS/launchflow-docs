# Scheduling price changes

Price changes are the heart of Launch Flow. You select the products or collections, set the new prices, and choose when they go live.

Unlike Shopify's built-in discount codes, Launch Flow changes the **actual listed price** of the product. That means the new price shows everywhere the product appears — collection pages, search, product pages — without the customer needing to enter a code at checkout.

### How it works

* Launch Flow records the current price as a snapshot.
* At the start time, it writes the new price to each selected product.
* If you set an end time, it restores the snapshot price when the promotion ends.

{% hint style="warning" %}
**Avoid editing the same products elsewhere mid-launch.** If you manually change a price (or another app does) while a Launch Flow promotion is live, the snapshot may no longer reflect what you expect when it's time to roll back. Make price edits to those products through Launch Flow while a launch is active.
{% endhint %}
