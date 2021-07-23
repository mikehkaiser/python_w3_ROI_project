# Property ROI Project

<p>This project is designed to receive user input on a potential property purchase.
Based on projected purchase price, expenses, and income, it then calculates an expected ROI for that property.</p>

<p>This was an exercise in Object-Oriented Programming working with a class, dictionaries, and try/catch loops.
I ran into a snag trying to access variables from other methods than where the originated, but in the end was able to complete the project with only
one additional 'global' attribute in the __init__ method.</p>

<p> In order to do that, I had to recreate similar variables in different methods.
The 'new' global attribute was 'cash_pay' which acted as a flag. There is a user input question about whether
the property is being purchased with cash. If 'yes', there is no monthly mortgage payment, but if the user says
'no', and they will have a mortgage, there is a loop within the next method that is triggered by the 'no' input.</p>

<p> To make it work, I instantiate the class object with cash_pay = 'no'. If the user enters 'yes' in the first method,
cash_pay changes to 'yes' and the loop in the second method is bypassed. Otherwise, if it stays 'no', the loop is triggered.</p>
