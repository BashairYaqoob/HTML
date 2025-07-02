 <!--input only has opening tag--> 
 upper line is a comment

form: tags accepets forms... we need to make forms seperately.. can have ~input and button tag

input: is inside of form... it is a small dialogue box and it only has opening tag
-outside of input tag write the text that should appear
-inside input we have attributes:
 *type: like text/date etc
 
  @if type is RADIO:
      =it is like MCQs.. you have to mark them
      =it requires you to submit single input (with name attribute              inside input tag) 
      =ALL RADIO BUTTONS MUST HAVE SAME name ATTRIBUTE
        to make sure that if you select one option , the other deselects

   @if type is CHECKBOS:
   -you need to check a box
   -you can checck multiple boxes

*name:should be same if we need options/mcqs .. it helps in grouping purpose

*id: helps in locating different sections in html, css and js

*checked: attribute wd no value: checks the boxes at start 

~labels: nest inputs in these tags to make sure that a text marks the button
(if i am clicking on option 1's text, it is ticking the bullet)
 use attribute "for" in label and make sure that its same as id attribute

 *placeholder: grayish text that explains user what is to be entered as input
 *required: DOESNOT HAVE A VALUE.. user must enter input b4 submitting

~button: submits the input.. has both tags .. type="submit/button/reset"
-<br>: inserts line break
