## Welcome to GitHub Pages
**This is our first page**
.
Registration Page
This project have 4 users. Each user need to register before entering this system.
*   Admin.
*   Seller.
*   Buyer.
*   Agent.


The first field of registration is Seller name which receives only string data type.
  
  ```
<tr>
	<td><label for="sellerName">Seller Name : </label></td>
	<td><input type="text" id="sellerName" name="sname" value="<?php echo $sellerName ?>"> </td>
	<td><p><?php echo $sellerNameErr; ?></p><td>
	</tr>

```

![Octocat](Registration.png)
