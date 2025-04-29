# cs314-laboratory-3-solved
**TO GET THIS SOLUTION VISIT:** [CS314 Laboratory 3 Solved](https://www.ankitcodinghub.com/product/cs314-laboratory-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114571&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS314  Laboratory 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Part I

Modify the Minix3 source code such that the string “PID &lt;pid&gt; swapped in” is printed, whenever a user-level process is brought in by the scheduler.

To do this, you will need to understand how the scheduler works. These pages https://minixnitc.github.io/scheduling.html , http://www.minix3.org/docs/scheduling/report.pdf give a good explanation. You have to look at the code in : minix/servers/sched and minix/kernel/proc.c .

Part II

You can test by using the UnixBench benchmark suite as instructed below:

1. Get the source code from ftp://ftp.iitdh.ac.in/opensource/tools/byte-unixbench-mod.zip and copy it to your home folder in the Minix3 VM.

(Note that this is a modified version of the suite. The original benchmarks were designed as “fixed duration” benchmarks: they each repeat a certain pattern over and over until a timer expires. The modification was done to make some of the benchmarks (namely, arith, fstime, pipe, spawn, syscall) as “fixed work”: they do a certain fixed amount of work, regardless of the time it takes to do that work.).

2. Run the command “gmake” to build the benchmarks in the Minix3 VM.

Submit: a single zip file (format: &lt;roll-number-1&gt;_&lt;roll-number-2&gt;_lab3.zip) with all modified source C files and a shell script. The shell script must copy the modified source files to the correct directories, and build the system. The evaluator will simply run the shell script, reboot the system, and check for the desired behavior. The zip must also contain a report of your study of the Unixbench suite.

Tip: print statements from the kernel and scheduler are also saved in /var/log/messages. Print statements from user programs can be simply redirected to a file for analysis.
