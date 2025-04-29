# cs39001-assignment-5-verilog-design-and-implementation-of-sequential-circuits-solved
**TO GET THIS SOLUTION VISIT:** [CS39001 Assignment-5 Verilog Design and Implementation of Sequential Circuits Solved](https://www.ankitcodinghub.com/product/cs39001-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114637&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39001 Assignment-5 Verilog Design and Implementation of Sequential Circuits Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Time allowed: 6 hours

INSTRUCTIONS: Make one submission per group in the form of a single zipped folder containing your Verilog source code files(s) and Verilog testbench(es). Name your submitted zipped folder as Assgn 5 Grp &lt;Group no&gt;.zip and (e.g. Assgn 5 Grp 25.zip). Inside each submitted source and testbench files, there should be a clear header describing the assignment no., problem no., semester, group no., and names of group members. Liberally comment your code to improve its comprehensibility.

Figure 1: A 4-bit LFSR circuit.

1. Linear Feedback Shift Register (LFSR) Design The objective is to design a synchronous sequential circuit using four D Flip-flops, which when loaded by an initial non-zero vector called seed, cycles through all the 15 non-zero binary combinations through its state transitions, before returning to the initial vector (the seed). Thus, this circuit can be used as a modulo-15 counter, although it does not count in exact binary sequence. The only combinational gates required are XORs. These sequential circuits are commonly termed as Linear Feedback Shift Registers (LFSRs), and have extensive use in digital circuit design and testing, communication theory, etc.

Design (using Verilog), simulate (using an appropriate Verilog testbench), and implement (on a FPGA platform supported by your CAD software tool), the 4-bit LFSR shown in Fig. 1. The four stages of the sequential circuit can be loaded by an arbitrary non-zero initialization seed by using the four multiplexers as shown in the diagram. In your testbench, verify that for an initialization seed 1111, the state transition sequence followed by this circuit is as follows: 1111 → 0111 → 0011 → 0001 → 1000 → 0100 → 0010

– 2 – CS39001

Figure 2: Sequential unsigned comparator schematic.

4. [Sequential Unsigned Comparator] Consider the task of designing a sequential circuit that can compare two unsigned integers A and B, each of which is 32-bit long. The block-level schematic is shown in Fig. 2, where in every clock cycle, the circuit serially reads one bit each of A and B from their MSB sides at its input ports a and b respectively, and performs state transition of an internal finite state machine (FSM). In every clock cycle, the contents of the registers containing A and B are left-shifted. The circuit has three output lines L, E and G, exactly one of which becomes logic-1 at the end of the session indicating the result. Thus, if A &lt; B, then {L,E,G} = 100; if A = B, then {L,E,G} = 010; if A &gt; B, then {L,E,G} = 001.

For simplicity, assume that the machine is in an initial all-zero (reset) state before the beginning of the session (the reset signal has not been shown in the above schematic), and the input control signal OP is at logic-0; as long as OP remains at logic-0, L = E = G = 0. At the end of the session (i.e., after the arrival of least significant bits), OP flips to logic-1, indicating the end of the operation, and that the values of L, E and G are now ready to be read.
