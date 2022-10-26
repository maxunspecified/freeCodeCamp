---
id: aaa48de84e1ecc7c742e1124
title: Palindrome Checker
isRequired: true
challengeType: 5
isHidden: false
---

## Javascript

```

  function palindrome(str) {
    var string = str.toLowerCase().split(/[^A-Za-z0-9]/gi).join('');
    var aux = string.split('');
    if (aux.join('') === aux.reverse().join('')){
      return true;
    }
    return false;
  }

```