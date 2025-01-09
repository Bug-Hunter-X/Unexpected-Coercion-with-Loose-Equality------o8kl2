# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (`==`) and its unexpected behavior when dealing with `null` values.  Loose equality can lead to type coercion, which might not always produce the intended result, making the code error-prone.  The provided solution showcases how to use strict equality (`===`) to prevent such issues and write more robust code.

## Bug Description
The original code uses loose equality (`==`) to compare values with `null`. This can lead to incorrect results due to JavaScript's type coercion mechanisms.  For example, `0 == null` evaluates to `false`, but `0 == 0` is `true`. This inconsistency can lead to logic errors. The solution below demonstrates how to improve the code by employing strict equality (`===`) for a more reliable and error-free approach.