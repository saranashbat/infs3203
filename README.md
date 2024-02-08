Bug 1:
In line 29 and 30 the user ask for a number but if this feilds is left empty by the user the user gets and error from the inteprator , 
This needs to be added as an alert to the user to know that this feilds cant be left as empty.

x = float(input("Enter first number: ")) 
y = float(input("Enter second number: "))
  Link: https://github.com/saranashbat/infs3203/commit/afd1afe0432eceb9adcfeb74787b04cf0d9d3e67#commitcomment-138440719


Bug 2: 
Before: the return gives the total sum of two inputs the user entered because of the add sign. (line 6)
After changing: the return subtracts the two inputs the user entered because of the subtract sign. (line 6)
  Link: https://github.com/saranashbat/infs3203/commit/3660ff9f1559b0d06c65019d530be895f5e95203#commitcomment-138415650
