## How to found the tests with different results?
I uses vimdiff command on terminal in order to visualize all differences.
![vimDiff](/lab5_wk10/vimDiff.png)
## A Link to the test-file with differet result
[test32](/lab5_wk10/32.md)
<br>
[test22](/lab5_wk10/22.md)

## The aboe images shows the markdown view for test22 and test32.
![test22](/lab5_wk10/test22.png)
![test32](/lab5_wk10/test32.png)

The lab9's implementation, the output for both test 32 and test 22 are [] and does not contain any links, thus the output is incorrect.

For our implementation, the output are [/bar\* "ti\*tle"] and [/f&ouml;&ouml; "f&ouml;&ouml;"] for test 22 and test 32 respectively, thus those are correct outputs.

The lab's output was incorrect because the parentheses checker is interupted by the extra space within the paren.

