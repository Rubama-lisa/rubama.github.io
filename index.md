## Welcome to Property Management System
**This is our Registration page**
.
The features of Registration Page
This project have 4 users. Each user need to register before entering the system.
*   Admin.
*   Seller.
*   Buyer.
*   Agent.


**The first field of registration is Seller name:** This text field receives only string data type.
  
  ```
<tr>
	<td><label for="sellerName">Seller Name : </label></td>
	<td><input type="text" id="sellerName" name="sname" value="<?php echo $sellerName ?>"> </td>
	<td><p><?php echo $sellerNameErr; ?></p><td>
	</tr>

```

**The Next field of registration is Phone Number:** This text field receives only integer data type.

```
<tr>
		<td><label for="sPhone">Phone Number : </label></td>
		<td><input type="text" name="sphone" id="sPhone" value="<?php echo $sPhone ?>"></td>
		<td><p><?php echo $sPhoneErr; ?></p> </td>
    </tr>
```

**The Next field of registration is Gender:** This radio field receives only string data type.

```
<tr>
       <td>
		<!-- Gender  -->
		<label>Gender : </label>
		<input type="Radio" name="gender" value="Male" id="male">
		<label for="male">Male</label>
		<input type="Radio" name="gender" value="Female" id="female">
		<label for="female">Female</label>
		<p><?php echo $GenderErr; ?></p>
		</td>
		</tr>
       
```


![Octocat](Registration.png)
