# csharp4.8 - Solutions to TestDome C# questions 


**1. Alert Service - C#** 

Refactor the AlertService and AlertDAO classes:

  Create a new interface, named IAlertDAO, that contains the same methods as AlertDAO.
  AlertDAO should implement the IAlertDAO interface.
  AlertService should have a constructor that accepts IAlertDAO.
  The RaiseAlert and GetAlertTime methods should use the object passed through the constructor.


[Solution - AlertService.cs](https://github.com/ks7788/csharp4.8/blob/master/AlertService.cs)

**2. Merge Names - C#**

  Implement the UniqueNames method. When passed two arrays of names, it will return an array containing 
  the names that appear   in either or both arrays. The returned array should have no duplicates.

  For example, calling MergeNames.UniqueNames(new string[]{'Ava', 'Emma', 'Olivia'}, new string[]{'Olivia', 'Sophia', 'Emma'})    should return an array containing Ava, Emma, Olivia, and Sophia in any order.

[Solution - MergeNames.cs](https://github.com/ks7788/csharp4.8/blob/master/MergeNames.cs)

**3. Palindrome - C#**
A palindrome is a word that reads the same backward or forward.

Write a function that checks if a given word is a palindrome. Character case should be ignored.

For example, IsPalindrome("Deleveled") should return true as character case should be ignored, resulting in "deleveled", which is a palindrome since it reads the same backward and forward.

[Solution - Polindrome.cs](https://github.com/ks7788/csharp4.8/blob/master/Polindrome.cs)
