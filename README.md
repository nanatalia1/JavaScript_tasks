Project prepared to earn the JavaScript Algorithms ans Data Structores certification by freeCodeCamp.
1) Palindrome Checker
  "A palindrome is a word or sentence that's spelled the same way both forward and backward, 
  ignoring punctuation, case, and spacing."
  
  Program returns true if the given string is a palindrome, otherwise returns false.
  
  Special sumpols, such as 2A3*3a2, 2A3 3a2, and 2_A3*3#A2 can also been passed.
  
2)Roman Numeral Conventer
  Converts a given arabic number in a roman numeral (provided in upper-case).
  
3)Ceasars Cipher
  "One of the simplest and most widely known ciphers is a Caesar cipher, also known as a shift cipher. 
   In a shift cipher the meanings of the letters are shifted by some set amount.

    A common modern use is the ROT13 cipher, where the values of the letters are shifted by 13 places. 
    Thus A ↔ N, B ↔ O and so on."
    
4)Telephone Number Validator
  Validates if the given number matche the US phone number format and it's variants, e.g:
      555-555-5555
      (555)555-5555
      (555) 555-5555
      555 555 5555
      5555555555
      1 555 555 5555.
  If it does match any of the variants above, true us returned, othervise- false.
  
 5) Cash Register
    "Design a cash register drawer function checkCashRegister() that accepts purchase price as the first argument (price), 
    payment as the second argument (cash), and cash-in-drawer (cid) as the third argument.

    cid is a 2D array listing available currency.

    The checkCashRegister() function should always return an object with a status key and a change key.

    Return {status: "INSUFFICIENT_FUNDS", change: []} if cash-in-drawer is less than the change due, or if you cannot 
    return the exact change.

    Return {status: "CLOSED", change: [...]} with cash-in-drawer as the value for the key change if it is equal to the 
    change due.

    Otherwise, return {status: "OPEN", change: [...]}, with the change due in coins and bills, sorted in highest to lowest order, 
    as the value of the change key."
    
    
