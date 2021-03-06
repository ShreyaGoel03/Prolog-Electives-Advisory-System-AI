# Prolog-Electives-Advisory-System-AI
<p align="justify">
Prolog has been used to create an electives advisory/prediction system for the M.Tech Students based on their branch, specialization and the career choice they want to pursue.
<br/>
<p>

### Algorithm Design:
<p align="justify">
The overview of the whole system is as follows:<br/>
1. Firstly, the name and GPA of the student has been taken as input. Comments are being displayed according to the GPA of the student.<br/>
2. The system is cleared by calling the retractall of which clears the stored user progress. The prerequisites, electives and the career tab is cleared.<br/>
3. Now, the current status of any ongoing MTP, aptitude and communication skills are taken as input.<br/>
4. Now, considering the CSE(AI, DE, IS), ECE(VLSI, CSP) and CB branches of M.Tech, the student is asked about its respective branch and the specialisation. According to the branch and specialisation, then the student is displayed with the respective choice of career in those fields. Taken cases are shown in the table below.<br/>
5. Now, according to the respective career chosen, particular electives which fall under that category are being considered. Series of questions are being according to those electives prerequisites if the student has done or knowledge about them.<br/>
6. After the student has answered the respective questions of prerequisites, then the electives which can be taken are being displayed with respective descriptions about them.<br/>
7. Extra information on aptitude, communication skills and MTP/Thesis is also being displayed to work on that respectively.<br/>
</p>

<p align="justify">
For example, the student is displayed with three branches, CSE, ECE and CB. Suppose, If the student chooses CSE, then he is displayed with three specialisations, AI, DE, and IS. If the students choose DE, then the student is displayed with career
choices respectively. Then for De, the choices are, 1. Big Data Engineer, 2. Software Developer/ Full Stack Engineer, 3. Database Administrator., Now whatever the student chooses the career, then the electives required for that career are considered. The
prerequisites according to those electives are being asked to the student if he has the
knowledge of them or not. After series of questions, the electives are being displayed to
the student with descriptions of them.
<br/>
</p>

### Cases Table:

| Branch | Specialisation | Career Paths |
| :---         |     :---:      |          --- |
| CSE   | Artificial Intelligence | 1. Artificial Intelligence(AI)/Machine Learning(ML) Engineer.<br/> 2. Artificial Intelligence Data Analyst. <br/> 3. Research/Data Scientist. |
| CSE   | Data Engineering | 1. Big Data Engineer. <br/> 2. Software Developer/ Full Stack Engineer. <br/> 3. DataBase Administrator. |
| CSE   | Information Security | 1. Security Engineer.<br/> 2. CyberSecurity Engineer. <br/> 3. Cryptographer/Cryptanalysis. |
| ECE   | VLSI & Embedded Systems (VLSI) | 1. VLSI Design Engineer Head.<br/> 2. Hardware Engineer. <br/> |
| ECE   | Communication and Signal Processing (CSP) | 1. Electronics and Electrical Engineer.<br/> 2. Communication Engineer. <br/> |
| CB   | Computational Biology | 1. Computational Biologist |


### Output:
Here shown: <br/>
CSE - DE - Software Developer.

![Run1](https://user-images.githubusercontent.com/43794593/154134723-e5e93063-f297-4a5b-a7dc-01a21a0a7f27.png)

![Run2](https://user-images.githubusercontent.com/43794593/154134729-e7b6d773-7400-4878-9725-17c6028aff23.png)

![Run3](https://user-images.githubusercontent.com/43794593/154134736-6d62e9c4-4210-4326-b6ad-eca4ae230b07.png)

![Run4](https://user-images.githubusercontent.com/43794593/154134739-fd5d4fcb-82a7-4fb5-ae43-1b272a6c9c3c.png)

![Run5](https://user-images.githubusercontent.com/43794593/154134742-59d219ea-1c88-4be5-a547-a18950d9c0a4.png)





