## Welcome to Property Management System
**This is our Registration page**
.
The features of Registration Page
This project have 4 users. Each user need to register before entering the system.
*   Admin.
*   Seller.
*   Buyer.
*   Agent.


**The first field of registration is Seller name:** This field receives only string data type.
  
  ```
<tr>
	<td><label for="sellerName">Seller Name : </label></td>
	<td><input type="text" id="sellerName" name="sname" value="<?php echo $sellerName ?>"> </td>
	<td><p><?php echo $sellerNameErr; ?></p><td>
	</tr>

```



![Octocat](Registration.png)
