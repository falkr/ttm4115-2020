# Design of Communicating Systems


### Step 1: Prepare for Monday, Jan. 13th 2019

Work through the following material _before_ class time:

<a href="prep-introduction.html" class="arrow">Preparation Material</a>

### Step 2: Class!

Come to the <mark>first class on Monday, Jan. 13th</mark> in [EL-23](http://bit.ly/2p6mAhe).
If you can't come, follow the instructions at the end of the preparation material above.


# Course Content



In this course you will learn about systems in which communication is an important part of functionality. We will study technologies to build these systems, how communication protocols can be used in combination with components and program code. 

---
type: figure
source: figures/ttm4115-content-systems.png
---

You will also learn how to describe these types of systems. We will create system models with various notations, at various levels of detail and with different degree of rigor. This includes formal modeling in terms of state machines, but also simple and effective sketches of the system on a whiteboard. As part of this, you will learn how to think in states and transitions, and how to describe complex interactions efficiently.

---
type: figure
source: figures/ttm4115-content-descriptions.png
---

Part of system development is also the coordination of a team of developers and the management of resources. You will therefore learn about development processes and directly experience the dynamics in a team.

---
type: figure
source: figures/ttm4115-content-people.png
---

<a class="arrow" href="learning-goals.html">Read more about the Learning Goals</a>



# Schedule

Each week, we follow the same schedule:

* Individual preparation before class time.
* **Monday 10:15-12:00** Class time in [EL-23](http://bit.ly/2p6mAhe)
* Teamwork on week activities, ca. 2 hours
* Teamwork on semester project

Here is the schedule: 


<div>
<table class="table table-sm">
<caption style=""></caption>
<thead>
<tr class="row-1">
<th>Week</th><th>Date</th><th>RAT</th><th>Preparation</th><th>Deliveries</th>
</tr>
</thead>
<tbody class="row-hover">
<tr class="row-2">
<td class="column-1">2</td><td class="column-2">6. Jan.</td><td></td><td class="column-3"><em><span class="minor">no class on campus</span></em></td><td class="column-4"></td>
</tr>
<tr class="row-3">
<td class="column-1">3</td><td class="column-2">13. Jan.</td><td><span class="badge badge-secondary" style="background-color: #bbbbbb">RAT 0</span></td><td class="column-3"><a href="prep-setup.html">Introduction and Course Setup</a></td><td class="column-4"></td>
</tr>
<tr class="row-4">
<td class="column-1">4</td><td class="column-2">20. Jan.</td><td><span class="badge badge-secondary">RAT 1</span></td><td class="column-3"><a href="prep-modeling.html">Modeling and Deployment</a></td><td class="column-4"></td>
</tr>
<tr class="row-5">
<td class="column-1">5</td><td class="column-2">27. Jan.</td><td><span class="badge badge-secondary">RAT 2</span></td><td class="column-3"><a href="prep-requirements.html">Requirements and Design Thinking</a></td><td class="column-4"></td>
</tr>
<tr class="row-6">
<td class="column-1">6</td><td class="column-2">3. Feb.</td><td><span class="badge badge-secondary">RAT 3</span></td><td class="column-3"><a href="prep-use-cases.html">Use Cases</a></td><td class="column-4"></td>
</tr>
<tr class="row-7">
<td class="column-1">7</td><td class="column-2">10. Feb.</td><td><span class="badge badge-secondary">RAT 4</span></td><td class="column-3"><a href="prep-statemachines.html">State Machines</a></td><td class="column-4"><span class="badge badge-danger">T1</span></td>
</tr>
<tr class="row-8">
<td class="column-1">8</td><td class="column-2">17. Feb.</td><td><span class="badge badge-secondary">RAT 5</span></td><td class="column-3"><a href="prep-stmpy.html">State Machines in Python</a></td><td class="column-4"><span class="badge badge-primary">I1</span></td>
</tr>
<tr class="row-9">
<td class="column-1">9</td><td class="column-2">24. Feb.</td><td><span class="badge badge-secondary">RAT 6</span></td><td class="column-3"><a href="prep-interactions.html">Interactions</a></td><td class="column-4"> </td>
</tr>
<tr class="row-10">
<td class="column-1">10</td><td class="column-2">2. Mar.</td><td><span class="badge badge-secondary">RAT 7</span></td><td class="column-3"><a href="prep-communication.html">Communication</a></td><td class="column-4"></td>
</tr>
<tr class="row-11">
<td class="column-1">11</td><td class="column-2">9. Mar.</td><td><span class="badge badge-secondary">RAT 8</span></td><td class="column-3"><a href="prep-components.html">Components</a></td><td class="column-4"></td>
</tr>

<tr class="row-15">
<td class="column-1">15</td><td class="column-2">16. Mar.</td><td><span class="badge badge-secondary">RAT 9</span></td><td class="column-3"><a href="prep-agile.html">Agile Development</a></td><td class="column-4"><span class="badge badge-danger">T2</span></td>
</tr>

<tr class="row-13">
<td class="column-1">13</td><td class="column-2">23. Mar.</td><td></td><td class="column-3"><em>Focus on T2</em></td><td class="column-4"><span class="badge badge-primary">I1</span></td>
</tr>

<tr class="row-14">
<td class="column-1">14</td><td class="column-2">30. Mar.</td><td></td><td class="column-3"><em>Focus on T3</em></td><td class="column-4"></td>
</tr>


<tr class="row-16">
<td class="column-1">16</td><td class="column-2">6. Apr.</td><td></td><td class="column-3"><em><span class="minor">no class on campus (easter)</span></em></td><td class="column-4"></td>
</tr>
<tr class="row-17">
<td class="column-1">17</td><td class="column-2">13. Apr.</td><td></td><td class="column-3"><em><span class="minor">no class on campus (easter)</span></em></td><td class="column-4"></td>
</tr>
<tr class="row-18">
<td class="column-1">18</td><td class="column-2">27. Apr.</td><td></td><td class="column-3"><em><span class="minor">no class on campus</span></em></td><td class="column-4"></td>
</tr>
<tr class="row-18">
<td class="column-1">18</td><td class="column-2">27. Apr.</td><td></td><td class="column-3"><em><span class="minor">no class on campus</span></em></td><td class="column-4"></td>
</tr>
<tr class="row-19">
<td class="column-1">18</td><td class="column-2">4. May</td><td></td><td class="column-3">Launch Day</td><td class="column-4"><span class="badge badge-danger">T3</span> </td>
</tr>
<tr class="row-19">
<td class="column-1">19</td><td class="column-2">11. May</td><td></td><td class="column-3"><em><span class="minor">no class on campus</span></em></td><td class="column-4"><span class="badge badge-primary">I3</span></td>
</tr>
</tbody>
</table>
</div>


# Learning

<mark>This course combines team-based learning with a semester project.</mark>
During the course, you will develop a system together with your teammates. The units each week support you during this task, from a requirements analysis, use case analysis towards a robust system specification and design that you then implement. During the semester you will need to hand in deliveries that document the different stages of your system. This is similar to a process in industry you will encounter later, just a bit adapted so it fits into a semester.

Though there is lots of team work, there is enough room for you to also work individually. The course requires preparation each week, which you can complete at your own speed and schedule. This preparation gives you the basic knowledge and understanding to work together, and it will be tested in class so that you get immediate feedback on your own progress.

<a class="arrow" href="learning-tbl.html">Read more about Team-based Learning</a>


# Grading

<mark>There is no final written exam in the course.</mark> 
The grading scheme is based on the RATs (quizzes) during class and the deliveries you hand in as teams as well as the ones you do individually. 
All these items give enough material for robust and balanced grading.

<a class="arrow" href="learning-grading.html">Read more about Grading</a>