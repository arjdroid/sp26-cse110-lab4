1. Line 9 prints `values added:  20`

2. Line 13 prints `final result:  20`

3. We should avoid using var because it does not have a block scope, but rather a function scope. So, it can cause variable name conflicts and scope issues.

4. Line 9 still prints `values added:  20`

5. Line 13 returns a `ReferenceError` since `result` does not have function scope and was scoped to the `if` block instead. So, there is no variable `result` defined for the scope of line 13.

6. Line 9 doesn't print anything since there's a `TypeError` at line 7 where we try to reassign `result`, it is a `const` so it can't be assigned to again.

7. For the same reason as above, line 13 doesn't print anything.