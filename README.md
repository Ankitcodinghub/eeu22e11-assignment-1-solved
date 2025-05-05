# eeu22e11-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [EEU22E11 Assignment 1 Solved](https://www.ankitcodinghub.com/product/eeu22e11-assignment-1/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99806&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEU22E11&nbsp;Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;Assignment 1

This assignment requires you to use the solution for the parachutist ODE you examined in class, to analyse the Red Bull Scientific data. The template code for this assignment

is redbull_lab_template. Submit your Matlab code to the blackboard site. YOU MUST USE THE NAMING CONVEN- TION GroupNumber_LastName_FirstName.m for the name of the file when you submit. Failure to do so may result in no marks for this submission. This assignment counts for 5% of your final mark.

The Red Bull Stratos Jump Team have recorded their sci- entific data online here. The key data recording the velocity of Mr. B. wrt time is in the CSV1 file RedBullJumpData.csv which you can download from blackboard. the lines of code below show you how to read from a CSV file in Matlab.

<pre>jumpdata = csvread(’RedBullJumpData.csv’);
t_redbull = jumpdata(:,1);
v_redbull = jumpdata(:,2);
terminal_velocity = jumpdata(:,3);
N_timestamps = length(t_redbull);
</pre>
Note that the third column in the file is the measured termi- nal velocity profile of the falling object. It was reported by the team but is not clearly defined. You will not need it to answer the questions below. However, you can explore whether the in- formation that column implies may be useful in answering the last question.

As you will see, the fall is initially unhindered by drag. Then as the atmosphere causes drag, the acceleration changes and eventually Mr. B. reaches terminal velocity. Our idealised solu- tion does not take into account the change of drag with time and so it is likely to be quite a poor model of what happens to Mr. B. as he falls.

Your single submitted Matlab script should address every one of the questions below. The answer to each part should be stored in the variable name as specified. UNLESS OTH- ERWISE STATED, ALL LINES IN PLOTS SHOULD USE A

</div>
<div class="column">
1 A CSV file is a Comma Separated Value file

t_redbull is a vector containing the timestamps at which the velocities

in v_redbull were measured. The number of instants at which the time and velocity pairs were measured is N_timestamps.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
LINEWIDTH OF 2.0. PLEASE USE THE TEMPLATE CODE PROVIDED.

1. Plot the measured values of velocity versus time from the JumpData.CSV file. Put your line into a plot handle called h_part1 using h_part1 = plot(….) as usual. Use the color red for the line. Mark each point on your line with

a red × mark. Render this plot as Figure 1. Fix your axes to a time duration of 180 secs and a maximum velocity of 400m/s2. Label the axes appropriately, show the grid and also adjust the fontsize of the axis labels to be 24.

2. Superimpose on that plot another line (in dashed blue), which shows the velocity versus time for an object in freefall without the effect of drag. Put that line into a plot han-

dle called h_part2. Note that this implies that accelera- tion is constant and so v(t) = at, where acceleration is in m/s2 and a = g. Assign your freefall velocity to a variable v_freefall at the same time instants as t_redbull.

3. Estimate the time at which Mr. B. starts to enter the at- mosphere. Do this either by using the plot in Figure 1 (i.e. by graphical/manual estimation) or otherwise. You may as- sume that when the actual measured velocity deviates from idealised freefall by &gt;= 5% then he has entered the atmo- sphere. Print out to the command line a report of this value i.e. Mr. B. enters the earth’s atmosphere at X secs after he jumps. Assign that value to the variable hit_instant.

4. Assume that the velocity of Felix as he falls is modelled by the first order differential equation that we used in the previous laboratory. Starting from the initial conditions at t = 56 secs use your numerical solution code from the previous laboratory to generate an estimate of the velocity of Mr B after that time i.e. up to 180 secs. Assume initial conditions are as measured in the file. Use c/m = 3/60. Superimpose the resulting numerical solution of velocity versus time on your plot in Figure 1 using a dashed green line. Assign that line to the plot handle h_part4. Assign your velocity vector to the variable v_numerical_1.

</div>
<div class="column">
Note that you should use the same timesteps as in the JumpData file. That means instead of a constant times interval between each point in your Euler solution you will have to change the time interval in line with the size in the recorded file.

</div>
</div>
<div class="layoutArea">
<div class="column">
evaluating the error in a mathematical model 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
5. Calculate the percentage error between your numerical so- lution and the actual measured value of velocity of Mr. B at 64 and 170 secs. Your code must also print this out on the command line using the text as follows. The Percent- age error at 64 and 170 secs is X and Y respectively. Assign your percentage error measurements to a 2 element vector per_error.

6. As you can see the model we have used in lectures is unable to capture what actually happens. We can achieve some idea of the change in c/m by using our idealised model over small intervals in time. In other words, we can try to use

a number of different, simple models at different points in time, to model the behaviour of Mr. B. Starting from t = 64 secs, find a value of c/m which yields a velocity at t = 69 secs in your numerical solution that is within ±0.3%

of the measured velocity. Assume initial conditions are as measured at t = 64secs. Hint : try values between 2/60 and 5/60 in steps of 1/60. Superimpose this new velocity solution on your existing plot using a dashed line coloured black. Assign that velocity vector to the variable h_part6. Report your measured error at t = 69 using The error at t = 69 secs using my estimated drag information is X.. Assign that error to the variable est_error.

</div>
</div>
<div class="layoutArea">
<div class="column">
evaluating the error in a mathematical model 3

</div>
</div>
<div class="layoutArea">
<div class="column">
400

300

200

100

0

0 50 100 150

Time (secs)

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Your final plot should look something like this.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Velocity m/s

</div>
</div>
</div>
</div>
