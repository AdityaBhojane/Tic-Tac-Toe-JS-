# Tic Tac Toe Game Project Flow 

## Step By step understanding
1) Create an HTML structure main container and 9 boxes
2) Style them accordingly using CSS 
### JS Logic - 
- Select element using DOM selectors
- add event listener and then we can check event.target 
- If textContent of target is empty then we can add 'O' or  'X'
- inside that we have check is pattern found in boxes like same 'X' or 'O' in a row or in column or in diagonals 
- for that we can make an patten array when we can store all patterns like 0,1,2 and 2,3,4 like that and using DOM selector we can get all Boxes from website in array format so we can set a loop to check is that pattern matches then we can return true
- also we can check using loop is all boxes are empty or not is not empty then false and if yes then true and it means its a Draw 
- for rest all boxes also we can use simple loop to iterate and make its textContent empty 

#### in this way we can make an tic tac toe game !