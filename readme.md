Instructions
---
The html files are named ***exercise-1.html*** and ***excercise-2.html***

Question
----
* Explain why the result of `('b' + 'a' + + 'a' + 'a').toLowerCase()` is `banana`.

- The result is banana because `b+a = a` , `+ + 'a' = NaN`, and last is + `'a'` which the actual result is baNaNa but converted to lowercase which the final result is `banana`