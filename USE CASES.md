Use Case #1

Primary Actor:

	Company Manager

Goal in Context:

	The company manager is able to determine license and vulnerability information from provided project information

Stakeholders:

	o	Company Manager: To receive clear and relevant project information

	o	Company Developer: To provide the relevant file/package level information

	o	Project Owner: To clearly understand company manager decisions to green/red light a project

	o	Software Owner: Sets the license and can request the software be removed.  

Preconditions:

	o	Relevant file/package information is in the Program and License database

	o	Proper project information has been provided

Main Success Scenario:

	Company manager receives accurate license and vulnerability information for the requested project packages

Failed End Conditions:

	Company manager receives inaccurate or invalid license and vulnerability information for the requested project packages

Trigger:

	Company manager uploads or identifies project information to which license and vulnerability information is provided


Use Case #2

Title : Input Program

Primary Actor : Developer

Goal in Context : Developer enters the Open Source Software to the Database and the OSS is acceptable for the company’s use

Stakeholders : Developer, Manager, Company, Open Source Program owner

Preconditions : 

Main Success Scenario: The program is accepted as usable for the company.

Failed End Conditions:

	The program is rejected.

	The program license cannot be found.

	The program scanner fails to match the license correctly.

Trigger :
