# ConstraintSatisfaction
TUM-WS 17/18 Techniques in Artificial Intelligence Constraint Satisfaction Problem


<b>Problem Definition</b>

It is the night before Christmas and you are in the only shop in Munich still open. You still need to
buy presents for your Mum, your Brother, your Grandma, your Grandpa, your Cousin, your Aunt, your
Uncle, and your Significant Other. In the shop there are:

  • Dave Brubeck CDs, costing 10 Euro
  
  • Luxury christmas socks, costing 7 Euro
  
  • Boxes of chocolates, costing 4 Euro
  
  • Coffee mills, costing 12 Euro
  
Consider the following constraints:

1. Each person must get exactly one present
2. You have a total budget of 52 Euro
3. Your mum, brother, and significant other must get different presents
4. Your uncle and cousin must get different presents
5. Your grandparents must get different presents
6. Your mum and uncle must get different presents
7. You cannot get chocolates for your mum, brother, significant other, or grandpa
8. Your cousin must not get socks
9. There is only one coffee mill in the shop
10. There are no more than 2 CDs in the shop
11. There are no more than 4 boxes of chocolates in the shop
12. Your brother must get a CD
13. Nobody gets chocolates

Model the constraint satisfaction problem in Savile Row. For each of the following subsets of constraints,
find the solution, if it exists:

Problem 1.1: { 1 – 12 }

Problem 1.2: { 1 – 3, 6 – 13 }

Problem 1.3: { 1, 8 – 13 }

Problem 1.4: { 1, 3 – 9, 11 – 13}

Problem 1.5: { 1, 3 – 12 }

<b>My Solution</b>

Choice of variables: I chose to assign the following as my decision variable:

x_ij  = { 1 , if present i is bought for person j
	  0 , otherwise}
,where i = {1,2,3,4} ; j = {1,2,3,4,5,6,7.8}

The mentioned numbers correspond to i={Mum, Brother, Grandma, Grandpa, Cousin, Aunt, Uncle, SO} and j={CD, Socks, Chocolates, Mill}, respectively.

<b>Solution 2.1:</b>

No solution found

<b>Solution 2.2:</b>

No solution found

<b>Solution 2.3:</b>

Mum: Socks

Brother: CD

Grandma: Socks

Grandpa: Socks

Cousin: Mill

Aunt:Socks

Uncle: Socks

SO: Socks


<b>Solution 2.4:</b>

Mum: Mill

Brother: CD

Grandma: Socks

Grandpa: CD

Cousin: CD

Aunt: Socks

Uncle: Socks

SO: Socks


<b>Solution 2.5:</b>

Mum: Mill

Brother: CD

Grandma: Chocolates

Grandpa: Socks

Cousin: Chocolates

Aunt: Chocolates

Uncle: Socks

SO: Socks

