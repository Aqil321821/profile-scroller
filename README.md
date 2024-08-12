# profile-scroller
 a profile scroller , implementing of iterators 

 https://profile-scroll.netlify.app/



Generator Function (createPeopleIterator):

Ye function ek generator hai jo infinite loop ke zariye profiles ko sequentially yield karta hai.
index variable profile array ke index ko track karta hai. index++ % people.length se index circularly increment hota hai, yani array ke end pe pahunchne ke baad phir se start hota hai.


createPeopleIterator() ko call karne se ek iterator object create hota hai jo next() method provide karta hai.


If the number you're dividing (dividend) is less than the number you're dividing by (divisor), the result of the division is 0, and the entire dividend is the remainder.

When the dividend is less than the divisor, the remainder is always the dividend. This is because you can't complete a single division step, so all of the dividend remains.


3 % 4 is 3 because 3 is less than 4, matlab aesi surat me reminder 3 hoga....


Iteration 1: Index 0 → Jamie Williams
Iteration 2: Index 1 → John Smith
Iteration 3: Index 2 → Bob Johnson
Iteration 4: Index 3 → Shannon Jackson
Iteration 5: Index 0 → Jamie Williams (cycle repeats)



nextBtn.click();
 command button ke click event listener ko programmatically trigger karta hai.
