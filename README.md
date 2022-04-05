Magento2 Extension - IoVista_ProductList

Build a stand-alone extension that displays chosen products in a new customer frontend page accessed from the My Account section.

Requirements:

    1. Create a new Yes/No attribute for products. The code should be handle_display [ DONE ]
    2. Develop a new page that only a logged-in customer can access [ DONE ] Eg. domainURL/productlist/customer/index/
    3. Add a new item into the My Account menu [ DONE ]
    4. Display a product list for products with the handle_display attribute set to Yes [ DONE ]


Optional features:

    1. Add a custom configuration into the System Configuration to handle the limit number of products displayed on the customer page. [ DONE ]
    2. Add a slider and show the products in it. Use the mode param to optionally select this view like account/products?mode=slider [ DONE ] eg.domainURL/productlist/customer/index/?mode=slider
    3. Cover the extension with unit tests  [ DONE ]

Important:

    1. Develop the extension using the CE 2.4 version, following Magento’s best practices
    2. Try to cover as many edge cases as you can think of. For example - what if the handle_display attribute already exists
        Doesn't create any issue
    3. Use git, host the code on Bitbucket/Github, and provide a link
    4. Make sure to include a link to a live demo of this extension
    5. Include a README file that covers module functionality

- Create handle_display attribute using Install script
- Admin configuration based display products
    Eg. No. Of Products Display : 10 then it's display 10 products in my account product list section
- It's work with all products type
- Without login customer can't access customer product list page
- Display message when there is not product select for product list
- Check with enable/disble and catalog visibility


Stores > Configuration > IoVista ProductList > 
    Set No. Of products

Catalog > Products > Edit Products
    Display ProductList : Yes


For Slider
    https://magento-754735-2547645.cloudwaysapps.com/productlist/customer/index/?mode=slider
