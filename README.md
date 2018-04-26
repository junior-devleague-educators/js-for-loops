# JavaScript For Loops

**For loops are great for:**

1.  Iterating through an array to access values
2.  Running a set of instructions over and over again for a set amount of times

## Exercises

After each exercise store your function in a variable and console log the result. Example:

```
var numArr = [1,2,3,4,5];

function getSum(num) {
  var result = 0;
  for (var i = 0; i < num.length; i++) {
    result += num[i];
  }
  return result;
}

var sum = getSum(numArr);
console.log(sum); // outputs 15
```

**1. DOUBLE A NUMBER**

**a.** Declare a variable called `numsToDouble`. Set it's value to an array containing the values: `[2,4,6,8]`.<br>
**b.** Declare a function called `doubleNumbers` with one parameter called `number`.<br>
**c.** Inside the function, write a `for` loop to iterate through the `numsToDouble` array. Your `return` value should output the following: `"4 8 12 16"`

**2. PRESIDENTS**

**a.** Declare a variable called `presidents`. Set it's value to an array containing the first 5 presidents last names: `Washington, Adams, Jefferson, Madison, Monroe`.<br>
**b.** Declare a function called `getPresidents` with one parameter called `names`.<br>
**c.** Inside the function, write a `for` loop to iterate through the `presidents` array. Your `return` value should output a message like:

```
The value at index 0 is: Washington.
The value at index 1 is: Adams.
The value at index 2 is: Jefferson.
The value at index 3 is: Madison.
The value at index 4 is: Monroe.

* Your result may output as a long line.
* Don't worry about not having line breaks.
```

**3. ADD ONLY EVEN NUMBERS**

**a.** Declare a variable called `evenNumberArray`. Set it's value to an array containing the numbers from `1-10`<br>
**b.** Declare a function called `addingEvens` with one parameter called `numbers`.<br>
**c.** Inside the function, write a `for` loop to iterate through the `evenNumberArray`. Your `return` value should output be the sum of only the even numbers.

**4. NAP TIME**

**a.** Declare a variable called `napSchedule`. Set it's value to an array containing boolean values: `[false, false, true, true, false]`.<br>
**b.** Declare a function called `isNapTime` with one parameter called `schedule`.<br>
**c.** Inside the function, write a `for` loop to iterate through the `napSchedule` array. If nap time is `true` output `"zZZzzZzz"`, otherwise ouput `"Get to work! It's not nap time!"` Your `return` value should output a message like:

```
Get to work! It's not nap time!
Get to work! It's not nap time!
zZZzzZzz
zZZzzZzz
Get to work! It's not nap time!

* Your result may output as a long line.
* Don't worry about not having line breaks.
```

**5. AVERAGE SCORE**

**a.** Declare a variable called `scoreList`. Set it's value to an array containing number values: `[77, 83, 95, 88]`.<br>
**b.** Declare a function called `getAverageScore` with one parameter called `avgScore`.<br>
**c.** Inside the function, write a `for` loop to iterate through the `scoreList` array. Your `return` value should output the average score with a message like: `"The average score is: " + avgScore.`

**6. GREETING**

**a.** Declare a variable called `myFriends`. Set it's value to an array containing the names of everyone in class.<br>
**b.** Declare a function called `greetMyFriends` with one parameter called `friendName`.<br>
**c.** Inside the function, write a `for` loop to iterate through the `myFriends` array. Your `return` value should ouput a message like: `"Aloha " + friendName + "!"` _\* Should output a string for each person._

**7. EVEN OR ODDS**

**a.** Declare a variable called `mixedNums`. Set it's value to an array containing even and odd numbers of your choice.<br>
**b.** Declare a function called `evenOrOdds` with one parameter called `checkNum`.<br>
**c.** Inside the function, write a `for` loop to iterate through the `mixedNums` array. If the number is even output `"What are the odds?!"`, otherwise output `"Not even brah!"`.

**8. WHERES WALDO**

**a.** Declare a variable called `nameList`. Set it's value to an array containing the following: ['Joker', 'Storm', 'Waldo', 'Wonder Woman', 'Beetlejuice']<br>
**b.** Declare a function called `wheresWaldo` with one parameter called `names`.<br>
**c.** Inside the function, write a `for` loop to iterate through the `nameList` array. You should output `"FOUND WALDO AT INDEX: " + i + "!! "`, otherwise output `"Waldo not found at index: " + i + ". "`.
