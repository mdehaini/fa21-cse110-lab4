1. It will print out prices.length which in this case is 3 because the variable being called, i, is defined with var so the variable is available throughout the whole function. i is set to 0 but increases within the for loop until i=prices.length when the loop enters
2. It will print the last price with the discount, in this case 150. The variable being called, discountedPrice, is declared with var so it is available in the whole function. It is set to prices[i] * (1-discount) so when we call with discountPrices([100, 200, 300], .5), so in the last for loop, discountPrice - prices[prices.length-1] * (1-.5) = 150
3. It will print out the last final price, in this case in 150. The variable being called, finalPrice, is declared with var so it is available in the whole function. It is set to Math.round(disocountedPrice * 100)/100 so when we call with discountPrices([100, 200, 300], .5), so in the last for loop where we already discovered discountedPrice = 150, finalPrice = Math.roung(150*100)/100 = 150
4. It will return an array of discounted prices, so in this case it returns [50, 100, 150]. The variable being called, discounted, is declared with var so it is available in the whole function.In this case, the discount is .5 so we multiply our original prices, [100, 200, 300] by .5 to get [50, 100, 150]
5. line 12 will return an error because i is defined with let decleration which means its scope is only within the block it is declared, the if block, and the line which calls it isn't within that block. 
6. line 13 will give an error because it is defined with let decleration which means its scope is only within the block it is declared, the if block, and the line which calls it isn't within that block
7. This will return 150 as the variable is decalred within the function block so it is avaialable in the whole function. In the last loop of the for loop, final price is sent to Math.roung(discountedPrice * 100)/100 which we discovered in number 3 equals 150
8. It will return an array of discounted prices, so in this case it returns [50, 100, 150]. The variable being called, discounted, is declared with let so it is available in the entire block it is declared which in this case is the function block. In this case, the discount is .5 so we multiply our original prices, [100, 200, 300] by .5 to get [50, 100, 150]
9. This line returns an error since i is declared with let which means that it is only available in the block it is declared, the for loop. line 14 tries to call it outside of this loop which isn't possible so we get the error
10. This will print the length of prices, in this case the input is [100, 200, 300] so prices.length = 3. We can call this variable because i) it is declared with const which means it is available within the block it is declared in so it is available within the function and ii) const cannot be reassigned which is true in this case. 
11. This returns an array of the prices discounted and since the input prices are [100, 200, 300] and the disocunt is .5, we get [50, 100, 150]. We can call this variable because i) it is declared with const which means it is available within the block it is declared in so it is available within the function and ii) const cannot be reassigned which is true in this case cause pushing a new variable is not the same as reassigning the variable. 
12. Data Types: 
    - A. student.name
    - B. student['Grad Year']
    - C. student.greeting()
    - D. student['favorite Teacher'].name
    - E. student.courseLoad[0]
13. Arithmetic: 
    - A. '5': since stringd map to their exact integer representation so we just have '3' + 2 = '5'. We get a string since one of our additives is a string 
    - B. '1': since stringds map to their exact integer representation so we just have '3' - 2 = '1'. We get a string since one of our additives is a string 
    - C.  3: null maps to 0 and sringd map to their exact integer representation so we have 3 + 0 = 3
    - D. '3': null maps to 0 and strings map to their eexact integer representation so we have '3' + 0 = '3'. We get a string since one of our additives is a string 
    - E.  4: true maps to 0 so we have 0 + 3 = 3
    - F.  0: false and null map to 0 so we have 0 + 0 = 0
    - G. '3': undefinded maps to 0 and strings map to their exact integer representation so we have '3' + 0 = '3'. We get a string since one of our additives is a string 
    - H. '3': undefinded maps to 0 and strings map to their exact integer representation so we have '3' - 0 = '3'. We get a string since one of our additives is a string 
14. Comparison: 
    - A. true: strings map to their exact integer represnetation so this is the same as 2 > 1 which is true
    - B. true: strings map to their exact integer representation so this is the same as 2 < 12 which is true
    - C. true: == just checks if system is equal with type conversion and strings map to their exact integer representation so this is the same as 2 == 2 which is true
    - D. False: === checks if system is equal without type conversion and since '2' is a sting and 2 is an integer they can't be equal
    - E. False: ==  checks if system is equal with type conversion and false maps to 1 so this asks if 1 == 2 which is false 
    - F. True: Boolean(2) returns true since 2 != 0, -0, NaN, undefined, false, or "" and so this question is asking if true == true which is true
15. == checks if the values are equal after type conversion makes them into the same type while === checks if two values are equal without the use of type conversion. 
16. see part2-question16.js
17. our for loop runs from i = 0 to i = array.length-1 and since our array = [1, 2, 3], it runs from i = 0 to i = 2. Everytime the for loop runs, it pushes the value returned by callback(array[i]). Here, callback = doSomething due to the parameters we plugged in so doSomething(array[i]) will return num * 2 (as seen in the function). So we push 1*2 then 2*2, then 3*2 to get newArr = [2, 4, 6]. This is the result. 
18. See part2-question18.js
19. It prints out the numbers in the following order: 1, 4, 3, 2. This is because 3 and 2 have a delay (2 having a longer one since dealy = 1000 ms)
