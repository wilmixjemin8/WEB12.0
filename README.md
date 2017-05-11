# WEB12.0
==========
 
WEB12.0
======

WEB12.0    is  about  C@  and  ARROW#  Programming Languages.


WEB12.0 is  about   C@ and  Arrow#  with  15  modules...

which  will be mentioned   only  in the  turorial , not here.


C@
===

UNIT-1: Introduction   to  C@ Programming   and  Advantages  of  C@ and  How  C@  is  used  with WXML
=======================================================================

C@  is  invented   by  wilmix  jemin  j   at  year  2015  at  Jdollar(JWEB)  Technology

and  it   is  focused  for  remotewebapplication  using  mobiles.

ADVANTAGES
==========

C@  is  mostly  used   for  mathematical statistics ...

C@  is mostly  used  for  other   project.


C@-TYPE-1
========


SYNTAX:
======



<C@>
<Convert>
<Logic>
public  class  <CLASSNAME>

{

public void  C@-Main( )

{
<!  C@  logic !>

}


}
</Logic>
</C@>


Program-1: C@  to   Print  the mathematical  statistics   using  C@  ....

<C@>
<Convert>
<Logic>
public  class  first

{

public void  C@-Main( )

{

<AList>  ar2= <NEW>  <AList> ();
ar2.add(1);
ar2.add(2);
ar2.add(3);
ar2.add(4);

//  add  1,2,3,4  to  arraylist and print  it  in form  with   table   format  using  WXML Parser


WXML.wxml<PARSE>r("ortable.wxml", 5," ","",ar2);

}


}
</Logic>
</C@>





WXML  Form   code  for  C@
==================

<!DOCTYPE WXML [

<!ELEMENT WXML (OR)*>


<!ELEMENT OR EMPTY>

<!ATTLIST OR

CNAME CDATA  #IMPLIED
DATE CDATA  #IMPLIED

ROWS CDATA  #IMPLIED
COLS CDATA  #IMPLIED
COLOR  CDATA  #IMPLIED


COLVALS  CDATA  #IMPLIED

ROWVALS CDATA  #IMPLIED
CELLSPACING  CDATA  #IMPLIED
CELLPADDING  CDATA  #IMPLIED
ADDRESS CDATA  #IMPLIED

>

]>

<WXML>






 <OR CNAME= 'EARE MACHINES'  DATE='12-12-2015'  ROWS='1' COLS='1'  COLOR='GREEN' COLSVALS='a,a1,a2,a3,a4'  ROWVALS='a' CELLSPACING='5'  CELLPADDING='7'    ADDRESS='EUROPE '   />


</WXML>


Note:   You can  refer   Arrow #  for  WXML  description.

What  is   the  Advantage  of  WXML?

1)  WXML  is   userfriendly  it   tells   the  developers  to  write  a  short  code
instead  of   writing  more  code  with  html.  That  is  olden  methods
of  writing  lenghtly  code using html.

2)  WXML  is  simillar  to   xml   ,  WXML  is  used  to  display   Forms,Report,etc.
but  xml  is  used  only for  datatransport.
=========================================================================================



ASHARP(ARROW#)
=============



UNIT-1: Introduction   to Arrow# Programming with  syntax-type-1 and syntax-type2  and  Advantages  of  Arrow# and  How  Arrow#  is  used  with WXML
=================================================================================


 ASHARP  is  invented   by  wilmix  jemin  j   at  year  2015  at  Jdollar(JWEB)  Technology

and  it   is  focused  for  remotewebapplication  using  mobiles.


ADVANTAGES
==========

Arrow#  is  mostly  used   for  mathematical statistics ...

Arrow#  is mostly  used  for  manufacturing  domain.


SYNTAX-TYPE-1:
===========


<Asharp>

<Convert>

<main>

<! C logic  !>

</main>

</Asharp>




Example  for  ASHARP-TYPE-1
==================

//  Example   to  print  wilmix jemin with  pet  Dog ...

<Asharp>

<Convert>

<main>

void  main()
{

int  i;

for (i=0;i<=12;i++)
{

printf("wilmix jemin dogg");
}



}

</main>

</Asharp>






SYNTAX-TYPE-2:
=============

<A#>

<Convert>

<Logic>
public class  <CLASSNAME>

{

public void  A#-Main( )
{
<! ASHARP  LOGIC!>

}

}



</Logic>
</A#>



EXAMPLE-2:
==========




<A#>

<Convert>

<Logic>
public class  output1

{

public void  A#-Main( )
{
<AList>  ar2= <NEW> <AList>();
ar2.add(1);
ar2.add(2);
ar2.add(3);
ar2.add(4);

//  add  1,2,3,4  values  to  arraylist

ASHARP.out.println("<html> <body bgcolor=blue>");
WXML.wxml<PARSE>r("ortable.wxml", 5,"gold ","1000 rs only",ar2);
//  WXML.wwxml  to  load   ortable.wxml  contents  and  display  the  table  in gold  with  1000 rsonly
 
ASHARP.out.println("</html>");
}

}



</Logic>
</A#>



ortable.wxml
===========

<!DOCTYPE WXML [

<!ELEMENT WXML (OR)*>


<!ELEMENT OR EMPTY>

<!ATTLIST OR

// declare   it  

CNAME CDATA  #IMPLIED
DATE CDATA  #IMPLIED

ROWS CDATA  #IMPLIED
COLS CDATA  #IMPLIED
COLOR  CDATA  #IMPLIED


COLVALS  CDATA  #IMPLIED

ROWVALS CDATA  #IMPLIED
CELLSPACING  CDATA  #IMPLIED
CELLPADDING  CDATA  #IMPLIED
ADDRESS CDATA  #IMPLIED

>

]>

<WXML>




// Title  name  SAR MACHINS

// column  values  a,a1,a2,a3,a4

//  Address   newyork


 <OR CNAME= 'SAR MACHINES'  DATE='12-12-2014'  ROWS='1' COLS='1'  COLOR='yellow' COLSVALS='a,a1,a2,a3,a4'  ROWVALS='a' CELLSPACING='5'  CELLPADDING='7'    ADDRESS='NEWYWORK'   />

//note  this   will   draw  a  form   with   table....

</WXML>

</WXML>





=========================================================================================




