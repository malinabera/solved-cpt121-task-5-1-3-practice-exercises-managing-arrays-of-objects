Download Link: https://assignmentchef.com/product/solved-cpt121-task-5-1-3-practice-exercises-managing-arrays-of-objects
<br>
<strong>Task 5.1.3 Practice Exercises – Managing Arrays of Objects </strong>

<ol>

 <li><strong> Assume that the application class below makes use of the Account class discussed previously </strong>import java.util.*; public class TestAccounts2</li>

</ol>

{ public static void main(String args[])

{

String accountID, name; double balance; Scanner sc = new Scanner(System.in));

/*** Array used to store up to 10 accounts ***/

Account[] accounts = new Account[1];

<strong>/*** CODE for part a) goes here ***/ </strong>…

<strong>/*** CODE for part c) goes here *** … </strong>

// print details for all accounts

System.out.println(“Account Details”);

<strong>/*** Code for part b) goes here ***/ … </strong>

}

}

<ol>

 <li>Write code to populate the array with the Accounts containing the following details:</li>

</ol>

<table width="366">

 <tbody>

  <tr>

   <td width="129">ID</td>

   <td width="123">Name</td>

   <td width="113">Balance</td>

  </tr>

  <tr>

   <td width="129">S5234</td>

   <td width="123">David</td>

   <td width="113">$1000</td>

  </tr>

  <tr>

   <td width="129">S1239</td>

   <td width="123">Cliff</td>

   <td width="113">$2000</td>

  </tr>

  <tr>

   <td width="129">S4236</td>

   <td width="123">Martin</td>

   <td width="113">$3000</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Write code which iterates through the objects that are currently stored in the array and prints their details to the screen. Your iteration loop should cease executing once it has gone past the last object in the array.</li>

 <li>What will be the output printed by the program if we replace the indicated comment for part C in the code above with each of the following blocks?</li>

</ol>

Tip: You may find drawing diagrams of the array and the objects each element is pointing to useful when considering the effect of each code segment.

<ol>

 <li><strong>a[1] = a[0]; a[2] = a[1]; a[0] = a[2];</strong></li>

 <li><strong>a[0] = a[1];</strong></li>

</ol>

<strong>a[0].withdraw(100); a[1].withdraw(100);</strong>

<ul>

 <li><strong>a[0].transfer(a[1],500); a[1].transfer(a[2],500);</strong></li>

</ul>