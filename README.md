Download Link: https://assignmentchef.com/product/solved-coen-243-assignment-4-strings-user%e2%80%90defined-classes
<br>



Questions

<ol>

 <li><strong>(20 points) </strong>Write a user‐defined function in C++ to display the multiplication of row element of two‐ dimensional array A[5][6] containing integer. The function does not return any value. It will print the multiplication of each row. The array elements are taken from the user in the main function and then the function is called and the array is passed to the function.</li>

</ol>

Example. If A = [ 2 3 4 6 2 1 3 1 0 4 5 8 3 1 0 4 5 2 3 1 1 4 5 9

3 1 3 4 1 8 ]

It will print 288 0 0 540 288 in the output.




<ol start="2">

 <li><strong>(40 marks) </strong>We want to create a class called <strong>Edevice</strong>, which represents the electronic devices of company. A device is defined with the following attributes: category (<strong>string</strong>) (The possible values are” Smartphone”, “Tablet”, “Laptop” and “Smartwatch”), model number (<strong>int</strong>), color (<strong>string</strong>), status (<strong>boolean</strong>) (true for new and false for used), year built (<strong>int</strong>), price (<strong>double</strong>). The member functions of the class <strong>Edevic </strong>must perform the following operations:</li>

</ol>




<ul>

 <li>Return (get) functions for all attributes</li>

 <li>Modify (Set) functions for all attributes</li>

</ul>




To test your class, you need to create, a driver, which is the cpp file that contains the main function. Let’s call this, <strong>testdevice.cpp</strong>. In the main function, you should prompt the user to enter information about two devices, create two objects of the class <strong>Edevice </strong>with the information entered by the user, and finally, test the member functions of the class.




<strong>Deliverables: </strong>

<ul>

 <li>A file called <strong>h </strong>that contains the specification of the class.</li>

 <li>A file called <strong>cpp </strong>that contains the implementation of the member functions of the class.</li>

 <li>A file called <strong>cpp </strong>that contains the main function.</li>

</ul>

1/3







<ol start="3">

 <li><strong>(40 marks) </strong>Define a class called <strong>“House”</strong>, that represents the information of a house. A House is defined with these attributes: age (<strong>int</strong>), type (<strong>string</strong>) (Detached, Semi‐Attached, Attached), rooms (<strong>int</strong>) and cost (double). Functions of the <strong>House </strong>class must perform the following operations:</li>

</ol>




<ul>

 <li>Return (get) functions for all attributes</li>

 <li>Modify (Set) functions for all attributes</li>

 <li>A function called estimatePrice() that returns cost of a house in future based on type and the number of years we’re looking into its price in future. So, it takes the type of the house and the year as input. An attached house, costs $100,000, appreciates 1% every year in first five years and 2% every year afterwards. A Semi‐detached house, costs $150,000, appreciates 2% every year in first five years and 3% every year afterwards. A Detached house, costs $200,000, appreciates2% every year in first five years and 2% every year afterwards.</li>

</ul>

<strong>Hint</strong>: Use this formula to estimate the house price in future:

<strong>Estimated price= current house price*(1+appreciation_rate)<sup>years form now</sup> </strong>

<strong> </strong>

Test your class by prompting the user to enter information about two different houses. Create two objects of the class <strong>House </strong>with the information entered by the user, and finally, test the member functions of the class. Also calculate the estimated price of houses given type and age (include 1 attached and 1 detached)





