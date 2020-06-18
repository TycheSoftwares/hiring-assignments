# WordPress Engineer Assignment

Have you already developed on WordPress? If you have already developed a plugin or theme on WordPress, you can use it as a work sample. Just make sure your code is compliant with the rules.

List of Assignments

1. WordPress Plugins
2. WooCommerce Plugins

<strong>WordPress Plugin Assignments</strong>

1a. Create a Quick Draft plugin. This should allow any custom post type to be converted to Draft status from the listing page and from the top admin bar.


1b. In Elementor plugin, there is this Github issue here: https://github.com/elementor/elementor/issues/8071 . The assignment is to work on creating a widget to display the Cross-Sell products. Most of the details are mentioned in the issue itself. The widget should display the products that are added here: https://screencast.com/t/vy5Spgpe . 


<strong>WooCommerce Plugin Assignments</strong>

2a. Create a page in WP Dashboard named "Woo API" with below approach:

 - List the 20 recent Products and Orders using REST API. Here no need to give pagination for now.
 - For the products, it should allow the Product Name to be updated for those via REST API 
 - Please note: do not use the standard WooCommerce functions. The calls must be via REST API
 - Please note: we would prefer if you build the UI using React or Vue.
 
 

2b. Use this plugin: https://wordpress.org/plugins/order-delivery-date-for-woocommerce/ . 

On the checkout page, please add a radio button field above the delivery date field. It should have 2 options: 

1. Delivery
2. Pickup

By default, the "Delivery" option should be selected. Whichever option the user selects, it should be saved as a custom meta field for that order.
