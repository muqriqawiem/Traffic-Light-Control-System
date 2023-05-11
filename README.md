<h1>Traffic Light Control System (MCU 8051 IDE)</h1>

<h2>Operation Explanation</h2>
<img src=""></img>

<h3>Step 1 : Initial phase</h3>
<ul>
    <li>All traffic lights remain red for 4 seconds.</li>
    <li>No vehicles are allowed to cross the junction.</li>
</ul>

<h3>Step 2: Top Traffic Light Phase</h3>
<ul>
    <li>The top traffic light turns green while the other traffic lights remain red.</li>
    <li>The top traffic light remains green for 8 seconds.</li>
    <li>Vehicles from route 2 can go to routes 3, 5, and 7.</li>
    <li>The top traffic light turns yellow for 2 seconds and then turns red.</li>
    <li>All traffic lights remain red for 4 seconds.</li>
</ul>

<h3>Step 3: Right Traffic Light Phase</h3>
<ul>
    <li>The right traffic light turns green while the other traffic lights remain red.</li>
    <li>The right traffic light remains green for 8 seconds.</li>
    <li>Vehicles from route 4 can go to routes 5, 7, and 1.</li>
    <li>The right traffic light turns yellow for 2 seconds and then turns red.</li>
    <li>All traffic lights remain red for 4 seconds.</li>
</ul>

<h3>Step 4: Bottom Traffic Light Phase</h3>
<ul>
    <li>The bottom traffic light turns green while the other traffic lights remain red.</li>
    <li>The bottom traffic light remains green for 8 seconds.</li>
    <li>Vehicles from route 6 can go to routes 7, 1, and 3.</li>
    <li>The bottom traffic light turns yellow for 2 seconds and then turns red.</li>
    <li>All traffic lights remain red for 4 seconds.</li>
</ul>

<h3>Step 5: Left Traffic Light Phase</h3>
<ul>
    <li>The left traffic light turns green while the other traffic lights remain red.</li>
    <li>The left traffic light remains green for 8 seconds.</li>
    <li>Vehicles from route 8 can go to routes 1, 3, and 5.</li>
    <li>The left traffic light turns yellow for 2 seconds and then turns red.</li>
    <li>All traffic lights remain red for 4 seconds.</li>
</ul>