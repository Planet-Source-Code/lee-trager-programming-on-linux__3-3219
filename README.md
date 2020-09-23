<div align="center">

## Programming on Linux


</div>

### Description

This will show you how to code in Linux using g++.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Lee Trager](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/lee-trager.md)
**Level**          |Advanced
**User Rating**    |3.8 (23 globes from 6 users)
**Compatibility**  |C, C\+\+ \(general\), UNIX C\+\+
**Category**       |[Debugging and Error Handling](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/debugging-and-error-handling__3-6.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/lee-trager-programming-on-linux__3-3219/archive/master.zip)





### Source Code

Not many people are using Linux right now, or even programming in it. But its pretty easy. You hear alot about gcc, but thats just for C if you want use C++ in your programs you need to use g++. Some versions of Linux don't have all the header and libary files, like Mandrake. But these are the advanced files like OpenGL and OpenAL. For these files search for them on sites like www.linux.com, www.OpenGL.org, and/or the site of the people who make your version of Linux.<br><br>
First what you have to do it open a text or code editor(what ever comes with your version of linux. Something like vi or Advanced Editor. If your using an editor make sure it is set to C++. Now code as your normaly do. You will find some diffrences like when a program closes in win(in console) is says "Press any key to countinue..." in linux this dose not happen, so... You have to use a dummy so a program like hello world wont just pop up then close.<Br><br>
A simpal hello world program is something like this.<br><br>
<font color=black>
<font color=blue>#include</font> <font color=green> < iostream.h ></font><br>
<font color=blue>int</font> main(<font color=blue>void</font>)<br>
{<br>
<font color=blue>char</font> dummy[2];<br>
cout << "hi\n";<br>
cin >> dummy;<br>
<font color=blue>return</font> (0);<br>
}
<font color=red><b>YOU SHOULD HAVE A SPACE AT THE END OR IT GIVES YOU A WARNING</b></font>
</font>
<br><br>
Now that you have coded something you have to save it. Make sure it is saved as a cpp file it is important. Save it some were that you know like your user dir. Go into Terminal or Konsole(what ever your version calls it) and type these commands.
<br>
<font color=green>cd <i>the directory of the file</i></font>
<br><br>
If you want to see the files in that dir type <font color=green>ls</font>
<br><br>
<font color=green>g++ hello.cpp <i>filename.cpp</i> -o hello <i>were you want the exe to save</i></font>
<br><br>
That will compile your code if there are any errors or warnings g++ will tell you about them. Now goto that dir that it compiled in and click on it. If it dose not open up right click on it and check "Run in terminal".
<br><br>
Please Write comments

