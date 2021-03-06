# Emo
Programming is a very emotional process. Therefore there is a need for a language that allows us to express our emotions _within_ the code. Emo fills this need.

# Usage
`python emo_interpreter.py example.emo`

# Example
```Emo
:X  This is a comment
:X  Best practice is to put two spaces between the comment
:X  indicator and the content of a comment
:X  This is the same with all operators


:X  Strings, ints, and floats are what you'd expect

"Hello"             :X  Strings
-25                 :X  Ints
3.14                :X  Floats


:X Print statement is tongue-sticking-out-face

:P "This prints with a newline"
:p "This prints without a newline"


:X  Arithmetic Operators

:P  4  +_+  3               :X  Addition
:P  4  -_-  3               :X  Subtraction
:P  4  *_*  3               :X  Multiplication
:P  4  ^_^  3               :X  Exponentiation
:P  4  %_%  3               :X  Modulo
:P  4  :\/  3               :X  Derpy Division (uses integer division)


:X  Comparison operators

:P  4  <_<  3               :X  Less than
:P  4  >_>  3               :X  Greater than
:P  4  =_=  3               :X  Equality
:P  4  >_<  3               :X  Inequality


:X  Variable names consist of eyes, a nose, and a mouth consisting of one letter
:X  Assignment operator is beaver face

:-y  :=  5
:P  :-y                     :X  -> 5


:X  Arrays are declared with square-smiley delimiters and 
:X  crying-small-face separators
:X  They are accessed with square-smileys

:-o  :=  [:  'first'  ,_,  'second'  ,_,  'third'  :]

:P  :-o  [:  1  :]          :X  -> 'second' 
:-o  [: 1 :] := 'newval'
:P  :-o                     :X  ->  ['first', 'newval', 'third']

:X  Associative arrays are declared with curly-smiley delimiters,
:X  crying-small-face separators, and use very-happy-smileys to
:X  relate keys and values. They are accessed with square-smileys
:-n  :=  {:
    'key1'  =>  'val1'  ,_,
    'key2'  =>  'val2'  ,_,
    'key3'  =>  'val2'
:}

:P  :-n  [:  'key1'  :]     :X  ->  'val1'

:X  Control statements
:X  Indentation is significant

(?_?)  :-y  <_<  0          :X  If
    :P  "Negative"
(!_?)  :-y  >_>  0          :X  Else if
    :P  "Positive"
(!_!)                       :X  Else
    :P  "Zero"


(@_@)  :-o                  :X  For loop
    :P  :-i                 :X  :-i is the implicit index variable



:X  Exceptions

( -_-)                      :X  Try
    :P  "Trying operation"
    \(>o<)/  "Badness!"     :X  Throw exception
( O_O)                      :X  Catch
    :P  "Caught an exception"    
(;-_-)                      :X  Finally
    :P  "Cleaning up"    

:X  Functions are declared with a kissy-face,
:X  the name of the function, and then a round-smiley
:X  list of arguments
:X  The 'for-you' gesture returns from the function

:X Add function
( ')3  :-a  (:  :-x  ,_,  :-y  :)
    (>")>  :-x  +_+  :-y

:p  "Sum of 5 and 6: "
:P  :-a  (:  5  ,_,  6  :)


:X  Boolean literals are happy face and sad face
:-)                         :X  true
:-(                         :X  false

:X  Boolean operators
:P  :-)  :&  :-(            :X  and
:P  :-)  :|  :-(            :X  or
:P  :!  :-(                 :X  not

:X  Generate a random value between 0.0 and 1.0
:X  with the waffle operator
:P  (#)

```