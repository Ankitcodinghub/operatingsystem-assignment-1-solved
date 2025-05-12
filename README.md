# operatingsystem-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [OperatingSystem Assignment 1 Solved](https://www.ankitcodinghub.com/product/operatingsystem-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91417&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;OperatingSystem Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Assignment 1

1 Process creation and termination system calls .

The first exercise deals using process creation system call, fork(). You need to write a program that spawns a child process, using the fork() system call. The child process reads a CSV file, presented with the assignment, that has (fake) student IDs and grades of various assignments. This child process computes the average score of each assignment across students of section ‘A’, and thereafter prints the details of these assignments (of section ‘A’, i.e.). The parent process does the same operation, on the same CSV file but for assignments given to students of section ‘B’.

The parent process must wait for the child process to terminate, by using the system call waitpid(). The child process must call the exit() system callonce its execution ends.

Now create a separate program which repeats exactly the same steps as above, but uses threads using pthread create() and pthread join(). For the program that uses threads, once the averages are computed, also compute the average score of each assignment across the sections by reusing the result obtained by the two threads.

You would require to refer to the manpages for various system calls men- tioned.

Note: You are expected to use read and read system calls, to read and write to the file.

What To Submit

<ul>
<li>Program source code with Makefile to compile and pause the compilation at each phase.</li>
<li>Write-up giving a brief description of how the program works (less than 1 page), with details of each system call, the arguments passed and the expected outcomes and how you handled error/corner cases.
1
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Grading Rubric

<ul>
<li>Successful compilation of the program via the Makefile – 10 points.</li>
<li>Correct output for the program, corresponding to each of the sections –
30 points.
</li>
<li>Correct use the system calls mentioned with proper arguments and error handling – 20 points.</li>
<li>Descriptive write-up (no more than 1 page) – 5 points.

2 Combining C and Assembly Language Pro-

grams (Total points:35)

This second exercise is aimed to serve two objectives – writing assembly lan- guage programs and secondly to help combine a C program with and assembly language function. You need to do the following:
</li>
</ul>
<ol>
<li>Write a program with three functions A(), B() and C().</li>
<li>A() should call B() passing a 64-bit integer as an argument.</li>
<li>B() should interpret that as a 8-byte ASCII string and print individual characters on screen. You need to call the write() system call from assembly language using the syscall instruction, passing appropriate ar- guments.</li>
<li>Modify the stack in the function B() in such a way that when B() executes the ret instruction, it jumps to a third function C(). C() must also be written in C. This MUST happen without an explicit call to function C(). A mere ret from B, should pass the control to function C() instead of A(). Finally, the function C() needs to terminate the program by using the exit() system call.</li>
<li>You ofcourse also need a main() function from where the program starts. The C file with the main() function could also have the function A() (i.e., main() could call A()).</li>
<li>The functions A(), B() and C() need to be in three different files. You may use printf() or write() functions to display which function you are in.</li>
</ol>
What To Submit

<ul>
<li>Program source code with Makefile the compile the program and generate a single binary executable.</li>
<li>README/Write-up describing the following:

– Steps to compile and execute the program.

– Description of the logic used for achieving the above (no more than one page).

2
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Grading Rubric

<ul>
<li>Successful compilation of the programs using the Makefile — 5 points.</li>
<li>Correct output for the program — 20 points.</li>
<li>Description of how the program works, viz. how A() calls B() and how upon return (ret) from B(), the control passes to the function C() — 10 points</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
