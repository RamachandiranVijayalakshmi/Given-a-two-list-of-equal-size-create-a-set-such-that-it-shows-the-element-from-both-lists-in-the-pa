## Given-a-two-list-of-equal-size-create-a-set-such-that-it-shows-the-element-from-both-lists-in-the-pa
## Sample code to check the two list 
```sh
firstList = [2, 3, 4, 5, 6, 7, 8]
print("First List ", firstList)

secondList = [4, 9, 16, 25, 36, 49, 64]
print("Second List ", secondList)

result = zip(firstList, secondList)
resultSet = set(result)
print(resultSet)
```
## Expected output
First List  [2, 3, 4, 5, 6, 7, 8]
Second List  [4, 9, 16, 25, 36, 49, 64]
Result is  {(6, 36), (8, 64), (4, 16), (5, 25), (3, 9), (7, 49), (2, 4)}
