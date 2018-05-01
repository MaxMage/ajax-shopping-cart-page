# Quantity update by AJAX for Magento 2

The module allows to update quantity on the  shopping cart page 'checkout/cart/' by AJAX. After the update recalculate totals and rebuild mini shopping cart.

## Installation

1. Go to Magento 2 root directory

2. Enter following commands to install module:

   ```
   composer require maxmage/ajax-shopping-cart-page
   ```

3. Enter following commands to enable module:

   ```
   php bin/magento module:enable MaxMage_AjaxShoppingCartPage
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   ```
