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