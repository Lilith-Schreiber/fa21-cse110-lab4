1. print out '3'; because i is for counting how many items in the array, and there are 3 numbers in the prices array
2. print out '150'; discountedPrice is the variable to calculate the discount price, and the loop make it to the last item, 300*(1-0.5)=150
3. print out '150'; also loop to the last item, 150 (discountedPrice) *100/100 = 150
4. [50, 100, 150]; because when it calculate a finalPrice, it will push the finalPrice into the discounted array as one of the item
5. error: i is only defined in for-oloop
6. error: discountedPrice is only defined in for-loop
7. 150; reason is the same as (3)
8. [50, 100, 150]; reason is the same as (4)
9. error: reason is same as (5)
10. 3; the length of the prices ([100, 200, 300]) is 3
11. [50, 100, 150]; reason is the same as (4) and (8)
12. A. student name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[1]
13. A. "32"; since '3' is a string, then appending 2 behind
    B. 1 '-' can only be used for numberic arithmetic, so return int
    C. 3; int goes first, null convert to 0 as int
    D. "3null"; since '3' is a string, null appending to '3'
    E. 4; since boolean cannot use the arithmetic, true convert to 1 as int, adding with 3
    F. 0; 0 (false) + 0 (null)
    G. "3undefined"; string goes first, undefined appending to '3'
    H. NaN; cannot - undefined
14. A. true; '2' convert to int, 2>1 is true
    B. false; string comparison, 2<1 is false
    C. true; '2' convert to int, 2=2 is true
    D. false; === strictly bonded with data type, thus int cannot compare with string
    E. false; true is 1 in int, not equal to 2
    F. true; boolean 2 is true, true = true
15. === inclued the comparison of data type, so if the data type is different, === will return false; in contrast, == does not consider data type, so 2=='2' will return true
16. answer in part2-question16.js
17. [2, 4, 6]; we pass the array [1, 2, 3] into the function modifyArray, then we use the loop to pass every item to the function doSomething to double the number
18. answer in part2-question18.js
19. 1 4 3 2