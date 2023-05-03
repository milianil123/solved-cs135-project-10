Download Link: https://assignmentchef.com/product/solved-cs135-project-10
<br>
<u>Project [10]: File Input/output</u>




<h1>Project Goals</h1>

The goal of this project is to:

<ol>

 <li>Get students familiar with functions to read from and write to files, in text and binary modes</li>

</ol>




<strong><u>Important Notes:</u> </strong>

<ol>

 <li><strong>Formatting: </strong>Make sure that you follow the precise recommendations for the output content and formatting: for example, do not change the text in the first problem from “Please enter item data</li>

</ol>

(part number, quantity, price): ” to “Enter the item: ”. Your assignment will be auto-graded and any changes in formatting will result in a loss in the grade.

<ol start="2">

 <li><strong>Comments: </strong>Header comments are required on all files and recommended for the rest of the program. Points will be deducted if no header comments are included.</li>

 <li><strong>Restriction: </strong>The use of goto statements anywhere within this program is prohibited. Points will be deducted if gotois used.</li>

</ol>




<h1>Problem 1</h1>

Write a program to repeatedly ask the user to enter information regarding inventory for a business (item part number, quantity, price) and then saves the information to a file called inventory.txt. The program stops the loop when the user enters 0 for the part number.

The program should function as follows (items underlined are to be entered by the user):

This program stores a business inventory.

Please enter item data (part number, quantity, price): <u>3, 1, 2.4</u>

Please enter item data (part number, quantity, price): <u>1, 4, 3.0</u> Please enter item data (part number, quantity, price): <u>0</u> Thank you. Inventory stored in file inventory.txt.

<strong>Note: </strong>

<ul>

 <li>Your program must write to the file in binary mode, using the fwrite function</li>

</ul>




Save your program as save_inventory.c










<strong>Challenge for problem 1 </strong>(10 extra credit points):

Modify your program to check if the user enters an identical part number again. If this occurs, the program should print a message and ask for the input again.

The program should function as follows (items underlined are to be entered by the user):

This program stores a business inventory.

Please enter item data (part number, quantity, price): <u>3, 1, 2.4</u>

Please enter item data (part number, quantity, price): <u>1, 4, 3.0</u>

Please enter item data (part number, quantity, price): <u>3, 4, 3.0</u>

This item has been entered before.

Please enter item data (part number, quantity, price): <u>2, 4, 1.3</u> Please enter item data (part number, quantity, price): <u>0</u> Thank you. Inventory stored in file inventory.txt.

Save your challenge separately as save_inventory_c.c




<h1>Problem 2</h1>

Write a program to read information from the inventory.txt file and display it to the screen, formatted as follows: Part#, Quantity, and Item Price in the table header should be separated by tabs. The part number field should take 5 spaces (values right justified), the quantity field should take 8 spaces (values right justified), and the price field should take 9 spaces with 2 numbers after the decimal (values right justified, with the $ sign in front of the price).

The program should function as follows:

Below are the items in your inventory.

Part#   Quantity        Item Price

3          1        $     2.40

<ul>

 <li>4 $     00</li>

 <li>4 $     30</li>

</ul>

<strong>Note: </strong>

<ul>

 <li>Your program must read from the file in binary mode, using the fread function</li>

</ul>




Save your program as disp_inventory.c





