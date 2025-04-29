1. 3; i is accessible globally and was incremented from 0, 1, to 2 and then stops at 3
2. 150; explanation: (i = 0) discountedPrice = 100 * (1 - 0.5) = 50 | (i = 1) discountedPrice = 200 * (1 - 0.5) = 100 | (i = 2) discountedPrice = 300 * (1 - 0.5) = 150
3. 150; explanation: 
- 100 * 0.5 = 50 → finalPrice = 50
- 200 * 0.5 = 100 → finalPrice = 100
- 300 * 0.5 = 150 → finalPrice = 150
4. returns (3) [50, 100, 150], which is the value of discounted
5. error; i is a local variable and therefore cannot be accessed outside of the for loop
6. error: discountedPrice is a local variable only accessible inside the for loop
7. 150; explanation: (finalPrice is updated for each iteration)
- 100 → 50
- 200 → 100
- 300 → 150
8. [50, 100, 150]; returns just the discounted value, no console logs
9. error; i is locally defined
10. 3, it is the given length passd in, and assigned to prices array (which is [100, 200, 300])
11. returns array [-50, 100, 450]; explanation:
- i = 0 | discountedPrice = 100 * (0 - 0.5) = 100 * (-0.5) = -50
- i = 1 | discountedPrice = 200 * (1 - 0.5) = 200 * 0.5 = 100
- i = 2 | discountedPrice = 300 * (2 - 0.5) = 300 * 1.5 = 450
12. Given the above Object, write the notation for:
- A. student.name
- B. student["Grad Year"]
- C. student.greeting()
- D. student["Favorite Teacher"].name
- E. student.courseLoad[0]
13. Arithmetic
- A. '32' bc + is a concatentation
- B. 1; numeric conversion
- C. 3; 0 is null
- D. 3null; + is a concatentation
- E. 4; true is 1
- F. 0; false is 0, null is 0
- G. 3undefined; + is concatentation
- H. NaN; undefined isnt a number
14. Comparison
- A. true; '2' converts to 2
- B. false; String comparison is lexicographic
- C. true; == allows type coercion
- D. false; === checks type and value
- E. false; true is 1, 1 != 2
- F. true; Boolean(2) is same type and value
15. == checks for value equality with type coercion, while === checks for both value and type equality, no coercion.
17. all vals [1, 2, 3] are multiplied by 2 to get [2, 4, 6]
19. 
1  
4  
3  
2
