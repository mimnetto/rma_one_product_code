# rma_one_product_code

## Adding One Product to a Table

## Steps

* Open the RAW HTML via manufacture's page
* Search for the exsisting product that you would like to be below the new product. (Ctrl+F to search)
* Find where the code for the exsisting product begins ```<!--NEW ROW --> <tr>```, and the existing product ABOVE IT ends ``` </tr> ```
* Copy and paste the blank product line code between the ``` </tr> ``` and the ```<!--NEW ROW --><tr>```
* Note: All products should start with ```<tr>``` and end with   ``` </tr> ```
* Note: If you are adding a product to be the first product on the table, the same instructions apply
* Note: Code for a blank table with one black product can be found in newTable.html


``` 
<!--NEW ROW -->
<tr><!--MODEL NUMBER ∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆ -->
<td style="background-color: #fff; padding: 2px 10px; border-bottom: 1px solid #E8E8E8; width: 120px;"></td>
<!--DESCRIPTION ∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆ -->
<td style="padding: 2px 10px; border-bottom: 1px solid #E8E8E8; width: 360px;"></td>
<!--PRICE ∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆ -->
<td style="padding: 2px 10px; border-bottom: 1px solid #E8E8E8; background-color: #fff; width: 60px;"><span></span></td>
<!--PDF ∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆ -->
<td style="padding: 2px 10px; border-bottom: 1px solid #E8E8E8; width: 40px; height: 42px;"><a href="#" target="_blank"><img class="__mce_add_custom__" style="display: block; margin-left: auto; margin-right: auto; padding: 5px;" title="pdf-icon.png" src="http://www.rmaelectronics.com/product_images/uploaded_images/pdf-icon.png" alt="pdf-icon.png" width="30" height="32" /></a></td>
<!--SHOPPING CART ∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆∆ -->
<td style="padding: 2px 10px; border-bottom: 1px solid #E8E8E8; background-color: #fff; width: 40px;"><a href="http://www.rmaelectronics.com/cart.php?action=add&amp;product_id="><img class="__mce_add_custom__" style="display: block; margin-left: auto; margin-right: auto;" title="-shoppingcartred.png" src="http://www.rmaelectronics.com/product_images/uploaded_images/-shoppingcartred.png" alt="-shoppingcartred.png" width="38" height="24" /></a></td>
</tr>
```



