<h1>Testing Project for YouTube</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: YouTube

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below storys was created in Jira and describes the functional specifications of the "**nume_modul**" module, for which the final project is performed upon.

![image](https://github.com/user-attachments/assets/48be5a9e-5d78-473c-9aa7-f5535526c50b)
![image](https://github.com/user-attachments/assets/8509ab18-9db7-4446-bda8-33e96bd35251)




Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/d6dcbd49-3748-460a-9186-94b34bfc981e)



<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here **(inserati link catre documentul cu planul de testare)**

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager - Sebastian Postole</li> 
  <li>Product owner - Marius Georgescu</li>
  <li>Software developer - Filip Olteanu</li>
  <li>QA Engineer - Alexandru Bucur</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>
<ul>
<li>The requirements for the YouTube application must be documented and reviewed</li> 
<li>Business requirements are completed by the analysis team and are delivered to the appropriate testing team for evaluation</li> 
<li>Sufficient resources, including testers and necessary tools, have to be allocated for testing</li> 
<li>Potential project risks are detected and mitigated</li> 
<li>Roles and responsibilities are allocated</li> 
<li>Test plan should be finalized before entering the next phase of testing, as predetermined by the established schedule, to ensure efficient and effective test execution</li> 
<li>Define the objectives of testing and the accepted level of quality</li> 
<li>The test plan document should be reviewed and approved by stakeholders, including developers and project managers</li> 
</ul>
<h4> 1.1.3 Exit criteria defined </h4>
<ul>
<li>70% or more of the tests are passed</li> 
<li>All identified test cases are executed, and the results are documented</li> 
<li>No critical issues have status open</li> 
<li>All detected errors have been reported and closed</li> 
<li>The test coverage meets the predetermined criteria, ensuring that all major functionalities and scenarios have been tested</li> 
<li>The product usage documentation has been finalized with the scenarios evaluated during the testing phase</li> 
<li>The budget was reached</li> 
<li>The deadline was reached</li> 
<li>The application is stable, with no significant crashing, freezing, or unexpected behavior encountered during testing</li> 
<li>Test completion report has been created and sent to the stakeholders to ensure its completeness and accuracy</li> 
<li>Product risks have been identified and mitigated</li> 
<li>The objectives defined in the test planning phase have been accomplished</li> 
</ul>
<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>
<ul>
1. Playlist Functionality
<li>Playlist Creation:</li>
 <li>Verified the ability to create new playlists.</li>
 <li>Tested with a minimal number of videos to confirm system behavior at lower limits.</li>
<li>Edit Playlist Features:</li>
 <li>Renaming playlists.</li>
 <li>Changing visibility settings (e.g., Private, Unlisted, or Public).</li>
 <li>Ensured changes were saved and correctly displayed in the user interface.</li>
</ul>
<ul>
2. Video Uploading
<li>Upload Process:</li>
 <li>Verified uploading of videos via the standard YouTube interface.</li>
 <li>Confirmed successful upload, processing, and visibility in the video library.</li>
<li>Video Personalization:</li>
 <li>Tested the ability to set a custom video title during upload.</li>
 <li>Verified the option to set video visibility (e.g., Private, Unlisted, Public) and ensured correct behavior post-upload.</li>
</ul>


<h5>Tests not in scope: </h5>
<ul>
<li>Functionality on mobile platforms (Android and iOS apps).</li>
<li>Video upload size limits and boundary testing for large file uploads.</li>
<li>Playlist or video upload behavior on mobile browsers.</li>
</ul>

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>
<ul>
<li>Core functions (playlist and video upload) were tested manually, with no automation for future regression.</li>
<li>Manual testing may miss edge cases like unusual names or privacy setting combinations.</li>
<li>Repeating tests across updates is time-consuming and prone to human error without automation.</li>
</ul>
<h5> Product risks: </h5>
<ul>
<li>Special characters in playlist or video titles are not supported.</li>
<li>Private mode for playlists or videos does not function correctly.</li>
<li>Playlist creation is limited to a maximum of 10 videos.</li>
<li>Uploaded videos may be publicly visible even when set to private.</li>
<li>Limited playlist flexibility may impact content organization and usability.</li>
</ul>

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

![image](https://github.com/user-attachments/assets/6dea2090-ffab-4e97-853c-b5d5b9e746d6)


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. 

The following test conditions were found: <br>

![image](https://github.com/user-attachments/assets/e5c26a34-bd4f-4353-8154-c614ac405f0e)


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**
