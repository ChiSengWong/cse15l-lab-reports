## Snippet1
![snip1](lab4_wk8/snip1.png)
## Snippet2
![snip2](lab4_wk8/snip2.png)
## Snippet3
![snip3](lab4_wk8/snip3.png)

## TestCase
![testCase](lab4_wk8/testCase.png)

## Our test result
![self_result](lab4_wk8/self_result.png)

## Other group's test result
![luke_result](lab4_wk8/luke_result.png)

In our implementation, we passed two test, which is snippet1 and snippet3, but we failed at snippet2.

In the other group's implementation, all three tests failed.

In snippet1, the function ignored all backticks by searching only for openBracket-closeBracket pairs, then openParen-closeParen pairs, and get whatever within the two paren as link.

In snippet3, the function also searhcing only for desired pairs, thus newline characters does not affect its output. For extra characters at the end, the function ignore extra text if one of the pair is not found.