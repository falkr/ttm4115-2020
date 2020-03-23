# Delivery T2

In this delivery you should reveal some details on the design of your system. The design should cover the main functionality of the system and include the most important critical details. Obviously, once you implement the system, there may turn up more details. The kitchen timer was an idealized example for this. Each team created decent state machines that documented the important details of the kitchen timer. The subsequent implementation could then focus more on the details how to implement specific actions in Python, but the overall logic was settled. 

Some technical hints on the delivery:

- Team delivery, one document per team
- Please use the file name **ttm4115-2020-t2-team-XX.pdf**
- Include the team name on each page, in the footer or header


## Plans for UI Components

Your system will be fully virtual, that means, not contain any specific hardware or sensors.
Instead, you should create [GUI components](tools-gui.html) that simulate the hardware components.
Please include a list of all GUI components you intend to create for your system, and provide a first sketch of them.


## Updated Deployment Diagram

Create a deployment diagram of the system. You can copy the one from T1 and adapt it to any changes in your plans. 

* Take into account what you have learned about components, state machines and about communication.
* Include the GUI components outlined above.
* Identify components that include state machines.

**Hints:**

* Usually a deployment diagram should fit on a single page.
* Use landscape format if you want.



<table class="rubric">
<thead>
<tr>
<th></th>
<th>Excellent</th>
<th>Good</th>
<th>Sufficient</th>
<th>Not rateable</th>
</tr>
</thead>
<tbody>
<tr>
<td>Layout</td>
<td>Layout follows a strategy that helps to understand the diagram.</td>
<td>Layout is structured.</td>
<td>Layout is structured.</td>
<td>Layout is unstructured and random.</td>
</tr>
<tr>
<td>Syntax</td>
<td>Correct syntax.</td>
<td>Correct Syntax.</td>
<td>Overall good syntax, with a few minor errors.</td>
<td>Major syntactical flaws.</td>
</tr>
<tr>
<td>Level of Detail</td>
<td>Consistent and intentional level of detail.</td>
<td>Adequate detailing.</td>
<td>Some inconsistencies, too much focus on some details on the expense of others.</td>
<td></td>
</tr>
</tbody>
<tfoot>
<tr><td colspan=5><a href="learning-grading.html#grading-criteria">Read more about this table...<div></td></tr>
</tfoot>
</table>



## Sequence Diagrams

Prepare sequence diagrams for the main use cases of the system. As you have learned in the team activities, it is hard to cover all details on sequence diagrams, and they may lose their value once we make them too complicated or too comprehensive. Therefore, cover the most important scenarios in an effective way. Use fragments (alt, opt,...) where they make sense, but also consider to just cover the same use case with several sequence diagrams that show different scenarios, dependent for instance on important alternatives and exceptions.

The level of detail should be so that it helps you to convey the overall system interactions, help you to create the state machines and uncover critical situations that require clarifications.

How much? Depends of course on your layout. If two diagrams fit on a page, most of your use cases should be covered within 4 pages. Use your own judgment.


<table class="rubric">
<thead>
<tr>
<th></th>
<th>Excellent</th>
<th>Good</th>
<th>Sufficient</th>
<th>Not rateable</th>
</tr>
</thead>
<tbody>
<tr>
<td>Coverage</td>
<td>All relevant scenarios are handled in an appropriate level of detail and clearness.</td>
<td>All relevant scenarios are handled.</td>
<td>Most relevant scenarios are handled.</td>
<td>Importan scenarios are missing.</td>
</tr>
<tr>
<td>Implied Scenarios</td>
<td>All relevant implied scenarios are handled and clarified.</td>
<td>Some implied scenarios are handled.</td>
<td>No implied scenarios are described.</td>
<td></td>
</tr>
<tr>
<td>Combined Fragments</td>
<td>Appropriate use of combined fragments where relevant.</td>
<td></td>
<td>Occasional inappropriate use, that means used where they don't make sense or lack of use where they would be useful.</td>
<td></td>
</tr>
<tr>
<td>Level of Detail</td>
<td>Consistent and intentional level of detail.</td>
<td>Adequate detailing.</td>
<td>Some inconsistencies, too much focus on some details on the expense of others.</td>
<td></td>
</tr>
<tr>
<td>Layout</td>
<td>Layout follows a strategy that helps to understand the diagram.</td>
<td>Layout is structured.</td>
<td>Layout is structured.</td>
<td>Layout is unstructured and random.</td>
</tr>
<tr>
<td>Syntax</td>
<td>Correct syntax.</td>
<td>Correct Syntax.</td>
<td>Overall good syntax, with a few minor errors.</td>
<td>Major syntactical flaws.</td>
</tr>
</tbody>
<tfoot>
<tr><td colspan=5><a href="learning-grading.html#grading-criteria">Read more about this table...<div></td></tr>
</tfoot>
</table>


1. If you don't find any implied scenarios, make sure your system is suitable for the course and not overly simplifying reality. If despite this there are no implied scenarios, add a comment.


## State Machines

Create state machines for selected components in the system.

* State machines must be syntactically correct.
* State machines must be complete.
* State machines must be implementable in STMPY (in principle), but you don't have to implement them yet.


<table class="rubric">
<thead>
<tr>
<th></th>
<th>Excellent</th>
<th>Good</th>
<th>Sufficient</th>
<th>Not rateable</th>
</tr>
</thead>
<tbody>

<tr>
<td>Control States</td>
<td>Appropriate use of control states that helps to make the machine understandable.</td>
<td>Overall good use of control states.</td>
<td>Overall okay use of control states, with some flaws.</td>
<td>Wrong use of control states. (1)</td>
</tr>

<tr>
<td>Events</td>
<td>Explicit and understandable handling of events by correct use of transitions or <em>/defer</em>.</td>
<td>All relevant events are handled in all relevant states.</td>
<td>Most relevant events are handled in most states where they matter.</td>
<td>Major events are not handled.</td>
</tr>

<tr>
<td>Semantics</td>
<td>Machine is consistent and critical situations explained in comments.</td>
<td>Machine is free of design flaws.</td>
<td>Some inconsistencies, too much focus on some details on the expense of others.</td>
<td>There are major design errors.</td>
</tr>

<tr>
<td>Implementation</td>
<td>Clear how the machine can be implemented in STMPY, ambiguous cases are commented.</td>
<td>Machine is implementable in STMPY.</td>
<td>Machine is generally implementable in STMPY.</td>
<td>Machine contains several constructs that are unclear how to implement.</td>
</tr>

<tr>
<td>Level of Detail</td>
<td>Consistent and intentional level of detail.</td>
<td>Adequate detailing.</td>
<td>Some inconsistencies, too much focus on some details on the expense of others.</td>
<td></td>
</tr>
<tr>
<td>Layout</td>
<td>Layout follows a strategy that helps to understand the diagram.</td>
<td>Layout is structured.</td>
<td>Layout is structured.</td>
<td>Layout is unstructured and random.</td>
</tr>
<tr>
<td>Syntax</td>
<td>Correct syntax.</td>
<td>Correct Syntax.</td>
<td>Overall good syntax, with a few minor errors.</td>
<td>Major syntactical flaws.</td>
</tr>
</tbody>
<tfoot>
<tr><td colspan=5><a href="learning-grading.html#grading-criteria">Read more about this table...<div></td></tr>
</tfoot>
</table>


1. A wrong use of control states would be when variables are used to keep track of information that is more suitable for control states. See [here](unit-statemachines-data.html).


## Overall Delivery


<table class="rubric">
<thead>
<tr>
<th></th>
<th>Excellent</th>
<th>Good</th>
<th>Sufficient</th>
<th>Not rateable</th>
</tr>
</thead>
<tbody>
	
<tr>
<td>Complexity and scope</td>
<td>The chosen scope for the system is appropriate.</td>
<td>The chosen scope for the system is appropriate.</td>
<td>The chosen scope for the system is appropriate.</td>
<td>System is too simple to apply learned material.</td>
</tr>

<tr>
<td>Consistency</td>
<td>All parts of the delivery are consistent.</td>
<td>Overall good consistency.</td>
<td>Some minor errors with the consistency.</td>
<td>Major inconsistencies between the parts.</td>
</tr>

<tr>
<td>Delivery</td>
<td></td>
<td></td>
<td></td>
<td>Late delivery or wrong format.</td>
</tr>

</tbody>
<tfoot>
<tr><td colspan=5><a href="learning-grading.html#grading-criteria">Read more about this table...<div></td></tr>
</tfoot>
</table>