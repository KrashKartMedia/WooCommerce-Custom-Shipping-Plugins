WooCommerce-Custom-Shipping-Plugins
===================================

This plugin adds a custom shipping method to WooCommerce > Settings > Shipping Called Our Shipping Price

The client we built this for had a need for a custom shipping price and a custom way to add the totals up. 

The wants to charge 9.95 per box shipped.

The clients can fit any 2 items of Small, Mediium, Large, Extra Large into one box. So for every 2 items (as long as then are not Jumbo Size) the shipping price will add 9.95. So 1-2 items of (S,M,L,XL) will cost 9.95 for shipping. 3-4 items will cost 19.90. And so on. 

Every Jumbo size item will Add 9.95 every time one is added. SO you can get the idea by this example:

One small, one medium and 2 jumbo sized items cost $29.85 in shipping alone. 9.95 * 3 = 29.85

This plugin is based off of the Shipping Method API provided by WooThemes Docs. (http://docs.woothemes.com/document/shipping-method-api/)

Installation
===================================

Under Products > Attributes, add a new attribute called Size. Add terms to the attribute called Small, Medium, Large, Extra Large, Jumbo.

Disable all shipping methods and by default, Our Shipping Price will be activated.
