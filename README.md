<div align="center">

## Making Life Easier with Pseudo Code


</div>

### Description

The purpose of this article is to introduce you to the world of Pseudo Code and help you improve your development skills.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[D Davis](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/d-davis.md)
**Level**          |Beginner
**User Rating**    |4.9 (49 globes from 10 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) , VBA MS Access, VBA MS Excel
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/d-davis-making-life-easier-with-pseudo-code__1-52946/archive/master.zip)





### Source Code

<table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
 <tr>
 <td><font face="Arial, Helvetica, sans-serif" size="2"><b>Making Life Easier
  with Pseudo Code</b><br>
  By: Dustin Davis (Programmers-Unlimited.com)</font></td>
 </tr>
</table>
<br>
<table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
 <tr>
 <td bgcolor="#003366"><b><font face="Arial, Helvetica, sans-serif" size="2" color="#FFFFFF">Introduction</font></b></td>
 </tr>
 <tr>
 <td><font face="Arial, Helvetica, sans-serif" size="2">Pseudo Code is not
  a programming language in specific, but it is a language specific to your
  native tongue (English, Spanish, etc.). It is a type of "modeling"
  tool that will be a great friend to you in future projects. By using non
  code specific terms and phrases, applications written in Pseudo Code can
  easily be understood by multiple developers, and if written well enough,
  can be used to translate applications to different platforms and programming
  languages. This means a great deal to anyone who has experience in developing
  on a tight time table. <P>
  In basic terms, Pseudo Code is the english (or whatever) version of real code. Let's take a look at some Pseudo Code.</font></td>
 </tr>
</table>
<br>
<table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
 <tr>
 <td bgcolor="#003366"><b><font size="2" face="Arial, Helvetica, sans-serif" color="#FFFFFF">Getting
  Started</font></b></td>
 </tr>
 <tr>
 <td>
  <p><font face="Arial, Helvetica, sans-serif" size="2">Getting started is
  the hard part as it requires that you have an idea that has been thought
  out. A word of advice is that you should never wait until you have 100%
  of your project worked out. If you do, you will most likely never start.
  For this article, we will design a simple program to emulate a Pay Phone.</font></p>
  <p><font face="Arial, Helvetica, sans-serif" size="2">The first step we
  need to take is designing and overall general program flow. A Pay Phone
  is pretty easy to do as it does not have much to it. <br>
  <br>
  </font></p>
  <table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
  <tr>
   <td bgcolor="#CCCCCC">
   <ul>
    <li><font face="Times New Roman, Times, serif" size="2">Wait for
    user</font></li>
    <li><font face="Times New Roman, Times, serif" size="2">Take money</font></li>
    <li><font face="Times New Roman, Times, serif" size="2">Take input</font></li>
    <li><font face="Times New Roman, Times, serif" size="2">Make call</font></li>
   </ul>
   </td>
  </tr>
  </table>
  <p><font face="Arial, Helvetica, sans-serif" size="2">Pretty simple eh?
  Like I said, not much to a Pay Phone. So now we have an overall general
  view of what we need to do, let's get moving with the next step.<br>
  </font></p>
 </td>
 </tr>
</table>
<br>
<table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
 <tr>
 <td bgcolor="#003366"><b><font face="Arial, Helvetica, sans-serif" size="2" color="#FFFFFF">Breaking
  Down the Overall Process</font></b></td>
 </tr>
 <tr>
 <td><font face="Arial, Helvetica, sans-serif" size="2">The next thing to do
  is go back over the overall general view that we created. We will take each
  step and break it down into working Pseudo Code.<br>
  <br>
  <u>"Wait for user"</u><br>
  This process could contain anything depending on the phone. Most phones
  are just dead, but some of the newer phone have LCD's that display all sorts
  of things. In this example, let's just make it simple<br>
  <br>
  </font>
  <table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
  <tr>
   <td bgcolor="#CCCCCC">
   <p><font size="2" face="Times New Roman, Times, serif">Function "Wait
    for user"</font></p>
   <blockquote>
    <p><font size="2" face="Times New Roman, Times, serif">Get Time<br>
    Display Time On LCD<br>
    <br>
    Check For Input</font></p>
    <blockquote>
    <p><font size="2" face="Times New Roman, Times, serif"><i>If coins
     are inserted, call "Take money"<br>
     If buttons are pushed, call "Take input"</i></font></p>
    </blockquote>
   </blockquote>
   <p><font size="2" face="Times New Roman, Times, serif">End Function
    "Wait for user"</font></p>
   </td>
  </tr>
  </table>
  <p><font face="Arial, Helvetica, sans-serif" size="2"><br>
  wow, that's it?! Pretty much. Obviously, anyone who has ever worked with
  LCD's will know there are more steps involved in displaying the time on
  the screen, but that's the good part, and we will get to that later. </font></p>
  <p><font face="Arial, Helvetica, sans-serif" size="2">On the first line,
  we define a function. Anyone who reads this will be able to tell that
  the following will be inside of the "Wait for user" function.
  On the following line, you will see "Get Time". This tells the
  reader that the code for getting the time will go in that spot, before
  "Display Time On LCD". We continue writing the parts of the
  function that it will contain. Notice that it's easy to read compared
  to code? This is the power of Pseudo Code.</font></p>
  <p><font face="Arial, Helvetica, sans-serif" size="2">Using Pseudo Code,
  we have just created a template for our "Wait for user" function.
  This template will allow anyone to come back to it and fill it in with
  code of their choice. </font></p>
  <p><font face="Arial, Helvetica, sans-serif" size="2"><u>"Take money"</u>
  , <u>"Take input"</u><br>
  Every Pay Phone has to take money and input. The functions are (in a general
  breakdown) very simple. <br>
  </font></p>
  <table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
  <tr>
   <td bgcolor="#CCCCCC">
   <p><font face="Times New Roman, Times, serif" size="2">Function "Take
    money"</font></p>
   <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2">Wait For
    Coin Insert<br>
    </font></p>
    <p><font face="Times New Roman, Times, serif" size="2">Identify
    Coin</font></p>
    <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2"><i>If coin
     is invalid, return to change drop<br>
     otherwise, increase users balance</i></font></p>
    </blockquote>
   </blockquote>
   <p><font face="Times New Roman, Times, serif" size="2">End Function
    "Take money"</font></p>
   <p><font face="Times New Roman, Times, serif" size="2">Function "Take
    input"</font></p>
   <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2">Identify
    Button Pushed</font></p>
    <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2"><i>If invalid
     button (#,*) then return money and disconnect call<br>
     If valid button, add digit to the phone number</i></font></p>
    </blockquote>
    <p><font face="Times New Roman, Times, serif" size="2">Check For
    a Valid Number</font></p>
    <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2"><i>If a
     valid number has been input, call "Make call"<br>
     Otherwise, return change and disconnect call</i></font></p>
    </blockquote>
   </blockquote>
   <p><font face="Times New Roman, Times, serif" size="2">End Function
    "Take input"</font></p>
   </td>
  </tr>
  </table>
  <p><font face="Arial, Helvetica, sans-serif" size="2">These functions are
  pretty simple and are no different from our "Wait for user"
  function. These functions are simply templates for later code insertion.</font></p>
  <p><font face="Arial, Helvetica, sans-serif" size="2"><u>"Make call"</u><br>
  Our make call function will be a little bigger than the previous functions,
  let's dig in...</font></p>
  <table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
  <tr>
   <td bgcolor="#CCCCCC">
   <p><font face="Times New Roman, Times, serif" size="2">Function "Make
    call"<br>
    </font></p>
   <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2">Get Cost
    of Call</font></p>
    <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2"><i>If user
     has not inserted enough coins, tell them to insert the remaining
     balance, Call "Take money"</i></font></p>
    </blockquote>
    <p><font face="Times New Roman, Times, serif" size="2">Dial Number</font></p>
    <p><font face="Times New Roman, Times, serif" size="2">Wait For
    Connection</font></p>
    <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2"><i>If busy,
     return change to coin drop<br>
     otherwise, store coins in bank</i></font></p>
    </blockquote>
    <p><font face="Times New Roman, Times, serif" size="2">Wait For
    Disconnect</font></p>
    <blockquote>
    <p><font face="Times New Roman, Times, serif" size="2"><i>On disconnect,
     call "Wait for user"</i></font></p>
    </blockquote>
   </blockquote>
   <p><font face="Times New Roman, Times, serif" size="2">End Function
    "Make call"</font></p>
   </td>
  </tr>
  </table>
  <p><font face="Arial, Helvetica, sans-serif" size="2">I just want to clarify
  that I am no phone technician and I know that there are many many more
  operations to a Pay Phone, but this is what we have for this article.
  Let's move on to the next section.</font></p>
 </td>
 </tr>
</table>
<br>
<table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
 <tr>
 <td bgcolor="#003366"><b><font size="2" face="Arial, Helvetica, sans-serif" color="#FFFFFF">Further
  Breakdown</font></b></td>
 </tr>
 <tr>
 <td>
  <p><font face="Arial, Helvetica, sans-serif" size="2">Now that you understand
  that Pseudo Code is crazy simple, let's get into some specifics. We will
  go back to our "Wait for user" function. We are going to modify
  it so that when you assign it to your programmer, he will understand exactly
  what you want.</font></p>
  <table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
  <tr>
   <td bgcolor="#CCCCCC">
   <p><font size="2" face="Times New Roman, Times, serif">Function "Wait
    for user"</font></p>
   <blockquote>
    <p><font size="2" face="Times New Roman, Times, serif">(start loop)<br>
    Get Time<br>
    Display Time On LCD<br>
     - Scroll time from left to right<br>
     - Format: HH:MM AM/PM<br>
    <br>
    Check For Input<br>
     - Check coin drop for coin insert<br>
     - Check keypad buffer for button push</font></p>
    <blockquote>
    <p><font size="2" face="Times New Roman, Times, serif"><i>If coins
     are inserted, call "Take money"<br>
     If buttons are pushed, call "Take input"</i></font></p>
    </blockquote>
    <p><font face="Times New Roman, Times, serif" size="2">(end loop)</font></p>
   </blockquote>
   <p><font size="2" face="Times New Roman, Times, serif">End Function
    "Wait for user"</font></p>
   </td>
  </tr>
  </table>
  <p><font face="Arial, Helvetica, sans-serif" size="2">You think I'm a crazy person
   who's toying with you now, don't ya?! I'm serious, this is how easy Pseudo
  Code can be. You can modify your Pseudo code to look as you like, just
  keep in mind the readability for others (if any at all). </font></p>
 </td>
 </tr>
</table>
<br>
<table width="90%" border="0" cellspacing="0" cellpadding="0" align="center">
 <tr>
 <td bgcolor="#003366"><b><font size="2" face="Arial, Helvetica, sans-serif" color="#FFFFFF">Conclusion</font></b></td>
 </tr>
 <tr>
 <td>
  <p><font face="Arial, Helvetica, sans-serif" size="2">The power of Pseudo
  Code can be from 0 to unlimited. It all depends on you and your methods.
  Pseudo Code can scale the ease of transition from Pseudo Code to Real
  Code depending on how you use it. If you use more programming language
  specific articles, you will have an easier time porting it into real code.
  In most cases, Pseudo Code can be directly replaced with code with little
  to no extra thinking. <br>
  <br>
  I hope this article has been helpful and I hope it helps you to write
  better code. By using Pseudo Code, it can help see issues that would normally
  not be seen by looking at real code since you are reading it in your native
  tongue.<br>
  <br>
  Check out more articles like this on <b>Programmers-Unlimited.com</b>.</font></p>
 </td>
 </tr>
</table>

