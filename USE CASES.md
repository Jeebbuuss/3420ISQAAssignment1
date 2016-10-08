Use Case #1

Primary Actor:

	•	Company Manager

Goal in Context:

	•	The company manager is able to determine license and vulnerability information from provided project information

Stakeholders:

	•	Company Manager: To receive clear and relevant project information

	•	Company Developer: To provide the relevant file/package level information

	•	Project Owner: To clearly understand company manager decisions to green/red light a project

	•	Software Owner: Sets the license and can request the software be removed.  

Preconditions:

	•	Relevant file/package information is in the Program and License database

	•	Proper project information has been provided

Main Success Scenario:

	•	Company manager receives accurate license and vulnerability information for the requested project packages

Failed End Conditions:

	•	Company manager receives inaccurate or invalid license and vulnerability information for the requested project packages

Trigger:

	•	Company manager uploads or identifies project information to which license and vulnerability information is provided

_______________________________________________________________________________________________________________________________________


Use Case #2

Title:

	•	Input Program

Primary Actor:

	•	Company Developer

Goal in Context:

	•	Company Developer enters the Open Source Software to the Database and the OSS is acceptable for the company’s use

Stakeholders:

	•	Company Manager: To receive clear and relevant project information

	•	Company Developer: To provide the relevant file/package level information

	•	Project Owner: To clearly understand company manager decisions to green/red light a project

	•	Software Owner: Sets the license and can request the software be removed.  

Preconditions:

	•	Relevant file/package information is in the License and Vulnerability Database

	•	Proper software information has been provided

Main Success Scenario:

	•	The program is accepted as usable for the company.

Failed End Conditions:

	•	The program is rejected.

	•	The program license cannot be found.

	•	The program scanner fails to match the license correctly.

Trigger :

	•	The company developer enters the Open Source Software into the Software License and Vulnerability Scanner for a scan of the software to compare with the License and Vulnerability Database files.


____________________________________________________________________________________________________________________________________________


Use Case #3

Primary Actor:

	•	Company Manager

Goal in Context:

	•	The company manager is able to update the License and Vulnerability Database files in the License and Vulnerability Database.

Stakeholders:

	•	Company Manager: The company manager needs to receive clear and relevant project information
	
	•	Company Developer: The company developer needs to provide the relevant file/package level information
	
	•	Project Owner: The project owner needs to clearly understand company manager decisions to green/red light a project

Preconditions:

	•	Relevant file/package information is in the License and Vulnerability Database
	
	•	License and/or vulnerability information has been provided

Main Success Scenario:

	•	Company manager uploads accurate license and vulnerability information to the License and Vulnerability Database.

Failed End Conditions:

	•	Company manager updates inaccurate or invalid license and vulnerability information for the requested project packages

	•	The database refuses to update the files

	•	The uploaded files are damaged before the database receives the files

	•	The company manager receives the incorrect updated file.

	•	The company manager receives a successful update status when the file does not successfully update

Trigger:

	•	Company manager uploads new or updated license and/or vulnerability files to the License and Vulnerability Database.
