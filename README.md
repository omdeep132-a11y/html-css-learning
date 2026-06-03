display property 

display : none

to remove element frm page completely

visibility : none

element  will be not visible but it will be in same place 

display: inline 

to fit block tags in single colum but can't manipulate top and botton margin padding 

display:block 

to allow inline tag to capture whole colum 

display inline 

can manipulate height width margin ppadding using this property 



relative units

% 
adepts  parent tags size as per %

em 
1 em = same size as parent 2  em means double size of parent tag 

rem 
1rem = same size as root element 2 rem means double size of root elemenr root element is html inmost cases

vh view port height
full screen of browser 1vh = 1% of browsers screen size 


positions 

static 
default position of tag doesnt allow any margin % padding 

relative 
allow  %  margin padding (simgle divv box  normal)
relative to itself

abseloute 
breaks the document flow  (can over lap with other boxes becouse its out of document flow )and it directly follows parent element acording to instruction 
if top is 1 it will stick to parents elements top 

fixed 
stick to any part of browser even while scrolling it will be fixed in one side of screen according to instruction 
if top is 0 then it stick to top of screen even whiile scrolling it will be visible

sticky 
get fixed onces it reach the place given in instruction 




background-size 
certtin 
tries to fit the img at least onces if space is remanning repeat the img until space is fullie filled 
cover 
fit img one time only but tries to fit completely 
auto '
default fit real img px to space given to div 


imp topic flex box 

flex container propertys 

align-items:center,end,start;
use to align items vartically 

justify-content:end,start,center,sace-between,space-around,space-evenly;
use to align items horizontelly 

flex-direction :
column: use to set items in column 
column-reverse: use to reverse boxes in column 

row:oppsite to column
row-reverse :opp to column-reverse

flex-wrap:
no-wrap ,wrap,none

align-cotent:Aligns multiple rows/columns when wrapping occurs.
stretch
flex-start
flex-end
center
space-between
space-around
space-evenly

flex items propertys (it has higher priority then container property )

order to shift boxes or change places of boxes according to 
flex-grow : iteem to which this property is apllied occupis extra space in container 
flex-shrink : default is 1 if set 2 then that item will srink in double then other items 
align-self:allows  signel item to align  seprately frm containers functions


