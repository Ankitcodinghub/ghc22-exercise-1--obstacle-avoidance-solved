# ghc22-exercise-1--obstacle-avoidance-solved
**TO GET THIS SOLUTION VISIT:** [GHC22 Exercise 1- Obstacle Avoidance Solved](https://www.ankitcodinghub.com/product/ghc22-exercise-1-obstacle-avoidance-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99209&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;GHC22 Exercise 1- Obstacle Avoidance Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Exercise 1: Obstacle Avoidance

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In Exercise 1, you learn how quadcopter determines its path around the obstacles in the scenario. The exercise consists of two steps: 1. Creating a scenario consisting of obstacles, and 2. Simulate a drone in the developed scenario in Step 1.

Step 0. Setup the environment

Before running the code for exercise 1, make sure to run the following command in the Command Window. This step adds the relevant folders to the path where the code for exercises is stored. This step also loads the model in the background for faster processing.

<pre>&gt;&gt; CatchingFire_Setup
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Step 1. Generate the scenario

This step is an interactive step where you will be using a MATLAB App to add locations for obstacles and waypoints in the scenario to be used in the later step. Run the following command to open the app

<pre>&gt;&gt; Exercise1_Step1
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>Add Trees – Click on this button first to add obstacles in the plot provided on the right. Click in the plot region in multiple places. The round circles will appear wherever you click to show the position of the obstacles. Make sure to add obstacles with some space between them to allow drone to move freely.</li>
<li>Add Waypoints – Click on this button next to add waypoints in the plot provided on the right. Click in the plot region in multiple places. The cross with the dashed line connecting to the waypoints will appear showing the path. The first waypoint will be treated as a initial position of the drone.</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>Reset the Scenario – This is an optional button to be used if you would like to reset the plot region. This allows you to restart adding obstacles and waypoints.</li>
<li>Create the Scenario – Once the locations of obstacles and waypoints are added to the plot region, the green button will be enabled. Click on this button to create a scenario, such as shown on the right above. This shows trees as the obstacle, red marks as the waypoint and blue as the initial position of the drone. The created</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
scenario will be used for Step 2.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="section">
<div class="layoutArea">
<div class="column">
You can close the app now by clicking on the ‘X’ on the top right corner. Observe the location of the developed scenario opened as a separate window in the MATLAB Online.

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Step 2. Simulate the drone path by following obstacle avoidance

This step uses Simulink model to simulate the drone (quadcopter in this case) path by utilizing an obstacle avoidance algorithm (3D Vector Field Histogram). Type the following command to open the model to run this step

<pre>&gt;&gt; Exercise1_Step2
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
The simulation (as shown in the right picture) will automatically pop-up and start once the Simulink model gets opened. The model consists of four main subsystems:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>Scenario Building – The scenario block configures the scenario and visualizes the obstacles, trajectory, and the lidar point cloud data.</li>
<li>Control Panel – The switch enables or disables the updates to the lookahead point from the Obstacle Avoidance block. The slider updates the lookahead distance used to compute the lookahead point.</li>
<li>Waypoint Following and Obstacle Avoidance – The Waypoint following, and obstacle avoidance subsystem finds</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
the obstacle-free desired position and the desired yaw according to the current UAV state and point cloud data.

• Controller and plant – The Controller and plant subsystem generates the control commands and updates the UAV state based on the lookahead point.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Step 3. Monitor and observe the results

Monitor the path of the drone through the obstacles and waypoints. The parameters can be updated:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>The top right corner of the Simulink model provides a control panel with a button to on and off the use of obstacle avoidance. You can use this to see how the path of the drone changes in the simulation in real-time. Are you able to see the updated path?</li>
<li>You can restart the exercise from step 1 and add more obstacles and change the waypoints. Follow the steps to</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
see how the drone’s path changes in the updated scenario.

• Once more time permits, you can review the code to update the parameters associated with drone and the sensor mounted on the drone to analyze the change in behavior.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Learn More

<ul>
<li>UAV Toolbox: mathworks/uav</li>
<li>UAV Obstacle Avoidance Documentation Example: mathworks/uav-obstacle-avoidance-in-simulink</li>
<li>Vector Field Histogram Algorithm: mathworks/controllervfh-system-object</li>
<li>Modeling and simulation: mathworks.com/discovery/modeling-and-simulation</li>
<li>Simulink and Simulink Online: mathworks.com/learn/tutorials/simulink-onramp</li>
<li>MATLAB App Designer: mathworks/app-designer</li>
</ul>
</div>
</div>
</div>
