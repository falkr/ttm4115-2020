# Delivery T1: Requirements

This delivery is a partial Vision and Scope document that focuses on why the system exists and what it should do, 
but without all detailed requirements listed. 

This delivery shows already a part of the system solution, by illustrating it with a deployment diagram.



## Grading

**Grading:** You don't receive a grade for this document directly. You will receive feedback on its content from other students, and will re-submit all content as part of the final submission. However, the better this initial submission is, the easier it is to receive valuable comments, and the easier it will be to create a very good final version. (So simply assume that already this version is graded.)

**Rejection:** Since this document is the basis for further work, we may reject it if it does not meet some criteria, both in form or content. You will then need to resubmit an improved version.


# Content

The delivery must contain the following sections:

## Requirements Part

### 1. Problem and Background
 
**Task:** Provide a brief description of the problem you want to solve. It should provide the context so that the reader can understand your vision in the next section.

**Hints:**

* Length should be maximum half a page.
* Formulate the problem and background in complete sentences, not bullet points.
* Focus on the problem and add as much background as necessary for the reader to understand the problem.
* In this part you should not mention the system at all.


### 2. Vision	

**Task:** Provide a vision for the system to build.
All team members should be aware of this vision and share it.
Be concise and specific.
Ideally, the vision connects the objectives with the problem description.
The vision provides some details about the system that explain in very coarse language how the system will tackle the problem.
It highlights what is new or special with the system.

**Hints:**

* Formulate the vision in complete sentences, not bullet points.
* The vision should be ca. ¼th of a page.


### 3. Objectives

**Task:** State at least three objectives, but not much more than five. Objectives are goals that your system can achieve. They need to be specific, and they need to be verifiable. State the objective, and state how it can be verified.
Objectives do not yet explain how the system is implemented, but are oriented towards the users' domain.

**Hints:** 

* Describe the objectives, not the features of the system.
* Show the objectives as a list.


### 4. Stakeholders
	
**Task:** Identify the main stakeholders in the system. Identify their values and interest. Present all in a table. 

**Hints:** 

* Expected length: half a page to a full page.
* Stakeholders are humans or organizations.


### Criteria for the Requirements Part

All sections in the requirement part are evaluated together with the following criteria:

<table class="table table-sm">
<thead>
<tr class="header rubric_title">
<th>Symbol</th>
<th>Description</th>
<th>Criteria</th>
</tr>
</thead>
<tbody>
<tr class="odd rubric_a">
<td>A</td>
<td>Excellent</td>
<td>
	<ul>
		<li>Excellent alignment between all points.</li>
		<li>Focused formulations.</li>
		<li>Excellent and compact presentation.</li>			
	</ul>
</td>
</tr>
<tr class="even rubric_b">
<td>B</td>
<td>Very good</td>
<td>
	<ul>
		<li>All major points addressed and in very good quality.</li>
		<li>Very good vision, that is very well aligned with the problem and objectives.</li>
		<li>Stakeholder considerations reveal valuable requirements and motivation.</li>			
	</ul>
</td>
</tr>
<tr class="odd rubric_c">
<td>C</td>
<td>Good</td>
<td>
	<ul>
		<li>The problem is clearly identified, motivated and explained.</li>
		<li>The vision is clear and consistent and aligned with the problem.</li>
		<li>All major points addressed (including stakeholders, objectives).</li>
		<li>Objectives are specific.</li>			
	</ul>
</td>
</tr>
<tr class="even rubric_d">
<td>D</td>
<td>Satisfactory</td>
<td>
	<ul>
		<li>Problem is addressed and somewhat aligned with objectives and vision.</li>
		<li>A few good objectives are named.</li>
		<li>Some objectives are not well aligned, at a wrong level of abstraction or somewhat unclear.</li>		
	</ul>
</td>
</tr>
<tr class="odd rubric_e">
<td>E</td>
<td>Sufficient</td>
<td>
	<ul>
		<li>All parts addressed, but with considerable shortcomings.</li>
		<li>Problem is addressed, but not clear and not aligned with objectives or vision.</li>
	</ul>
</td>
</tr>
<tr class="even rubric_f">
<td>F</td>
<td>Fail</td>
<td>
	<ul>
		<li>Not delivered or incomplete.</li>
	</ul>
</td>
</tr>
<tr><td></td><td></td><td style="text-align:right; font-size: small"><a href="learning-grading.html#grading-criteria">Read more about this table...<div></td></tr>
</tbody>
</table>


## Use Case Part




### 5. Use Case Sea-Level Hierarchy

This is not an official diagram type, but it turned out so useful for the development process that we decided to add it as part of the delivery.

**Task:** Show at least three use cases at the sea level. Add relevant ones at the fish-level that support the sea-level use cases. Also, make sure to have at least one cloud-level use case and relevant ones at the kit level to connect cloud-level with sea-level. Make sure that the use cases are at the right level and relevant for the vision and objectives of the system.

<!--
* **Task:** Present a use case diagram that covers the major features of your system.
* **Evaluation:** Completeness, plausibility, correctness of syntax, layout, clarity.
* **Hints:** Present a use case diagram that covers the major features of your system. Most likely, the use case diagram will fit on a single A4 page in landscape orientation. This diagram can show more use cases than you will detail in the next task. **This diagram type is shown in the compendium, page 149.** 
-->

### 6. Use Cases in Table Form

**Task:** Describe 3 use cases for the major features of your system. Choose use cases at the sea-level. Follow the table format proposed in the book and shown on page 150.

**Hints:** Most likely, each of the use cases will fit on a single page in portrait orientation. (So use about 3 pages in total.)


### Criteria for the Use Case Part

The main function of the use cases is to provide a clearer picture of the needed system functionality before anything is implemented. 
The value of this part hence is based on its usefulness for the upcoming process.

<table class="table table-sm">
<thead>
<tr class="header rubric_title">
<th>Symbol</th>
<th>Description</th>
<th>Criteria for the Use Case Part</th>
</tr>
</thead>
<tbody>
<tr class="odd rubric_a">
<td>A</td>
<td>Excellent</td>
<td>
	<ul>
		<li>The use cases provide excellent value for the development by addressing relevant issues in a compact form.</li>
		<li>Selected level of detail is consistent.</li>
		<li>Excellent alignment with objectives, vision and upcoming system.</li>			
	</ul>
</td>
</tr>
<tr class="even rubric_b">
<td>B</td>
<td>Very good</td>
<td>
	<ul>
		<li>The described use cases form a cohesive, focused whole that are a very good basis for planning the upcoming development of the system.</li>
		<li>Descriptions are clear, complete and concise.</li>
		<li>All important exceptions and alternatives are handled at a suitable level of detail.</li>			
	</ul>
</td>
</tr>
<tr class="odd rubric_c">
<td>C</td>
<td>Good</td>
<td>
	<ul>
		<li>Use cases have a suitable name.</li>
		<li>Descriptions are clear.</li>
		<li>Good alignment between the user requirements and the use cases is visible.</li>
		<li>Major exceptions and alternatives are handled.</li>			
	</ul>
</td>
</tr>
<tr class="even rubric_e">
<td>D/E</td>
<td>Satisfactory / Sufficient</td>
<td>
	<ul>
		<li>All major information is provided, but some flaws here and there.</li>	
	</ul>
</td>
</tr>
<!--
<tr class="odd">
<td>E</td>
<td>Sufficient</td>
<td>
	<ul>
		<li>Diagram shows some relevant concepts.</li>
		<li></li>
	</ul>
</td>
</tr>-->
<tr class="even rubric_f">
<td>F</td>
<td>Fail</td>
<td>
	<ul>
		<li>Not delivered or incomplete.</li>
	</ul>
</td>
</tr>
<tr><td></td><td></td><td style="text-align:right; font-size: small"><a href="learning-grading.html#grading-criteria">Read more about this table...<div></td></tr>
</tbody>
</table>


## Architecture Part



### 7. Deployment Diagram

**Tasks:** Present a first version of a deployment diagram of your system. Identify the main execution nodes of your system and how they are connected. Identify critical hardware components (even if you later chose to simulate them.) Identify communication protocols that you are already aware of, and identify execution environments.


**Hints:** Most likely, the deployment diagram will fit on a single A4 page in landscape orientation.


### Criteria for the Deployment Diagram


The deployment diagram is evaluated based on general criteria for diagrams.

<table class="table table-sm">
<thead>
<tr class="header rubric_title">
<th>Symbol</th>
<th>Description</th>
<th>Criteria for Diagrams in General</th>
</tr>
</thead>
<tbody>
<tr class="odd rubric_a">
<td>A</td>
<td>Excellent</td>
<td>
	<ul>
		<li>Excellent layout.</li>
		<li>Consistent level of detail that is appropriate for the task of the diagram.</li>
	</ul>
</td>
</tr>
<tr class="even rubric_b">
<td>B</td>
<td>Very good</td>
<td>
	<ul>
		<li>Very good layout, following an overall strategy.</li>
		<li>Completeness with respect to what should be covered.</li>
	</ul>
</td>
</tr>
<tr class="odd rubric_c">
<td>C</td>
<td>Good</td>
<td>
	<ul>
		<li>Diagram is syntactically correct.</li>
		<li>Diagram appears orderly.</li>
		<li>Diagram may contain some minor flaws, but okay overall.</li>			
	</ul>
</td>
</tr>
<!--<tr class="even">
<td>D</td>
<td>Satisfactory</td>
<td>
	<ul>
		<li>Diagram has a number of flaws.</li>
		<li></li>
		<li></li>		
	</ul>
</td>
</tr>-->
<tr class="odd rubric_e">
<td>D/E</td>
<td>Satisfactory / Sufficient</td>
<td>
	<ul>
		<li>Diagram shows some relevant concepts.</li>
		<li>Diagram has a number of flaws.</li>
	</ul>
</td>
</tr>
<tr class="even rubric_f">
<td>F</td>
<td>Fail</td>
<td>
	<ul>
		<li>Not delivered or incomplete.</li>
	</ul>
</td>
</tr>
<tr><td></td><td></td><td style="text-align:right; font-size: small"><a href="learning-grading.html#grading-criteria">Read more about this table...<div></td></tr>
</tbody>
</table>


# Formatting Rules for Deliveries

* Start each section on a new page. 
* Make sure to include team name on each page, in the header or footer of the document.
* Filename: **ttm4115-2018-XX-team-YY.pdf**, where XX is the delivery, like `T1` and YY is your team number, for instance 01 or 13. Consistent file name makes it much easier for us to process all deliveries!
* Diagrams can be included in landscape format, but must be readable from the right. (That means, they must be readable when the page is turned 90 degrees clockwise.
