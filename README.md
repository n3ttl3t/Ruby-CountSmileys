# Count Smileys

## Given an array (arr) as an argument the function CountSmileys returns the total number of smiling faces.

Rules for a smiling face:
- Each smiley face must contain a valid pair of eyes. Eyes can be marked as : or ;
- A smiley face can have a nose but it does not have to. Valid characters for a nose are - or ~
- Every smiling face must have a smiling mouth that should be marked with either ) or D.

No additional characters are allowed except for those mentioned.

Valid smiley face examples:
```
:) :D ;-D :~)
```
Invalid smiley faces:
```
;( :> :} :]
```

## Acceptance Criteria
Input | Output
--- | ---
countSmileys([':)', ';(', ';}', ':-D']); | 2;
countSmileys([';D', ':-(', ':-)', ';~)']); | 3;
countSmileys([';]', ':[', ';*', ':$', ';-D']); | 1;
