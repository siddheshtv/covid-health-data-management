## Covid Health Data Management
Deepbrains.ai Hackathon Project

Author: Siddhesh Kulthe

## Title
Patient Health History Record System

## Abstract
This project aims to model and develop a Data Lake (repository that contains structured,
semi-structured and unstructured data) for data from patients in the healthcare
system. This Data Lake contains both relational databases and unstructured data (result
of image exams) and semi-structured data (XML files that are exported by equipment)
that make up the patient's history. The planning is for this Data Lake to be accessed via
mobile application and via the Web. The Data Lake will be powered by both doctors,
laboratories, and the patient himself. Doctors will be able to access the patient's entire
life in a clear, safe and fast way. Thus, if the patient changes doctors, all of their
information remains available in an integrated manner. Doctors will be able to exchange
vital patient information with each other via the system. An example would be a patient
who finds out he has diabetes and needs his nutritionist to reevaluate his diet. Within
minutes the patient would have access to a new diet sent by his nutritionist. In an
emergency, the patient, even unconscious, could have his data released via the doctor's
ID, taking responsibility for the access in an extraordinary way. If the patient so wished,
he could obtain prognoses about probable diseases that he could develop based on
analysis of the data of his health history through the application of Artificial Intelligence
techniques. In addition to the clear advantages for the patient, the government would
have a much more reliable and secure mass of data to carry out its analyzes for the
public health policies adopted. In cases of emergencies such as pandemics, the
government could quickly and safely know the groups of risks that would have to be
insured and their current situation.

## Introduction
Nowadays, when patients schedule a medical appointment and need to submit their
exams, they are required to carry a large volume of printed material. In addition to the
potential inconvenience of having to carry this documentation, a lot of information can
be lost. Countless patients have their vaccination card, exams and the record of several
other procedures performed throughout their lives lost due to the action of the weather,
rain or loss of them. When migrating from the private network to the public network, or
vice versa, your health history may no longer be accessed, being inaccessible. In
addition, most health information is not digitized. All of these circumstances cause loss
of important information throughout the patient's life. With advances in technology,
storing patient data has become a necessary and fundamental action for healthcare
professionals. In the last few years, the data has proved to be the biggest commodity in
the industry, in the academy and in the health area. With the increasing increase in data
production and the rapid development of Big Data technologies, cloud computing and
machine learning, the value of data has been identified in several domains, especially
in the health area. However, there are still barriers to the dissemination of scientific data
among the various researchers, such as proprietary, heterogeneous formats, access
permissions, etc. This isolation of data creates data silos. Non-integrated data storage
can cause healthcare professionals to miss out on research and development
opportunities. In addition, this information must comply with the new legislation, which
will start to take effect soon. However, patient data is heterogeneous, voluminous and
confidential. Several technologies can support this sharing, eg, Data Warehouses (DW),
which are multidimensional databases used for data integration. However, DWs store
only structured data (many scientific data are semi -structured or unstructured), their
modeling can be complex and time-consuming and require a high development
time. More recently, the Data Lake concept has emerged as an approach to integrating
structured, semi -structured and unstructured data. A Data Lake is an approach that
consists of a data repository associated with an engine for processing queries and
data. 
The great advantage of a Data Lake is that it does not require prior modeling and is
capable of storing data in its raw format (not necessarily in a structured way), preserving
the principle of immutability. However, in order to be able to store and query data in
different formats, Data Lake must have a series of metadata in order to facilitate the
location of the data and its subsequent analysis. There are several solutions for
Data Lakes on the market, with the Hadoop stack solutions being the most
used (https://www.searchtechnologies.com/blog/search-data-lake-with-bigdata). However, these solutions have several limiting factors when dealing with health
data. Many healthcare professionals lack computer expertise and dealing with
technologies like HDFS, Hadoop and Spark may not be trivial. In addition, source data
(history of creation, alteration and deletion of data) must be captured, as well as data
privacy issues. Healthcare professionals must be able to query and view the data
intuitively, in addition to being able to generate new data for Data Lake after applying
certain processing (eg, a machine learning algorithm). Thus, the present project
proposes the development of a system that supports the management of Data Lakes for
health data. With the system, doctors can: (i) import data from multiple sources into
Data Lake through an intuitive interface, (ii) associate source data with imported data
(say the source of a particular exam), (iii) apply anonymisations to the imported data,
(iv) consult data in different formats and (v) feed Data Lake with data from processing
within the Data Lake environment itself. In this way, the
government administration would have more control over the data of its population and
could establish health policies in a less uncertain way, better control the health system,
better plan and invest resources, in addition to better monitoring patients.
Proposal relevance
From the government's point of view, this project aims to meet the demands of the most
vulnerable population in relation to public health needs in order to maximize hospital
care and subsidize decisions aimed at better targeting public health policies. The
government will be able to better target medical specialties according to the demands
of the population. For example, identifying that a community with a majority of elderly
people does not offer support from a geriatrician. Logistics can be maximized by
sending supplies to places that really need them, such as a greater amount of flu
vaccines where there is a higher incidence of this disease. Health studies may use
Artificial Intelligence models to discover where there is a greater possibility of such
diseases according to the health situation of a given region. In the event of an
emergency such as an outbreak or epidemic, the government could quickly learn and
take the necessary measures in relation to the vulnerable population. In the case of
using Telehealth, these more reliable and fast data are essential for the doctor, at a
distance, to have knowledge of the patient's health history and perform a safe care. With
this, the government can assist patients using specialists at a distance and at a low
cost. Another problematic point is the repetition of the same procedure by two or more
doctors in a short period of time. With this system this problem could be minimized
because if the doctor makes a repetitive order, the system will charge and the doctor
will be notified. In this case, the doctor will be able to confirm the request if necessary
or view the last same procedures that were performed. For the government to have this
mass of data updated and secure would be fundamental to its public policy. From the
patient's point of view, he will be seen more quickly at the health points with his data
being made available to the reception and to the doctor who, even before the
consultation, will have access to his updated health history for a better analysis of his
case. The health system's monitoring of the patient's life and needs will be safer and
more reliable. The patient and the doctor will be able to access the results of procedures
on their cell phones or computers without having to search the places where they were
made. This would make the patient have a quick medical response in the event of an
emergency. It would also be possible for doctors to form a group at a given moment and
be able to exchange information about the patient if necessary. For example, a patient
discovers that he has diabetes and at the same time his nutritionist receives the exam
sent by his doctor and already updates his diet in minutes. If the patient arrives for care
in an emergency situation, without being conscious, the doctor who attends him will be
able to access his data using a standard password linked to his ID. 
After the appointment, the patient or his family will be able to confirm or not the state of
emergency. The patient will be able to interact his data with Artificial Intelligence models
to generate possible diagnoses of diseases that can be developed during his life. From
a medical point of view, patient care will be safer and faster. In emergencies, decisions
can be made based on more reliable and secure data. All procedures can be accessed
at any time, making service faster, safer and more reliable. It would also increase the
number of patients seen thereby speeding up the waiting line. In the use of e-Health the
doctor would have complete safety and reliability in treating a patient even at a distance
with more accurate and updated data. To finish all these fermentes, they would make it
possible to dry the public machinery as well as its flexibility and dynamism. Every public
health policy would be guided by much more accurate and current data. The
government would have the public health situation in real time and could even estimate
future data. This could be used in the form of Big Data by joining the population's health
data with others such as education and safety, among others. With this, the government
will be able to access the most important public information and generate statistics and
projections for its population.

## Objective to be executed
Computer systems based on patient information need precision, which is not the current
reality. The storage services in the health area, in most cases, when they exist, are not
reliable. The big problem with electronically storing medical files is the standard that
each healthcare professional uses. In view of these problems, we propose to develop a
way to store patient information, quickly and safely, without modifying the original data
regarding its format. The project aims to create a System based on the Data Lake
concept that can be accessed by cell phone application and web-based systems. Data
Lake would be powered by the patient himself, doctors and the public health
system. The patient could delegate this function to someone they trust if they have any
limitations. In the case of data feeding by the patient, he inserts each procedure done
through the cell phone or if you prefer by the computer. To do so, simply enter the
procedure information via the form. If the procedure is using paper or similar, the patient
can take a photo and store the image in digital form for later consultation with the
doctor. If you use a computer this can be done by scanning the procedure. The doctor
may enter pertinent information with the patient's approval, but it will be identified as
information added by the doctor to your ID. This system will be based on a Data Lake
that has the patient's personal data and history of all procedures performed by him, in
addition to the results of the exams. The doctor, or whoever is going to access the
patient's data, can only do so with the patient's authorization. The system will generate
an access password that can be canceled by the patient or will expire with a certain
time. If the patient is unable to perform this process, the doctor will use a standard
password on an emergency basis. To finish the service, the patient or family member
must confirm the emergency care by the doctor. Until this process is performed, the
system is locked. This project will reach people who use the public health system, which
already uses something similar, and people who came from the private health
system. Patients who have migrated from the private to the public health system can
download their procedures from the private network and store them in their health
history before finalizing the contract. The database is the main purpose of this project,
as it aims to store information in a simple but reliable and safe way of health-related
data for the entire life of the patient. The best way to store and standardize data will be
studied. Account will be taken of how to insert information to better suit patients,
including the elderly and those in vulnerable situations. A quick and central information
guide to answer questions will also help people to make better use of the application. As
a consequence, we will have quality public health, doctors being able to practice their
profession with more quality and a government that can identify and solve public health
policy problems more effectively. Hospitals will be able to serve better and more patients
with this, unblocking the bottleneck of this system and minimizing the wait for
care. Public money can be used in a more targeted way to public health points and the
population of the most vulnerable regions. 

## Objectives and Scope
The project aims to achieve the main objective of integrating public health data through
a Data Lake so that the government can make decisions based on accurate and reliable
information. A management system for this Data Lake will be developed that will allow
the use of e-Health in a safe and reliable way, taking patients the best specialists
available. Through this Data Lake, it will be possible to create disease prediction models
using Artificial Intelligence techniques and the use of mathematical and statistical
models allowing the government to be able to make more reliable and secure decisions
even in an emergency, such as outbreaks and epidemics. Other points to be achieved
include minimizing waiting times and maximizing the quality of patient
care, providing tools for safe and reliable storage of patient data throughout their lives,
minimizing losses from procedures performed by patients, and complying with the new
legislation to protect personal data. Doctors will be able to issue prognoses and
diagnoses based on secure information, always be in contact with their patient, obtain
updated data from their patient in case of emergency for their decision making, and
therefore, the doctor's work will be more efficient and quality. The project aims to meet
the demand for better quality information from governments for decision-making in
relation to public health policies. The data available today is not up to date and
reliable. In addition, they are in national databases. The availability of data that is
structured based on government actions in the area of public health may represent a
more interesting alternative for both the clinical team and managers.
Goals
With a team of 8 people, coordinator, vice coordinator, a researcher, a specialized
technician and four students, it is possible to carry out this project in a period of 2
years. The first step will be the organization of the data that will compose the Data
Lake. It is important to discover the source of the data, its formats and forms of
integration. This requirements survey must be in line with the government's needs. This
process would include visits to health units to verify on the spot the functioning of the
units. The proposed goal is to visit at least 30% of health units in the first 6 months. It is
also proposed to hold at least 4 meetings with the government team so that the data
and Data Lake models as a whole can be evaluated. Once the system needs are
diagnosed, new meetings with the government team will aim to map all Data Lake
functionalities that were not identified in this proposal. The goal is to hold at least 3
meetings for this purpose. The identification of the functionalities will allow the
elaboration of the Project Specification Document, which details with all the descriptions
everything that the system will carry out, and outlined by the Use-Case Diagram, which
is a logical guide for the developers. The Relationship Entity Modeling will also be
developed in the case of structured data. Integration with semi-structured data will take
place through wrappers. The tests will be carried out with the end user in evaluation
sessions to be scheduled with the government. The errors are reported by the
representatives of the government and subsequently corrected by the developers. For
this step it provides for at least four interactions between developers and the staff of
the government. The initial version for testing is expected to be installed in 12 months
and an approval version in 14 months. Documentation: at least 2 manuals will be
prepared: a document with details about the code so that any changes, updates or
implementation can be made by any other developer in the future and the installation
and use manuals to assist users in an instructive way. After the model has been tested
and confirmed as fit for use, we will start creating the web version system and mobile
application. Finally, it is proposed to hold 6 seminars to present the system and train
users.

## Methodology
The present methodology is divided into: Analysis of the Informational Environment:
The steps developed in this phase work with concepts discussed in the theoretical
framework and aim to identify two important issues: the requirements and the types of
data that will be stored in the Data Lake. The requirements will form the basis for
defining the Information Architecture. 
The requirements analysis allows a horizontal and cross-functional view, in order to
better understand the procedures and define what is essential for their performance. In
general, process modeling allows you to obtain a macro view, from which you can
understand your objectives, evaluate possible solutions to your problems and take
corrective measures to deviate from an ideal situation. Through process modeling, it is
possible to: explain the vision of those responsible for the processes; obtain an
integrated and complete view of the processes; explain rules; simplify and optimize
processes; explore new concepts, and plan the information, systems and necessary
infrastructure. There are three major flows of information to be identified: information
collected externally, information produced internally, and information produced and
intended for the public. Diagnostic Stage: This stage aims to analyze the organizational
and functional structure of all the structure of public health. To conduct this analysis,
four activities are developed: Analysis of the Organizational and Functional Structure:
The objective of this phase is, Identification of the organization chart and functioning of
the procedures. Analysis of the Business Environment: The objectives of this activity
are to identify and conceptualize how all public health procedures work. Strategy
Analysis - This activity will be carried out in pursuit of the following objectives: survey of
the objective, strategic points, among other strategic considerations raised by
the government. As a secondary objective of this activity, an analysis must be made to
identify possible problems existing in the procedures and what are the requirements for
their resolution, the opportunities for improvement, reengineering solutions, always with
a focus on the project. Analysis of Information Systems. This activity aims to raise the
existing systems in the public health area as developed systems and those maintained
by the government's computer area as well as systems developed directly by users,
using spreadsheets, text editors or another tool. Every form of storing data under
the responsibility of the government. Process Analysis: This step aims to make an
analysis of the processes used. In order to conduct this analysis, four activities are
proposed: Definition of Processes: The Identification of Macroprocesses, has the
objective of knowing the strengths and weaknesses and seeking a competitive
differential, therefore, it is essential to raise within the structure the main processes and
their activities. The identification of these processes allows a greater clarity of the
internal environment and its relationships with the external environment. Analysis of
Processes: The correlation between processes and healthcare units is a useful product
as a starting point for process reengineering, as it is possible to identify the relationship
between healthcare facilities and processes. For each process, identify the health
units. Analysis of Processes in front of Information Systems - For each business
process, identify the existing information systems that provide and create information
related to the process and sub- process. This correlation is the starting point for
identifying the processes that are poorly served by information systems, the degree of
independence of the user areas and the level of information integration. Reengineering:
Objectives and Priorities - This activity is a complement to previous activities with the
objective of modeling an adequate information environment to design the executive
information system. Analysis of Information Needs: The creation of an integrated
information environment, internal and external, that allows the evaluation of results and
strategies, in addition to enabling the identification and access to information, require
an architecture of this information. The design of an Information Architecture is based
on two major blocks of study: the processes of and the information matters necessary
for these processes. The stage aims to make an analysis with the existing organizational
processes, Functional Areas and Information Systems, the material that will support
these analyzes are the instruments of the previous stages. For analysis, three activities
are scheduled: Analysis of Information Necessary to Organizational Processes: In this
step the focus should be on the information needs that guarantee the efficiency of the
process and allow to outline the appropriate strategy for the objectives in which the
project is aimed. The resultant result of this activity is: List of the necessary information
by organizational process. Definition Information Matters: The analysis of information
matters involves an analysis of information flows existing in the government, which fall
into three main groups: information collected externally and used by it, information
produced internally and used, and information produced and destined for the public. 
Definition of the General Information Architecture: The definition of a compatible
information architecture to meet the organizational model, in addition to involving a
technological update, also contributes to the integration of the operational and financial
systems and to the development of an Interconnected Information System and
Organizational Knowledge Management. The information architecture for the executive
information system is defined based on the analysis of macro processes in relation to
the identified information issues. This definition involves four stages described below:
Correlating Processes and Information Matters; Grouping of Macroprocesses in Logical
Systems; Identification of information links between processes; Overview of process
integration. Management Assessment: This step aims to analyze the organizational and
functional structure of all health points that make up public health. To conduct this
analysis, two activities are developed: Validation of the Reengineering of Organizational
Processes and Validation of the General Information Architecture. The next step will be
the Executive Information Environment Project: Decision Support Analysis: This step
aims to fulfill the requirements necessary to identify the information that will compose
the information system. To conduct this analysis, four activities are developed: Analysis
of the Result Areas. This activity has as support material the instruments and products
generated in the previous stages. Each person in charge receives the support material
describing the Project's Mission, Vision and Strategies. In this case, the concept used
is that of the Logical View, that is, that view that models the functional characteristics
that the system provides to end users. Result Indicators: The role of performance
indicators in the improvement of processes is of fundamental importance to achieve the
defined objectives. To carry out this activity, the methodology uses the methodological
instrument that identifies the Information Needs by Vision, Result Area and
Indicators. Each responsible fill this instrument for later examined and validated by the
project team and representatives of the government. Analysis of Information Needs: At
the end of this step, once again, each person in charge of the methodological
instrument: Information Needs by Vision, Result Area and Indicators, fills in the data
following the activities previously performed and which defined the visions and within
from each of the views the respective result areas with their indicators. Management
Assessment: With all the assembled team, the products of this phase are presented
and validated and should be prepared the final report by the project team and
representatives of the government.

## Results
Studies indicate that there is an evident change in the operational practice of health
work activities after computerization. The substitution of the written record on paper for
the one typed on the equipment has the potential to optimize various work processes,
making the sharing of information wider and easier. It can be said that there is a
consensus on the possibility that information technology can speed up the service and
facilitate the use of information, in the search for effective health results. Various
information flows, as in the case of marking specialized procedures, for example, must
become safer, faster and more effective. The decline in the time of medical consultation
is associated with the system already identifying the patient quickly and safely, as well
as making available to the health professional their history. After computerization,
requests for exams and complementary evaluations will be controlled through
procedures in the system performed safely and with a lower error rate. The data for
recording and retrieving data from individuals and the health system itself will obey the
new legislation on the protection of personal data. The integration of the basic network
with government data can be done by connecting the local system to the national base,
which may favor the integration of data between different locations. Scenario
professionals using a computerized system agree that retrieving patient data and
reducing handwriting activity has made the job much easier and greatly reduced the
error rate. Professionals where computerized systems have been adopted consider that
it is easier to register diagnoses coded by the International Classification of
Diseases. As for the facilities provided by data standardization, professionals in the field
perceived the speed to access patient data. Another change is in the vaccine record,
with the system can access all vaccine records, even if the patient's medical record is
lost, or even if some professional fails to record data. 
The expected benefits with computerization would achieve changes in work processes,
facilitate the visibility of all data recorded quickly. In the computerized scenario, the
processing of collective statistical data and the recovery of individual data is made
possible by removing the service statement. At the end, the use of information is related
to the interdisciplinary care process and responsible professional practice, which gives
visibility to the good quality of the service, and more confidence in the uses of
information in epidemiology and action planning. Professionals can start to evaluate
better than the tests that are really needed. The system allows doctors to track all of
their patients' information. The system also favors the exchange of information at
different levels of health care, which may favor greater integration of actions in health
care networks. The with partilhamento data between basic health units and hospitals it
is also a possible contribution system: all that a patient is, the first consultation to
surgery, it is registered. Another possible contribution of the system is the reduction of
the documents to be stored, since exams and several other records will be
digital. Although it is not reasonable to assume that computerization reduces the need
for personnel, it is reasonable to assume that health professionals can optimize their
activities and can devote more time to their core activities. In the operational scope, the
process of computerization of health modifies activities, adds the task of typing
simultaneously to writing, creates a new logic to the user's flow for their demand, and
expands the universe of the professional's performance, characterizing it as
multipurpose. With computerization, the time needed for the doctor to perform the work
activity decreases, as he would no longer need to wait for the answer of test results to
proceed with the process, the need for case documentation and the need for frequent
research to find information. Technological developments have advantages such as
readability, access and automatic data recovery performance. The production of
information in this complex world of health must aggregate concepts and standards, in
order to reduce the repetition and redundancy of data capture, to enable an integrated
information system that meets the needs of the user, the manager and the healthcare
professional. The interface of the programs and the standardization of health
information are decisive for the achievement of systems integration. The use of
information will be as important and routine as the best technology embedded in the
machine represents the reality of the health professional's work. This use is recognized
by the professional at the top when the results of the work facilitate the recovery of
patient histories and the availability of information helps in the management of the
assisted case. The advance exists because the electronic record reduces errors,
standardizes concepts that can be grouped into a set of data, giving visibility to actions
that facilitate diagnosis for management, for monitoring the health care line of
individuals, enable planning and health decision making. Information has a strategic
value for professional practice associated with the results of its use in the planning,
programming and evaluation of services, in improving individual care and attention to
collective health. The quality of the data adds value and gives objectivity to the
knowledge of the health situation, the epidemiological picture that will serve as a
strategic input for the intervention in a population. It is necessary to recognize that
technology has a special importance in the health process, so that it transforms and
rearranges, determining new innovations to the professional's approach to care,
developing a virtuous circle of innovations. The use of health information technology
increases the responsibility of professionals, improves the notification of diseases under
surveillance, allowing less time for investigation and intervention in reality. The
automatic extraction of reports releases management to the role of management,
control, evaluation, regulation of activities and procedures and to reflect on social
particularities of the described area. The project aims to address important points such
as:

## Control of Epidemias
A standardized patient control system that generates parameterized reports. Send data
that uses the resources of telecommunications, tele location and informatics for
immediate communication of the data generated by a computerized central, patients
and doctors. 
A Database that updates itself with each new data introduced, a system capable of
issuing alarms and exit reports and forwarding them, through telecommunications
systems, to the locations and social instances concerned, advocating public health
attitudes. The system will have the population's epidemic histories and will be able
to monitor the conditions conducive to the outbreak of endemics and the medicalhospital demands and use Artificial Intelligence with the continued processed
episodes, generating an increasing knowledge base about local characteristics of the
people.

## Patient Control
The technology will make it possible to increasingly know the patient and perform health
care in a more complete way, with more relevant information and having the dimension
of which is the history and its trends. Thus, the best for the individual is that this
information is increasingly available to the health unit that provides the attention to know
what the person's history and what they may have. This patient begins to know what is
going on with him and what types of decisions or attitudes he can make. D democratize
and bring to the patient some kind of value, information or form of
support. The information starts to flow and the whole system is unified. The goal is
to create a great platform in the health sector where it is possible to have all the
information connected and a holistic view of the individual with all links in the health
chain integrated. The health information is the individual, it only allows you to use that
information within the platform. We respect all national and international standards
aimed at information security and confidentiality. We also work with a secure
technological base. Our vision is that the more the user shares his information so that
more population indicators and information, the better and more grounded the
population health management strategies, protocols and other issues related to
prevention and treatment will be. The patient must share his information in order to work
in a very careful and positive way for the development of policies and actions. Any
sharing, whether with operators, companies or the public system, will be limited to
population indicators, preserving existing individuality and confidentiality.
Control of Vaccination Campaigns
In addition to monitoring all the patient's medical records and enabling the generation
of statistical reports and hospital indicators, this tool also allows the control of
vaccination campaigns such as: organizing vaccination and scheduling campaigns
following the vaccination calendar; control the application of doses; produce reports with
the list of those immunized; assess risk dynamics regarding the occurrence of outbreaks
or epidemics, based on the records; control the stock of vaccines, facilitating
programming, acquisition and distribution; decrease adverse events of post-vaccination
reactions. The system will be linked to the Vaccintion Control allowing: Evaluation of the
Immunization Program Records, by age group, the doses of applied immunobiologicals
and calculates the vaccination coverage, by basic unit, municipality, regional of the
State Department of Health, state and country. Provides information about routine and
campaigns, abandonment rate and sending immunization bulletins. Immunobiologicals
Stock and Distribution that manages the stock and distribution of
immunobiologicals; Post-vaccination Adverse Events that allows the monitoring of
adverse reaction cases that occurred after vaccination and the rapid identification and
location of vaccine batches; Supervision Instrument Evaluation Program is used by
Vaccintion Control supervisors and technical advisors to standardize the evaluation
profile, capable of speeding up the results tabulation; Program for the Evaluation of the
Supervision Instrument in the Vaccination Room is used by the state immunization
coordinators to standardize the evaluation profile, capable of speeding up the results
tabulation; Determination of Immunobiologicals Used, which allows the management of
the doses used and the physical losses to calculate the technical losses from the applied
doses; Information System of the Reference Centers in Special Immunobiologicals that
records the attendances at the public service station and informs the use of special
immunobiologicals and adverse events.
Medical specialist needs control by location
The evidence points out that the lack of doctors in certain contexts involves different
factors, from demographic and epidemiological aspects of the population, through
financing and public-private relations in the health system, to the remuneration, career
and working conditions of professionals. It is necessary to seek solutions to the
structural inequalities that persist, both in the supply of doctors and in the access of
citizens to health services and actions. Health needs must be the main marker for the
reorganization of health care models and systems and their estimation must
permanently challenge health managers, councils and workers, entities representing
professionals and patients, and civil society in general, in the construction of
progressive consensus on the organization of the health system and the services it must
provide.
More reliable and secure data and in accordance with the new personal data
protection law
One should not lose sight of the fact that health information is the mainstay for the
management of services, as it guides the implementation, monitoring and evaluation of
health care models and of disease prevention and control actions. System
managers are also interested in articulating with the various bodies that produce them,
in order to complement and establish a regular flow of information at each level of the
health sector. Timeliness, timeliness, availability and coverage are characteristics that
determine the quality of the information, fundamental for the entire System to present
good performance. They depend on the conception presented by the Information
System, and their sensitivity to capture, as early as possible, the changes that may
occur in the morbidity and mortality profile of an area, and also on the organization and
coverage of the activities carried out by epidemiological surveillance. In summary, an
information system must provide the necessary support so that the planning, decisions
and actions of managers, at a given decision level (municipal, state and federal), are
not based on subjective data, outdated knowledge or conjecture. The system is made
up of several subsystems and its general purpose to facilitate the formulation and
evaluation of policies, plans and health programs, supporting the process of decision
making. To this end, it must have the technical and professional requirements
necessary to plan, coordinate and supervise activities related to the collection,
registration, processing, analysis, presentation and dissemination of data and
generation of information. One of its basic objectives is to make it possible to analyze
the health situation at the local level using homogeneous micro-regions as a reference
and, necessarily, considering the population's living conditions in determining the
health-disease process. The local level, then, has responsibility not only with feeding
the health information system, but also with its organization and management. In this
way, another aspect of particular importance is the design of the information system,
which must be hierarchical and whose upward flow of data occurs inversely proportional
to the geographical aggregation, that is, at the local level it is necessary to have, for the
analyzes epidemiological studies, with a greater number of variables. Fortunately, the
current resources of electronic processing are being widely used by health information
systems, increasing their efficiency as they make it possible to obtain and process an
increasing volume of data, in addition to allowing the articulation between different
subsystems.
More objective targeting of public health policy
There is a consensus that the Unified Health System represents a major advance in
terms of public policies, with health being a sector with clear proposals and practices
for social control, administrative transparency and participatory management. Although
advanced in its guiding principles, the Unified Health System still maintains, in its model
of care, a perspective strongly guided by the fundamentals of biomedicine, which will
hinder its long-term sustainability, from a financial point of view. In this sense, health
promotion presents itself as a concrete possibility of changing the health agenda both
to strengthen and to support its consolidation. 
Given the above, it is understood that decentralization aims at strengthening the health
region to co - responsibility of the government in the deployment and implementation in
local and regional healthcare system with a view to improving people's quality of
life. However, the conditions for decentralization to guarantee universal access to health
actions and services and comprehensive care according to the needs and demands of
the population are not guaranteed, with contradictory results in the national territory. As
a result of some countries heterogeneity, the change in resource allocation resulting
from the implementation of decentralization has not been sufficient to change the
pattern of inequality in access to health goods and services. In the
process, governments to see on the task of managing a network of heterogeneous
services en will be integrated institutionally and insufficient supply of services on
average complexidad and.
Faster reaction to public health emergencies
In order to act in a timely manner in these situations, the health sector must organize
itself to ensure adequate preparation and continuity of services during a public health
emergency. For that, the previous systematization of the work process, makes it
possible to establish the ability to maintain the development of health care surveillance
actions. In this sense, it is essential that, in the System, actions are developed to
strengthen the capacity to act in public health emergencies. Structures aimed at
detecting and responding to public health emergencies are units that have the following
functions: continuous analysis of health problems that may constitute public health
emergencies for the issuance of a “warning sign”; management and coordination of
actions developed in emergency situations, being considered fundamental for coping
with epidemics and pandemics. The information received comes from notifications
generated in the system by doctors, patients or public agents. Unofficial sources are
also accessed and analyzed, namely: information published in the main media,
Promed, websites of national and international health organizations, notifications from
the population (rumors), among others. Among these initiatives, the following stand out:
the decentralization of the execution of actions, the use of evaluation indicators, the
institutionalization of the practice of using the tool in planning and decision-making, the
progressive expansion of the scope of the epidemiological surveillance; ongoing
process of integrating surveillance (health, epidemiological, environmental, worker
health) at the three levels of government; integration with primary care; structuring the
national network of public health laboratories; improvement of risk communication
strategies; mobilization and articulation of health services with the country's teaching
and research institutions.
Doctors with access to the entire health history and with more accurate patient
information including emergency care
The emergency represents a threatening, sudden situation that requires immediate
corrective and defense measures. It also means accident and urgent urgent need,
which must be done quickly. In an emergency, patients are often taken against their will,
refusing standard medical care. They can often be disturbed in their mental state,
whether due to a psychiatric problem, an illness or even intoxication. The doctors who
work there have very little time to access the reasoning capacity, or the competence of
the patient to make decisions that protect their health, and have to make quick
decisions, without the benefit of being able to consult the ethics committees, for
example. Example. In many places, there is pre-hospital care, in which non-medical
personnel work and doctors are also responsible for the decisions of these people and
authorize measures, without directly seeing patients. Associated with all this, there are
added the problems caused by an imperfect health system, which ends up being better
demonstrated in an emergency sector, hampered by poor working conditions, of being
able to provide adequate care. 
The gateway to a health system is made either through primary care at the level of
health centers, offices or through the emergency, when, suddenly, for many reasons,
we need the most immediate attention possible, otherwise we risk having our lives really
changed. It is for this reason that in the emergency situation there is a real obligation of
the State to provide and ensure this type of assistance, which is totally independent of
the ideological issue, because someone unconscious does not have the capacity and
the competence to determine their destiny and society. As a whole must ensure
through d the state care appropriate to the citizen. Access to the emergency sector is
an individual right for everyone, and we must strive in every way to remove barriers that
prevent such access. The right to emergency is equal to the right to life. Society as a
whole must become aware of this right in order to ensure a right that extends from the
pre-hospital, hospital, outpatient follow-up and rehabilitation phases. The prehospital
phase is an extension of the emergency sector within the community. Patients must
have prompt access to trained personnel so that they can be seen and properly
transported to hospitals where they can receive the correct care. Access to these
services cannot be limited. At that moment, the patient may be in a situation that cannot
decide to release the data or have a family member nearby who can decide for him. In
addition, the patient has difficulty maintaining a confidential relationship in an open
environment in which doctors, nurses, patients, security, police, rescuers
and medical technicians interact simultaneously. In this case, the responsible physician
can use a master password to access the patient's data, linking his ID to the care
provided. After assistance, the patient or family member can guarantee the procedures,
thus releasing the doctor's ID in the emergency that occurred. The corresponding
governmental area and all those other people who are in some way interested in
maintaining the health of the population must participate in a managerial way. We have,
therefore, people who will certainly seek to find the best solutions for a health
system. They will have a deliberative function and, if this works, at the level of each
government, that is, at the municipal, state and federal levels, we will finally
have tools that will facilitate the use of resources so that decisions in the area of the
budget really reach health. This is the way that civilized countries use their health
systems to function, and all with a certain priority for emergencies. The doctor-patient
relationship begins when the patient literally enters the system. Initial contact is usually
made by hospital staff at a screening desk, in a waiting room. Sometimes the patient
can even choose his doctor, but it is not the most common. Ideally, this first interview
should be carried out by a person from the health area and, in this case, a nurse
specialized in emergency care who, in the form of a pre- consultation, could raise the
basic data, the history, the main complaints and the fundamental vital data. With that
she could, in a summary judgment, give priority or not to attendance. The order here is
that the most serious cases will be dealt with first, but all will be dealt with. In
this pre- consultation, it is noticed that the patient's accurate
and updated information is also a priority. The other form of entry is when it is brought
by ambulance, having been attended by medical and first aid personnel from
the pre- hospital care system. At that moment, an easier relationship starts because this
entrance to the hospital is already direct to the medical sector, since it has already
started the pre- consultation phase and in part already of consultation, which facilitates
communication with the hospital in a more or less critical situation. With patient
information available quickly and updated, the hospital itself can now prepare for
care. The doctor must also be aware of the cases in which there is a risk of life or serious
urgent functional loss where the doctor has the authority and competence to
act. Consent for treatment must be obtained from the patient or the person who
represents him / her legally, so under less urgent conditions the physician must
endeavor to obtain parental consent. Finally, we can draw some conclusions about
medical responsibility in the emergency. Those doctors who work in the sector have an
obligation to give the best of their technical attention to all patients who seek this
sector. And the institution that maintains it has an obligation to provide him directly or
indirectly with accurate, reliable, up-to-date and secure information for his quality of
care, requiring the sponsoring organizations to provide the resources; that they
correspond to the needs, maintaining control systems for this in all areas. 
Patients with updated and accessible health history when they need medical
attention
The updated medical history is common to children. When he was born, in what way, diseases
and allergies that he presented in early childhood, vaccines, medications and growth curve are
some data that mothers usually have on the tip of the tongue, along with the tests already done
and that can be requested by the doctor. As people grow, however, this monitoring is lost and
the information is inaccurate. Having an updated medical history helps a lot in medical
appointments, especially when the doctor is faced with the diagnosis of a more serious disease,
in which it is necessary to do an investigation about what happened to the patient and,
sometimes, even if there are cases in the family. Medical history is essential for a
consultation. When there is no such record, the doctor does it on the spot. It also helps the
patient to be prepared, with information about medications in use, illnesses in the family and
symptoms. In this way, the doctor can devote more time to investigating the person's current
complaints. Today, there is no integrated health system, in which all this information is available
to doctors. This history is made independently by each doctor or hospital at a consultation of the
person. As a result, duplicate or unnecessary tests are often requested, or even the doctor
consulted is not the most suitable specialist for the problem presented. With the hustle and
bustle of everyday life it is difficult to have this history in memory, which tends to fail or be
inaccurate when it is most needed. Therefore, keeping a file with medical information, which can
be digital or even a notebook, can make the person have a more satisfactory consultation. You
can use any form of storage, from the physical filing of records or use modern technological
tools such as digitalization of data. The patient's historical record helps the doctor to have a
more comprehensive understanding, in addition to being able to understand his current
situation. The doctor's role has also changed a lot in recent years, with care being more
sectorized by areas of the body, when before there was a more comprehensive view of the
patient by a family doctor, who knew the history of diseases and followed the person throughout
life. With the evolution of medicine and a greater knowledge and specialization of doctors, this
central figure practically ceased to exist, causing the patient to have to manage all this
information more closely. The ideal model would be the balanced action of a clinical physician,
who would function as the case manager, advised / assisted by the specialists. This would
decrease conflicting opinions and improve the interaction between the patient, his illness and
his doctors. To have a system that centralizes the information the patient now has a a tool that
analyzes the problem globally since it does not always a headache, for example, is related to a
neurological problem. The doctor should not be contacted only at the time of the disease, but
mainly in the prevention of it. The general practitioner is the specialist indicated for adult
monitoring, focusing information and having a complete view of the patient, triggering and having
as collaborators experts whenever n ecessário .

## Electronic Health Record Integrated with the System
When we imagine the possibility of having all medical information, or in an even more holistic
way, of anyone's health, available to doctors and other health promoters at any time and
anywhere, we realize that the opportunity rarely translates in real options due to
several difficulties related to its implementation. The electronic medical record t in three
categories or systems: basic, no clinical notes; basic, with clinical notes; and advanced, in an
integrated way. Therefore, it appears that there is a great difficulty in adopting a very welcome
tool. On the other hand, it has already been demonstrated that several of the systems and
functionalities required for the formation of a true system are already adopted and used in many
health units, without, however, there being an interaction between them. The biggest difficulties
for the adoption of an integrated system are: maintenance cost and specialized team. In this
project we eliminate all obstacles because the solution provided already has the appropriate
team and maintenance can be easily done by any qualified IT team. Another major difficulty
highlighted would be the interaction of information between different terminals, such as
hospitals, clinics, laboratories and medical and other health professionals' offices. This can be
eliminated using a mobile application or standard web system for all platforms. There are few
examples in the world to be followed that demonstrate the feasibility and advantages of adopting
such systems. In the United States, the network connected to the VHA
(Veterans Health Administration) has an implementation rate of an advanced system four times
higher than the average of the country, noting an impact signifi captive n the quality of clinical
practice. Some countries such as the United Kingdom and the Netherlands have a high level of
adoption of health information technology, mainly in outpatient care. The physician's electronic
signature is recognized in the hospitalization, discharge and prescription documents, inserted in
the electronic medical record. 
The medical record is defined as a single document, consisting of information, signs and images
recorded from facts, events and situations about the patient's health and the assistance provided
to him, with a legal, confidential and scientific character, used to enable both the communication
between the members of a multiprofessional team and the continuity of care provided to the
individual. Paper records must be kept for a period of 20 years after the last record or the
patient's death. In addition, there are very specific and inhospitable rules for disposing of medical
records, which makes this task unattractive. Therefore, we can imagine what this means in
quantitative and qualitative terms with respect to the archiving of so much information. The paper
model has been replaced by system computerized. To sign it, the doctor must have
a digital certification, which is his signature and identity in the virtual world, equivalent to the
registration number with the traditional Regional Council of Medicine. And iff project was
conceived ed that experience was acquired knowledge about the benefits of electronic medical
records, such as readability of reports tions, access various profi ssionais in places and different
times or not, sustainability and environmental issues, and especially secret and
confi ability. The digital signature is more secure, as it is easier to tamper with a stamp than an
encrypted code. The system can be even more productive with the implantation of the
GOVERNMENT DATA APP. If the way of storing patient data is standardized, the information
can be consulted at any hospital. Some institutions serve as an example of partial
implementation, with great advances, however, still dependent on the medical record. There
may also be an integration between a Hospital Information System, which stores administrative
and clinical information, and a system for transmission, archiving, retrieval, processing and
visualization of medical images. The major challenge in the full adoption of system, through the
scrutiny of doctors, is the credibility of integrated systems. Credibility implies the concern with
ethical issues of secrecy and confidentiality, in addition to the legal violation, intrinsic to medical
records. The confidentiality of information is a right of every citizen, which guarantees the
inviolability of intimacy, private life, image and honor of people. This duty to preserve secrecy is
provided, and in most codes of professional health ethics. Medical Ethics imposes secrecy as
a fundamental principle for the practice of medicine. It contains obligations with
professional secrecy. There are: the physician's duty to guide his assistants and ensure that
everyone respects professional secrecy, and also the physician's prohibition on facilitating
access to medical records by people who are not. They are bound by professional secrecy. This
is solved by the project presenting because only the patient's consent can authorize the
disclosure of the contents of the medical record, through a password authorized by the mobile
phone aplication. The patient would decide what information he wants to keep to himself and
what he wants to reveal. However, there is a caveat about such disclosure, which can be made
“for just cause, legal duty or express authorization of the patient”. Not only doctors, but
also nurses and other health professionals, as well as all administrative employees who come
into contact with the patient's information as a duty, are authorized to access it only according
to their professional needs. Therefore, the duty of secrecy is not limited to the doctor, but to all
those who, due to their profession, have access to these data. Q uanto the signing and letrônica,
certifi digital cation and other issues of "credibility", it seems that the good experiences will
promote one of the greatest revolutions related to patient care, and enable the use of information
for pedagog use single and scientific. We believe that the first steps towards the future of the
patient's electronic medical record have been very promising.
Models mathematical and Intelligence Artificial to make projections with greater reliability
The synonym for image is the search for knowledge in every detail. Medicine aims to recognize
diseases before they become noticeable through symptoms with the help of tests that use
images. Scientists are convinced that it is in principle possible to track diseases due to the
abnormalities found in the images. The theory behind the concept: if deviations in images are
known as markers, doctors would receive clues as to whether a patient is at risk or not. The
Information Technology operates in medical image processing, which takes into account the
advances in the processes of capturing images and ways of interpreting digital content, where
it is based on Artificial Intelligence techniques. The image is enhanced for human visualization
or for later analysis by the computer and mathematical models are used to assist in the execution
of automated image analysis, and these processes involve merging images together with the
management of images and aggregated information. 
Patient access to your private health insurance information
Medical record is the entire set of data about a particular patient. This medical record is intended
to inform all methods regarding the patient's drug therapy. Medical Ethics expressly prohibits
the possibility of being denied access to the patient to his p rontuário as well as providing copy
when requested by the same, and explanations for understanding of the patient. Deny the
patient access to his medical record, fail to provide him with a copy when requested, as well as
fail to give him explanations necessary for his understanding, except when they cause risks to
the patient or to third parties. The Consumer Protection also deals with the impediment of
information. Prevent or hinder the access of the consumer to the information contained in it in
registers, databases, records and records. Likewise, Medical Ethics provides for punishment for
anyone who prevents access to information. Often the patient leaves the private health plan and
migrates to the government system. As a result, the patient information that is stored in the
private health plan can no longer be accessed by the patient himself.
Data belongs to patients
The medical record comprises not only the record of the patient's anamnesis, but the entire set
of documents and information regarding the medical care provided in favor of a patient. Medical
records are understood not only to record the patient's anamnesis, but also all standardized,
orderly and concise documents, referring to the record of medical care provided and attached
documents. They constitute a true dossier that serves both for the analysis of the evolution of
the disease and for statistical purposes that feed the service's memory and as a defense of the
professional should he be held responsible for some atypical or unwanted result. A set of
ordered and standardized documents for the records of medical care provided by doctors and
other health professionals in public or private health services. Single document consisting of a
set of information, signs and recorded images, generated from facts, events and situations about
the patient's health and the assistance provided to him, of a legal, confidential and scientific
character, which allows communication between members of the multiprofessional team and
the continuity of assistance provided to the individual. The medical record lends itself
fundamentally to some functions, such as demonstrating the quality of care provided to the
patient, clarifying medical information and the clinical decision process, the formulation of clinical
and administrative statistics, in addition to enabling the editing of management reports with the
development of a strategic planning policy that allows the management of ethical-legal
aspects. The documents generated in the emergency room and in the outpatient clinic must be
filed with the medical record, in case of hospitalization. There is no reason to register and file
separately the documents generated in the emergency room, since the care provided in this
sector must be recorded with anamnesis, diagnosis and results of laboratory tests, if performed,
prescribed and performed therapy, as well as the evolution and discharge. In view of the
aforementioned devices, it is clearly inferred that the patient's medical record is a document that
belongs only to him, which is why the disclosure of its content implies a serious violation of the
right to privacy, to the image itself. The obligation to protect the medical record also falls on the
hospital that maintains its custody. In France informs that every patient expects the information
provided to be kept confidential. And it is the hospital that should promote the keeping of this
confidentiality, the use of this information being the dimension of the patient's own
need. Whatever the degree of the server in the hospital, he has the obligation to keep the
contents of the medical record, thus responding legally and disciplinarily for the unauthorized
disclosure of information. Therefore, information that necessarily requires patient identification
can only be provided with your express consent or that of your legal representative, unless the
determination to exhibit comes from law or a judicial request based on just cause. In these
cases, the hospital must demand written authorization from the patient or his legal
representative, when he is incapable, even partially. Disregarding these rights and premises,
some health care plan operators have been demanding that hospitals present the medical report
as a condition for the payment of services provided through the agreement signed, under penalty
of disallowance of the bills, imposing on nosocomios to bear those costs. The reports belong
first to the patient and their information to the attending physician, and as part of the medical
record, they must not be passed on to the company that pays for the medical or hospital service,
since different people, including non-doctors, or even uncompromised with the professional
secrecy, would have information on patients, which should not be disclosed. The confidentiality
of the medical record, as well as any information related to the patient, including about his
examinations and the reports that accompany and integrate him, can only be violated with the
express consent of the patient or his legal representative, or through a judicial request based on
in just cause, as already mentioned. Given these considerations, there is no doubt about the
fact that the medical record, exams, reports and any and all information related to the patient's
health belongs to him only, and not to the doctor or hospital, who only have the duty of custody
of these documents, as mentioned. 
The requirement for any health plan operator to have access to this patient's private information
without the patient's express authorization as a condition for the payment of procedures
performed by the hospital is absurd and illegal. And although there is a provision in the contract
signed between the hospital and the health plan operator in order to provide this information, it
is understood by the abuse of this clause, which deserves to be removed, and by the health
professional's duty to maintain the confidentiality that it must safeguard this information, for the
reasons already listed and the fact that it belongs to third parties unrelated to the hospital-health
insurance operator relationship, and cannot have any effect against them, who do not participate
in this contractual relationship. That said, we have one of the most frequent, if not the most
common, causes of complaints against doctors to the Council. It is related to the lack of simple
and accurate information to patients or their families about the health status or risks of the first
and also about the schedule of proposed medical assistance, including informed consent of the
patient or guardian when necessary. The unclear or overly erudite way in medical terms with
which such information is provided to patients or their families and the consequent failure to
understand it by interested parties, almost always leads to misinterpretations and friction. The
situation is aggravated by the obvious need for more detailed information in serious or complex
cases, where there is great emotional distress from the family and the doctor himself. At the root
of complaints about negligence, there are always questions about the quality, “quantity” and
frequency of information provided by the doctor. The information to which patients and their
families are entitled is both the verbal information of the day-to-day clinical evolution and the
final reports of discharge, transfer or death. In the doctor-patient relationship and especially in
the field of information, linguistic problems must be taken into account. It is easy to understand
that in a country, where citizens of different ethnicities and descendants live and also with great
regional and age variations between doctor and patients, such problems can be aggravated but
certainly can easily be avoided. Patients are also entitled to their complementary exams, even
if they are done at the doctor's office or clinic, such as radiographs, electrocardiograms,
ultrasounds, stress tests, among others. The doctor must provide the patient's reports and
exams and record the results on his medical record. Cabinet or clinical pathology exams
performed in other laboratories should be noted on the clinical record and also returned to the
patient. They must not be withheld, they belong to the patient who may, for whatever reason,
wish to consult another doctor and has this right. All these problems are minimized with the
adoption of consent to the patient's access to his information. In the act of the first contact with
the representative of the health area, he will be able to access the patient's data through his
authorization via application. This would generate a password so that the health representative
can have access to the patient's life history. At the same time, it generates a protocol with data
on who accessed this information and date, location and other necessary information.
Electronic Health Record x Health History
The implementation of electronic registration in health establishments has reflected isolated
solutions, which contribute to the fragmentation of the Unified Health System. The association
of physical and digital records requires a change in institutional culture. The
Electronic Health Record is an important and necessary technological tool for doctors and / or
clinics in order to make the management of patients and all matters related to them agile and
practical. Also known as the Electronic Patient Record, it is a digital version of all the
documentation of the patients attended by a specific health professional, such as medical
history, tests performed, prescription of medicines and among others. From the technological
era that the world is going through, all areas of operation will need to modernize to become even
more attractive, both for current customers and for attracting new consumers. It was no different
with medicine. Currently, the development of new medical solutions like this, seek not only to
serve as a digital storage of data and medical record information, but also seek to optimize care,
reduce expenses and work to attract and retain patients. However, with regard to the end of
paper registration, there is a condition to be met. Only systems that meet the “security
assurance” requirements can destroy these physical documents, as long as they are
digitized. Still, is a degree of information security that requires the use of a certified digital
signature / ID. This means that data can only be kept in its exclusive digital format (replacing
paper), when digitally signed. The good news is that doing this is free today: every PDF
document can be digitally signed with very simple tools, such as Acrobat Reader. The National
Institute of Information Technology offers a free plug- in for Acrobat that allows you to sign any
document. Thus, you can use an electronic medical record system with an adequate level of
security and digitally sign your documents, maintaining their legal validity. In the case of health
professionals and clinics, the digital medical record is an important ally in the optimization of
time, in the organization of information, in the practicality of searching for the patient's history
and in the agility in the insertion of new data.
Thus, with technological improvement, the entire daily work flow is facilitated. Health History are
all electronic medical records plus medical notes, notes of patients in their daily lives that can 
assist in the diagnosis and prognosis of patients when they need an appointment, an emergency
or even telehealth care. The more information doctors can have about their patients, the more
accurate they will be in their decision making.
Planning with AI mathematical modeling
A computer that is a partner of the doctor when diagnosing the patient and that improves with
each exam analyzed. This is not a hypothetical situation or directly taken from the scripts of
science fiction films, but something that has been developed for some years and is already part
of the daily life of some public health units. The name of the method is self-explanatory:
computer-assisted diagnosis, a concept that unites the foundations of Artificial Intelligence (AI)
and machine learning. The figure of the physician remains essential for the assessment of the
patient's health and diagnosis. The system is nothing more than a the tool to the work of medical
professionals. From the information given to the doctor, he through the exams and the system,
it will be decided if the patient has a disease or if he needs new exams. What the systems for
aid to medical diagnosis do is to learn from previous examples, that is, from images with
diagnoses already given. Thus, he applies this knowledge that came from the database and
helps in the recognition of new information, which is the disease that is not yet known, in the
specific exam that the program is analyzing. This is called ' machine learning ', because the
machine is 'learning', with each diagnosis and, through Artificial Intelligence, it becomes able to
identify new cases. The neural network selects the best results from each index to indicate which
settings generate the least consumption, something that is directly linked to efficiency. The
Artificial Intelligence tool is interesting because it learns and removes patterns, suggesting even
more interesting ways out of problems and goals that we encounter on a daily basis.
Database using DATA LAKE methodology
Increases in computer processing power, cloud storage capacity and usage, and network
connectivity are transforming the current data stream into an endless stream of detailed
information about personal customer profiles, sales files, product specifications, processes and
so on. Information arrives in all formats from a variety of sources, including IoT devices, social
networking sites, sales systems and internal collaboration systems. Due to the fact that we are
increasingly accumulating an extensive data set, this has introduced new challenges in the
capture, storage, analysis, research, sharing, transfer, visualization, consultation, updating and
privacy of information. Inevitably, these challenges required a completely new architectural
design and new technologies, which help us to store, analyze and gain insights from these large
and complex data sets. An emerging class of data management holds a significant promise in
this regard: Data Lakes. These storage platforms are designed to store, process and analyze
structured and unstructured information. They are typically used in conjunction with traditional
corporate data warehouses (EDWs), but in general, cost less to operate than EDWs. This is a
result of being able to use accessible and easily obtainable hardware, and because the data
sets do not need to be indexed and prepared for storage at the time of their introduction. The
data is kept in its native formats and reconfigured only when necessary, and as
needed. Relational databases can also be managed as part of a Data Lake platform, but only to
facilitate the ability of end users to access some information searches. Data Lake is not a
revolution in the world of Big Data, a one-size-fits-all solution, but a simple evolutionary step in
data processing, which naturally happened. Date Lake can be defined as centralized storage,
consolidated and persistent raw data, not modeled and unprocessed from multiple sources
without a predefined explicit schema and without me tadados defined externally. This definition
shows one of the main concepts of Data Lake - storage of unchanged data. Traditionally, we try
to filter and structure the data before it enters the Data Warehouse. With Data Lake this is
different. Two things emerge from this - structuring and transforming data on intake has a
performance impact and possible data loss. If we try to do complex calculations on a large
amount of data received, we are likely to have serious performance problems. If we try to
structure data on intake, we may realize later that we need pieces of data discarded during
structuring. The problem is that, with vast and complex data, it is very likely that we do not know
what insights you can extract from them. If we try to guess, there is a good chance of guessing
wrong. The data must be enriched with metadata, describing its origin, time of ingestion, among
others. We can also partition data on intake, which makes processing more efficient
later. Ingesting data in this way does not offer quality guarantees and has no access control. If
we don't really know what's there, we can't set up efficient security around them. All of this will
come later, when the data is processed. Everyone with access to Data Lake will
have unrestricted access to raw data. We can introduce a trivial security system scheme,
allowing selective access to data partitions.
This is a very crude security and may or may not bring any value. Data Lake supports data
acquisition in an agile way, natural storage model for complex and multi- structured data, support 
for efficient non-relational computing and provision of economical storage of large and varied
data sets. We must be able to collect data from different sources, using different protocols, to
store relational and non-relational data, and to offer API for analysis and processing. All of this
must be flexible enough to scale up and down. Data Lake is generally separated into three
layers: ingestion, caching and processing. The intake layer can be further divided into a batch
data acquisition and streaming layer and a message layer. The caching layer is also called the
storage layer. Any of these layers can contain several technologies, each offering
different APIs and functionality. Each application / technology in each of these layers must be
able to benefit from horizontal and vertical scaling and allow fault tolerance to some extent. Each
of these systems must be orchestrated using the resource manager, to provide elasticity in cost,
capacity and fault tolerance. The purpose of the intake layer is to act as a storage layer for raw
data that reaches the Data Lake system. This layer should not force the user to apply the
scheme to the received data, but it can offer this as an option. Support for data partitioning, even
if it is not mandatory, is highly recommended, as we can partition processing data to try to
improve performance when processing it. The purpose of the storage layer caching is to store
temporarily or permanently processed data (or pre - processed), relational or non
- relational. The data stored here is ready for viewing / consumption by external systems or is
prepared for further processing. Applications that reside in the processing layer will take the data
from the processing layer, process it, structure it in some way and store it here,
optionally partitioning it in a certain way. It is common to have a data set, used by data receiving
systems, spread around different storage systems found within the storage layer. The purpose
of the processing layer is to offer one or more platforms for distributed processing and analysis
of large data sets. It can access data stored in the intake and cache layer. Generally, the
technologies found here are implemented using master - worker architecture - master node
analysis data processing algorithms encoded in applications that are submitted to it, create
execution strategy and distribute the workload across multiple work instances, for that can
execute it in parallel. With this type of architecture, the processing layer can be easily scaled to
meet the computing power needs needed for specific use cases. Looking at the previously
declared Data Lake properties, let's define the criteria that the technology stack used to
implement it needs to meet. Scalability. Technologies need to be able to accept a vast and
growing amount of data efficiently. Durability. Data must be persisted securely and data loss
prevention must be supported. Support for ingesting unstructured data. Support for efficient
handling of flow-like data. Support for data deletion, in order to remove unnecessary data or
data that is not allowed to be present, due to privacy / legal concerns. Support for data
updates. Support for different access patterns - random access, search / query languages, batch
readings. Different downstream systems may have different requirements for accessing data,
depending on their use cases. Data Lake is gaining more and more popularity for bringing a new
conception of data storage and processing, adhering to the needs imposed by Big Data and the
volume of data that keeps growing. It is very likely that in the near future Data Lake will be part
of any entity's data infrastructure. There is a lot for entities to take advantage of regarding
Data Lake. Because information is loaded in raw formats rather than pre- configured as they
enter organization systems, they can be used in ways that go beyond basic capture. For
example, data scientists who are not sure what they are looking for can find and access
information quickly, regardless of format. In fact, a well-maintained and managed “raw data
zone” can be a gold mine for data scientists looking to establish an advanced and robust analysis
program. And as entities extend the use of Data Lakes beyond small pilot projects, they are able
to establish self- service options for business users in which they can generate their own data
analysis and reports. Input zone and raw data. At the first level, the Data Lake is built separately
from the structure of IT systems and servers as a purely capture, low-cost and scalable
environment. Data Lake servers, with a thin layer of data management within the technology,
allow raw files to be stored indefinitely before being prepared for use in computing
environments. Organizations can implement the Data Lake with minimal effect on the existing
architecture. Strong management, including rigorous classification of information, is
necessary during this initial phase if we are to avoid creating a swamp of
information. Data science environment. At this next level, organizations should begin to more
actively use the Data Lake as an experimentation platform. Data scientists have quick and easy
access - and can focus more on the ongoing experiments with the information and do their
analysis, instead of focusing only on data collection and acquisition. In this sandbox, they can
work with raw data to build prototypes of analysis programs. They can implement a variety of
open- source and commercial tools while the Data Lake creates the necessary test
cradles. Download to data warehouses. At the next level, Data Lakes are starting to be
integrated into existing EDWs. Taking advantage of the low cost of storage associated with the
Data Lake, can the use data "cold" (rarely used, dormant, inactive). P fear the use of data to
generate insights without forcing or exceed storage limits, or without having to dramatically
increase the size of data warehouses traditional. Mainly, they can maintain intense extraction of
relational data in existing EDWs, which have the ability to manage them. They can also migrate 
low-intensity transformation and extraction tasks to the Data Lake - for example, when data
scientists need to scan databases for queries that are not supported by traditional indexing
structures, such as finding a needle in a haystack. Critical component of data operations. Once
ating gone this operation and development stage, it is very likely that most of the information
that flows through it past the Date Lake. This becomes an important part of the data
infrastructure, replacing existing data marts or operational data stores and allowing for date
provisioning. Businesses can take full advantage of the distributed nature of
Data Lake technology as well as the ability to handle computationally intensive tasks, such as
those required to conduct advanced analysis or implement machine learning programs. We
can decide to design data-intensive applications on the Data Lake - as a performance
management control panel. Or they can use application programming interfaces to seamlessly
combine Data Lake research insights with insights from other applications. The time and skills
necessary for them to make their Date Lakes grow from simple information entry areas to
become critical components of data infrastructure varies according to the objectives
of s entities and its s point s match. At each stage of development, we need to examine important
issues related to the size and variety of data sets, their existing information management
capabilities, the level of expertise in big data in their business units, and to produce knowledge
within the IT organization. Let's consider how a global bank applied principles of agility to
develop a Data Lake. The bank had been struggling with a number of critical data challenges:
low quality of information for business, lack of specialists to manage different data sets arriving
in different formats, aging of data warehouse technologies and many sources of
information. Incoming data sets needed to be structured before entering four layers of the
data warehouse (output, normal form, subject layer and application layer) and before any useful
feedback was generated. In addition to these technical challenges, IT and business leaders
were not working collaboratively. The data was being stored in isolated systems, so critical
business information remained stuck. Requests for access to certain data sets were slow to
respond due to poor coordination and communication between business units and IT
operations. Finally, the Data Lake is an important tool for data storage in the health area.
Telehealth
Many countries guarantees that health is the right of everyone and the duty of the State, with
GOVERNMENT DATA principles based on equity, universality and integrality of health. Even so,
there is great inequality in access to health services, since the great concentration of specialties
is in large centers. With a component of the Strategy eHealth (Digital Health) countries, aims to
expand and improve the network of health services, especially the Primary Health Care, and their
interaction with other levels of attention strengthening Health Care Networks. Many countries
will establish the Guidelines for health care to overcome socioeconomic, cultural and, above all,
geographical barriers, so that health services and information reach the entire population; greater
user satisfaction, higher quality of care and lower cost for public health policies; meet the basic
principles of health care quality: safe, timely, effective, efficient, equitable and patientcentered; reduce queues; reduce time for consultations or specialized diagnoses; avoid
unnecessary travel by patients and health professionals. The three distinct types of telemedicine
services are synchronous, asynchronous and remote monitoring. Synchronous refers to the
delivery of health information in real time. This allows for a live discussion with the patient or
provider to provide medical knowledge. Asynchronous telemedicine refers to the “store and
forward” technique, while a patient or doctor collects medical history reports, images and
pathologies, then sends them to third parties. Finally, remote patient monitoring involves
continuous assessment of the patient's clinical status, either through direct video monitoring of
the patient or by reviewing exams and images collected remotely. New technologies, such as
mobile apps on devices, allow for a wider range of telehealth possibilities. The goal of telehealth
is access to health care, keeping medical expenses under control. One of the most successful
applications of telehealth is to reduce health disparities in areas with limited medical access. The
e-Health to eliminate the transportation costs, which often overwhelm low socioeconomic level of
patients. Through similar mechanisms, it can improve knowledge about health, providing
education to the patient and preventing hospitalizations with the guarantee of adherence to
medication. In addition to improving access, it is estimated that telehealth can save billions for the
health system. The use of technology could reduce referrals, make continuous flow medical
assessments and decrease the burden of some preventable diseases. For example, chronic
illness is responsible for 75% of medical expenses. It is proposed that, by monitoring patients at
home, ensuring adherence to medication by electronic means and providing quick access to a
doctor, the financial burden of hospital readmissions can be reduced. Agility in distance reports
is one of the fastest growing segments of telemedicine today. Today, it is enough to have access
to the internet to, after conducting an exam, send the exam to a patient database.
There, a specialist doctor can make the report of the exam with the patient's permission via
a mobile application. In medicine, some professionals need to do specific tests routinely. In these 
cases, the use of telemedicine speeds up the results and the worker can immediately know what
are the next steps to be taken. Quick access to specialist doctors. Previously, every medical clinic
needed to have a full-time clinical staff available with all specialties. This, in addition to being very
expensive, is a difficulty in some regions. With the help of new technologies and telemedicine,
this is no longer an obligation. The results of the exams can be sent over the internet and the
report is made by medical teams composed of experienced specialists anywhere in the
world. Among the biggest benefits of using telehealth is cost reduction. First, the clinic does not
have to invest in infrastructure for issuing reports, as the documentation center is located
elsewhere. It is also not necessary to keep a full medical staff available full time. In addition, the
unit does not have to bear the storage costs, as all reports are filed in the patient's
database. Increased service capacity. A telemedicine company has full-time support. Therefore,
the results are fast and efficient. What's more, the operations are safe, since the reports are
stored in different locations. Thanks to the agility and safety of the processes, a medical clinic that
has the support of telemedicine has the capacity to improve its services. With the use of
telemedicine, patients and companies that hire the clinic's services are more satisfied. When the
report is delivered quickly, the patient does not have to wait to start treatment, which means time
savings and cost savings. Reduces referrals to specialists. With guidance, he often dispenses
with referrals to a second doctor and ensures an adequate and early conduct. Reduces
unnecessary hospitalizations. This modality has a low cost and requires less communication
infrastructure, as there is the possibility to consult asynchronously (offline) and use simple
systems without the need for high speed internet. The uperation of geographical barriers is
a determining aspect of telehealth is that it allows a patient from the interior of the country to be
treated by the same professionals in the health field. Even though a place has greater
infrastructure, digital service allows people who live in remote areas or with less infrastructure to
access good health services, overcoming territorial barriers that determined the chances of
recovery and treatment, one of the challenges being guarantee access to medical services mainly
in sparsely populated regions, such as inland, rural regions, indigenous tribes, among other
places. Taking into account the same example presented above, the model enables the
universalization of health services, including both medical care, evaluation of exams, procedures
and continuous monitoring. The technologies make it possible for all people to receive specialized
medical care, making the universalization of services a closer objective. In general, these places
receive general practitioners, making it difficult for specialists such as gynecologists, cardiologists,
neurologists, among others. In this sense, The concentration of professionals in certain regions
of the country limits the availability and quality of medical services in others. One of the challenges
has always been the qualification of professionals, as many nurses, managers, radiologists,
attendants and even doctors are unable to travel to make updates and training. With telehealth
focused on tele-education, the dissemination of knowledge becomes possible, promoting courses
and updates that enable the advancement and innovation of medical services regardless of
regional limitations. Thus, telehealth has been a key element to improve and expand access to
healthl, ensuring more satisfaction for medical professionals and also patients. Through
telehealth, specialized professionals can perform these services to ensure more quality in
diagnosis and treatment, in addition to patient monitoring. The optimization of resources is one of
the aspects that have always been decisive in the medical field is the availability of
resources. Telehealth, however, is favorable to a policy of resource contingency, as it allows the
optimization of care and the relationship between doctor and patient, facilitating, for example, the
prevention of diseases. For the reduction of costs to be possible, universal access to health is a
determinant that services can be cheaper. The technology helps to reduce travel costs, idle
infrastructure and waste of inputs. By cheapening the costs of accessing medical services, such
as through specialized partners in each type of demand, it allows more patients to use a
specialized and highly qualified service without paying extra for it. Services is another problem is
the concentration of investments in some places to the detriment of others, also attracting the
most qualified professionals. Thus, both doctors and managers are concentrated in these regions,
causing other parts of the country to have a shortage of qualified professionals to carry out the
efficient management of health resources. Telehealth promotes this articulation between areas,
facilitating health management and also the qualification of professionals located in remote
regions, which allows even the most needy and susceptible areas to benefit from these
exchanges. Thinking about the challenges to improve medical services, some of the benefits of
telehealth stand out and justify public and private investments in the model. Due to its countless
benefits, telehealth has been increasingly used by those who wish to optimize time and improve
the quality of care. However, it is necessary to have greater clinical acceptance to introduce this
innovation in the daily routine of medical practice and to train professionals to use it. The
pandemic of the new Corona virus brought the deserved highlight to the work of health
professionals. In addition, it reveals the need to implement technological innovations to improve
care and increase safety for doctors and patients. 
This is the time to accelerate the preparation for the technological transformation proposed, on
an emergency basis. The benefits of the Telehealth program are numerous.

## Teleconsultation
With teleconsultation, the exchange of information between doctor, patient and other health
professionals is facilitated. It can also be especially useful for clinics and hospitals in remote
areas. Teleconsultation is a type of medical consultation performed at a distance, with the help of
technology. That is, in teleconsultation, doctor, patient and other health professionals are not in
the same place. Medical specialties such as radiology, dermatology, pneumology, psychology
and neurology can benefit from this modality. Remote service is possible thanks to the use of the
internet, applications and online platforms. Some services also consider their scheduling centers
as a teleconsultation. Teleconsultation can be carried out between a doctor and a patient or
between a doctor and another health professional, in order to clarify doubts. When a professional
asks a specialist for guidance regarding the diagnosis or test results, this act is also called second
opinion or teleconsulting. In this world scenario, teleconsultation is not only essential to keep
patients, especially those in risk groups, protected at home, but it helps to relieve the health
system. Online consultation also expands the offer of specialists to communities in remote areas
that lack these professionals. The application of the term teleconsultation is sometimes made in
the wrong way among health institutions in the country. There are some that advertise the service
as being the easy scheduling of consultations over the phone, in which a processing center
coordinates the distribution of vacant hours, or even through shared online schedules. The
teleconsultation is the possibility of performing a medical consultation remotely through secure
online communication technologies such as video conferencing and video calling applications
using computers the u smartphones to function. Considering the interaction between the parties
involved, the teleconsultation can be synchronous or asynchronous. The synchronous form
indicates immediate service, with questions being asked and answered in real time. For this, it is
necessary to have a system, application or platform that allows video, audio or instant messaging
to be carried out. Asynchronous form refers to the service performed at different times, using
technology that allows questions and answers to be sent in a few hours or days. This format is
usually used when there is no urgency for answers, or even in situations that do not require direct
interaction. In the case of consultation between doctors and patients, the great advantage is that
travel is not necessary. The impact of this reflects for patients with reduced mobility, debilitated
or who live in small towns in the countryside, far from the reference units. With teleconsultation,
then, these people would no longer have to travel long distances to talk to a specialist. This is due
to the pandemic by the new corona virus, which can lead to a sudden increase in hospital
demand, and the consequent collapse of the health system. Teleconsultation, in this sense,
increases the scope of doctors and facilitates mass consultation. Another benefit of
teleconsultation is the democratization of the service, making it possible to serve in several cities,
even very small ones. Most of them, mainly specialists, are concentrated in large cities, which
makes assistance to smaller municipalities difficult. The main reason is the lack of
demand. Imagine, for example, an oncologist: although the demand for your services can occur
in any city, its frequency is much less where there are fewer people. Therefore, the permanence
of this professional in very small cities is not viable. On the other hand, in some metropolises the
number of specialists is already saturated. This means that there is demand on both sides, but
physical logistics make the doctor's work unfeasible. With teleconsultation, however, this same
oncologist is able to meet small demands from several cities. This relieves large centers, takes
care where it was not previously possible and generates more jobs, both in the public and private
sectors. With teleconsultation, it is possible to have a specialized service without leaving the
place. In some places there is medical assistance, however, with professionals who are not
specialized or are used to certain situations. In these cases, there are two options to follow: opt
for more general care or try a consultation with a specialist who is often distant or charges
more. With teleconsultation, it is possible to have this specialized service without leaving your
seat. In addition, the technology allows the discussion of several professionals in the same case,
increasing the focus on the patient. It is possible, therefore, to guarantee a higher quality, multiprofessional and patient-centered service. In the teleconsultation, it is possible to ensure that only
the doctors and professionals involved in the process receive the patient's data, through
encryption and the patient's approval to release their data to a doctor or health professional. At
the beginning of the dissemination of telemedicine, it was believed that data security would be a
negative point of this new technology. After all, the risk of leaking information about patients
is less with this technology because it needs the patient's consent to use their data. With the latest
end-to-end encryption technologies, it is possible to ensure that only doctors and professionals
involved in the process receive patient data with endorsement. In this method, the data is
incomprehensible throughout the intermediate path, requiring a “key” to be deciphered. 
This key exists only on the computer of the receiving doctor and the patient's application. While
there is data loss risks, they are very small, smaller even than the risk of leakage existing data on
the physical care. In this traditional modality, there is a danger of loss of medical records, loss of
exams or exchange of information. With teleconsultation, human errors involved in the process
are minimized, since a system strictly controls the accuracy of the data. In general, it can be done
in the following ways: Among doctors, when a general practitioner seeks assistance from a
specialist, such as a second opinion in the diagnosis, a more suitable medication, or even
guidance on how to perform a procedure. The patient may or may not be present; and mong
doctor and patient, directly, without the mediation of another physician or health
professional; s synchronous, the interaction is immediate or the response is provided in a short
period of time. An example is the video consultation between doctor and patient; happens at
different times and does not require direct interaction between the patient and the doctor. Distance
consultations can be initial, first attendance, follow-up, urgency or supervision, with the exchange
of experiences between professionals, and they range from primary care and nursing to different
medical specialties. Among the advantages of teleconsultation, we can highlight the extension of
the medical service for patients from geographic regions that are difficult to access or with difficulty
in locomotion and the greater precision of diagnoses, since the cases can be discussed with
several specialists, mainly in hospitals that do not have them. In its clinical staff specialties such
as cardiology and neurology. Other points that weigh in favor of teleconsultation are the
optimization of time and costs, both for doctors and for patients, since the service does not require
travel and the demands can be solved more quickly; and information security, since medical data,
stored and distributed within the security and interoperability standards already defined for the
country, have a much higher degree of privacy than physical records. In summary, we highlight
the following benefits: Reducing distances: access to specialist doctors, even if the patient is in
remote regions; d more accurate iagnósticos: doctors can get a second opinion and exchange
cognitiv ent with other specialists; the ability to treat the patient; r reduction of operating costs in
clinics; s information security: storage within the standards defined by country. To perform the
teleconsultation, the medical clinic needs a system with the latest technology that guarantees the
security of the data transferred between health professionals and between patient and doctor, in
addition to the safe storage of this information. During the pandemic of the new corona virus, for
example, teleconsultation facilitates the access of patients to doctors specialized in virology. The
proposal through this application is to prevent patients with symptoms compatible with the new
corona virus and other pathologies from having to seek emergency services for consultations
when there is no need. In addition to protecting them, preventing them from being exposed to
areas of greater risk of contamination, the service expedites the assistance to a specialist if
necessary, as the patient already leaves with the medical referral.

## Cost reduction
The use of the digital environment is one of the main cost reducers today. Tele- consultations
are no different: Inter-consultations with specialists, who would have been very expensive before,
can be cheapened with technology. After all, there will be multiple professionals available, forcing
the price of consultations down. However, contractors are not the only ones who save on
teleconsultations. Today, many doctors choose to work in several cities at the same time,
maximizing their financial gains. This generates expenses with transportation, accommodation
and food during the trip, reducing part of their profits. With teleconsultations, however, these same
doctors can occupy their workload without worrying about the costs intrinsic to travel. With that,
both they and the patients save, in the end. Although restricted, teleconsultation has been used
successfully by public and private services in the country. The need to improve care in primary
care motivated the public service to create an initiative to regulate telehealth, and, consequently,
teleconsulting. In order to carry out teleconsulting, the nuclei must have professionals capable of
clarifying doubts about management, conduct and clinical procedures, health actions and issues
related to the work process. Through the second opinion provided by specialists from the
telemedicine company, clinicians and other professionals can offer more accurate diagnoses. The
second opinion also applies to the interpretation of exams. With the support of telemedicine,
health establishments also gain a reinforcement in the issuance of reports, which can be done
remotely. It is enough for a doctor or trained technician to perform the exams with a digital device
and share the data via the telemedicine platform. Then, qualified specialists analyze the clinical
suspicion, examination and patient information and record their conclusions in the online
report. The document is digitally signed and available on the same platform. This entire process
takes a few minutes, giving agility and reliability to the reports. 

## Teleconsulting
The teleconsulting is considered a great innovation technology with the potential to increase and
strengthen access. In addition, it reduces the expenses of the health system with referrals to other
levels of care and unnecessary exams, based on assistance with the best conduct for each
patient. The guidance provided by tele consultants is based on the best possible evidence and
the choice of the specialist to be consulted is in accordance with tele
regulation. The Teleconsulting is a registered and consultation conducted among workers,
professionals and managers in the health field, with the means of two-way telecommunication
instruments. In general, this consultation aims to answer questions about actions, procedures and
routine issues during the work of health professionals. This is what happens, for example, when
a nurse requests the help of a dermatologist in order to choose the best treatment for a patient
who has suffered a chemical burn. Another classic example is when a doctor asks a specialist for
help in the face of altered results of a laboratory test or diagnostic imaging test. Often, this
guidance does not require referral to a second doctor, streamlining the appropriate therapeutic
approach. According to the purpose, we can classify teleconsulting into four types: Clinical
Teleconsulting: the most common modality, it serves to solve doubts about conducts and
procedures in primary care ; Teleconsulting of the Work / Management Process: support provided
by specialists in collective health or family health, which elucidate questions about the
organization of tasks in primary care; Teleconsulting with referral intention: its purpose is to
confirm, or not, the need to refer to a reference specialty; Teleconsulting for requesting reading /
learning material: requesting support material for the development of activities of
interest. According to the document, this service can be offered synchronously or
asynchronously. The most common modality is asynchronous, in which questions are sent via
email, application, chat or any other remote answering system. The synchronous mode
corresponds to conversations in real time, usually via teleconference or video conference. This
format is usually requested only for emergencies or serious cases, in which time interferes with
the diagnosis and sequels left by a disease. An example is stroke (stroke). Every minute the
patient does not receive appropriate care, the chances of death and sequelae
increase. Teleconsulting adds a series of advantages for patients, doctors, professionals and
health units. Counting on the help of colleagues who are geographically distant gives more
security for decision making by doctors. Through teleconsulting, they can expand knowledge,
discuss cases and elucidate clinical hypotheses. They also reduce the need for referral to
specialists, as many cases can be resolved in primary care. Even when this does not happen,
teleconsulting offers risk classification, prior ordering of exams and shared management,
improving the quality of referrals. Clinics and hospitals reduce travel costs and daily expenses,
bringing together professionals via tele or videoconferences. In addition, they gain the support of
specialists, raising the quality of services provided by managers and primary care teams. Thus,
the number of referrals to specialists and the wait for these calls decreases, while care
improves. With greater agility in the service, patients are more satisfied, benefiting the institutional
image of health facilities. The patients benefit from better services, resulting in more assertive
treatments, fewer hospitalizations and shorter recovery time. Teleconsulting provides the
construction of faster protocols, reducing queues and clarifying doubts with agility. Patients and
companions also save time and money, as they resolve most requests for primary health care
services.

## Telediagnosis
Autonomous service that uses Information and Communication Technologies (ICTs) to carry out
diagnostic support services, such as evaluation of remote exams. This is an example of facilitating
access to specialized services. Thus, it aims to reduce the time of diagnosis to avoid predictable
complications, performing early interventions. It seeks to reduce the time of diagnosis by enabling
treatment for predictable complications through early diagnosis. The telediagnosis service was
developed to perform remote diagnostics, and was defined by the Ministry of Health as a
service that uses information and communication technologies to perform diagnostic support
services across geographical and temporal distances. P rincipalmente, a higher quality of life
for the patient, as it will not be necessary to perform locomotion to health centers in other
municipalities. The results will be available online, accessible to the patient. Different diagnostic
tests in the health field can use information and communication technologies, depending on the
transmission of biological signals, such as electrical signals and medical or radiological
images. The main advantage of using telediagnosis is in improving access, especially for
residents from places far from large urban centers, to diagnostic methods essential to health
care. The decisive participation of technology to increase the population's access to important
exams, sometimes even with increased quality. With telediagnosis, diseases, injuries and even
tumors can be identified early and correctly, contributing to the success of treatment. That is why
it is present in several clinics, hospitals and offices, whether private or members of the Unified
Health System. Telediagnosis consists of the evaluation of medical examinations at a distance, 
carried out with the support of information and communication technologies. Therefore, it is not a
matter of carrying out any method of clinical analysis or investigation of diseases without the
presence of a health professional. Due to its characteristics, telediagnosis represents an advance
against geographic and structural barriers, guaranteeing greater population access to different
health tests. According to the legislation, telediagnosis is the autonomous service that uses
information and communication technologies to carry out diagnostic support services, across
geographical and temporal distances. Telediagnosis is not as new or futuristic as you might
think. One of his first reports dates from 1974, having been conducted by one of the most
reputable hospitals in the world, Massachusetts General Hospital, in partnership with Harvard
University. Doctors noted that, although there was great variability among patients, complaints
used to be repeated with great frequency. Therefore, in most cases, the diagnosis made at a
distance was consistent with the clinical diagnosis. In those years, it was observed that vital data,
examinations and clinical interviews could be transmitted remotely quickly and effectively. At the
end of the study, 96.5% of the clinicians who attended in person considered telediagnosis as a
satisfactory tool. Today, we have taken this concept to a new level. New telediagnostic
technologies allow even greater data security, image definition and interaction between doctors. If
telediagnosis was previously viewed with suspicion, today it is seen as a powerful
ally. Telediagnosis, in turn, is the arm of telemedicine that allows medical evaluations and health
investigations based on the observation of images generated in exams, together with the patient's
clinical information. Like any other service provided at a distance, telediagnosis has evolved, and
continues to evolve, as health technologies advance. For this reason, today, telediagnosis has
high resolution images, thanks to a combination of digital devices and modern software. Thus,
specialists interpret quality images, favoring a reliable and safe diagnosis. It is worth mentioning
that the reports produced at a distance are digitally signed by the responsible specialist. Also, the
sharing of the patient's health information occurs only through telemedicine platforms, which are
accessed only through login and password, and with the authorization of the patient, which are
supported by legislation. The information collected during the exams are also stored securely
n the system database, also can is r stored in the cloud, eliminating the risk of loss or
misplacement of results on paper. The most common distrust in relation to telediagnosis concerns
security. Today, however, telediagnosis uses end-to-end encryption technology. In it, the exams
are sent completely encrypted and can only be “deciphered” by the recipient's computer. Thus,
even if there is an interception in the middle of the path, the exam cannot be read. The q uality of
diagnosis is another very common issue is related to the training of professionals working
remotely. They are, in fact, chosen carefully, given the sheer volume of exams they receive. The
specialization is the same as that of the professional who reports physically. As his work involves
only graphic interpretation, there is no loss of quality in telediagnosis. The third most raised
question concerns the economy. After all, to hire a telediagnosis service, you will inevitably have
to hire a professional plan, with specific conditions and fees. It is necessary to take into account,
however, that physical professionals also consume resources. In addition, they include
transportation, food and lodging costs in the final pricing of their services. Therefore, the remote
diagnostics has the potential to still be cheaper than hiring an in - person doctor
to make laud those of the exams. The telediagnosis process is simple and fast. First, the
professional responsible for conducting the image exam, which may be a technician in nursing,
radiology or other disciplines, performs the exam, using digital equipment for this. Combined
with the system, it is capable of storing records in pixels, which are the smallest points in a digital
image. The data collected in the exam is saved in the system database. Visible on the computer
screen, the images are shared via the system and mobile application. From that moment, the
specialist accesses the platform or mobile application, viewing the patient's images and clinical
information. The doctor can then analyze the image and make adjustments, such as zoom or
contrast. After interpreting the data, the specialist records his impressions and conclusions in a
medical report, which is digitally signed. Thus, the remote report can be ready in minutes, in a
much faster process than the conventional one. This document is available to healthcare
professionals and patients in the database. If necessary, the report can be printed. As it adds
agility to examination reports, telediagnosis has been used not only to expand access to these
documents, but also during emergencies. Most common uses: cardiological exams, such as
digital electrocardiogram, holter and ABPM; Electrocardiogram is an exam that monitors the
heartbeat and can help in the diagnosis of diseases and other conditions that can affect the organ,
such as myocardial infarction; the digital Holter, in turn, is a test that uses a compact device,
called a Holter, to extend heart rate records for 24 hours or more; ambulatory blood pressure
monitoring, which is performed over 24 hours; an instrument capable of pointing out hemorrhages,
epilepsy, brain tumors and other neurological pathologies, the electroencephalogram can also
benefit from telediagnosis, it is an exam that shows the electrical activity of the
brain; the polysomnography which reveals patterns and changes in the body during sleep, such
as brain activity and breathing, and apnea obstructive son the; chest X-ray, tomography,
mammography, bone densitometry ; magnetic resonance; ordinary radiography uses X-rays to
obtain images of internal parts of the body; 
computed tomography records images from different angles; mammography is an x-ray of the
breasts; bone densitometry is used in the diagnosis of diseases such as osteoporosis, through
data on the density of bone tissue; the MRI does not use ionizing radiation, but a magnetic field
to harvest high reso images lution of anatomical structures; pulmonary function
test, which evaluates lung capacity, helping to detect diseases such as bronchial asthma
(bronchial inflammation) and Chronic Obstructive Pulmonary Disease, among many
others. Telediagnostic reports can only be signed by specialists in the area of the examination
performed. When the diagnosis is made remotely, these documents are digitally signed. In the
case of X-rays, tomography and mammography, for example, a radiologist will be responsible for
telediagnosis. Sometimes, these doctors also need to have in-depth knowledge about the exam,
such as in the interpretation of the electroencephalogram. EEG diagnoses, whether in person or
remotely, require the signature of a clinical neurophysiologist, or
electroencephalographist. Telediagnosis brings together a series of benefits, both for patients and
for clinics and hospitals that use the service, as the telediagnosis process gives agility to reports,
which can be issued in just 30 minutes. This speed has a very positive impact, not only for urgent
diagnoses, such as heart attacks, but also in case of serious illnesses. Most types of cancer, for
example, are most likely to cure when diagnosis is early. Both the patient and the health units can
save using telediagnosis. This is because, with this service, it is no longer necessary to travel to
reference centers or offices to obtain quality reports. In the case of clinics and hospitals, with
telediagnosis, there is a cost reduction in hiring specialists to cover the entire hours of operation
of the unit. Having specialists from a telemedicine company also helps when healthcare workers
are absent, such as during holidays, holidays and events. In case of doubt in the test results, the
medical teams can count on the expertise of the telemedicine company specialists for a second
opinion. According to the study, Brazil has 452,801 doctors, which means 2.18 doctors per
thousand inhabitants. However, only 39 cities, which have more than 500 thousand inhabitants,
concentrate 60% of the available labor. Away from these areas, access to quality exams and
reports is often time-consuming, as patients need to travel to referral centers. But this scenario is
changing little by little, thanks to the greater offer of telediagnosis in Brazilian municipalities. With
telemedicine, local clinics can train technicians to perform the exams and rely on telediagnosis to
issue reliable reports. The grief of advances in public health, most experts are still concentrated in
the large urban centers. In addition, with the platform, it is possible to cross-check data and
conduct research on the patient's history, which results in greater support for diagnoses. It was
clear that this service has contributed to increase access to quality reports, produced at a
distance, which is advantageous for the patient and health units.

## Tele Monitoring
This tool makes it possible to monitor health and disease parameters remotely under medical
supervision or guidance. Monitoring may include the collection of clinical data, transmission,
processing and handling by a healthcare professional using an electronic system. New forms of
patient monitoring represent a revolution in healthcare provided worldwide. With the support of
increasingly personalized and assertive technologies, doctors, nurses and other health
professionals can reach patients in remote and difficult to reach places, or accompany them in
their homes. This is possible thanks to modern equipment and the rise of specialties, such as
telemedicine, which enhance the means of transmission and sharing of medical information. The
m onitoramento the patient is an accomplished continuously process, which aims at monitoring
the health conditions. For this, a complete monitoring includes three steps. First, data are
collected through devices, anamnesis (interview with the patient), clinical evaluation, laboratory
or diagnostic tests. Then, the data are analyzed and interpreted, leading to conclusions or
hypotheses. Finally, this information serves to support assertive decision-making by health
professionals. Monitoring can be carried out in person, when the patient goes to the health
establishment or is hospitalized in one of the wings of the hospital, or remotely, through calls or
periodic visits and telemonitoring. The choice of data to be collected depends on the patient,
disease or diagnostic hypothesis, whether or not there is a chronic condition. For example, when
monitoring a diabetic person, it is essential to periodically check blood glucose levels. However,
general information is common in most monitoring, especially for inpatients. Temperature, heart
rate, blood pressure, respiratory rate, oxygen levels and other blood gases are some data
evaluated in almost all cases, through measurements (oximetry and blood gas analysis) and
exams, such as the electrocardiogram. Chronic diseases are those that have no cure, but can be
controlled so that the patient has a good quality of life. Most of these pathologies affect the
cardiovascular (heart and blood vessels), respiratory system or originate from the insufficient
production of components necessary for the proper functioning of the organism. Diabetes,
hypertension and chronic obstructive pulmonary disease are examples of chronic
diseases. Individuals who suffer from these ailments need constant monitoring, as they are at
increased risk of experiencing serious events, such as acute myocardial infarction or stroke
(stroke). 
Hypertension patients who do not take steps to keep blood pressure levels lower end up
overloading the heart, which can lead to heart failure and heart attack (when blood flow to the
heart is blocked). Diabetics who do not control glucose levels are more prone to kidney disease,
vision problems and peripheral arterial disease, which reduces blood flow to the feet and
increases the chances of ulcers (wounds) and infections. On the other hand, when blood
pressure, glucose level and other factors are properly controlled, the chances of complications
and serious events decrease dramatically. Hence the importance of monitoring chronic patients,
which helps to prevent health problems. Another group of patients who benefit from monitoring is
admitted to the Intensive Care Units. Most of them are in a condition that requires continuous care
and a therapeutic approach. Overall, five categories of patients require comprehensive
monitoring: in critical condition, and m high-risk conditions, suspected evil life-threatening,
unstable physiological systems among other cases. The purpose of monitoring patients is
the most complete clinical evaluation, combining this general examination with the data obtained
from monitoring increases the accuracy of the diagnosis. This information becomes even more
important, which brings together critically ill patients who need quick and assertive
interventions. In this scenario, having reliable data can make the difference between the patient's
life and death. Therefore, one of the main objectives of monitoring in these environments is to be
a tool for decision making. The monitoring also serves to acquire continuous physiological data,
transmit, store and organize this information, which must be integrated and correlated. Providing
clinical alerts, measuring disease severity, providing feedback and clinical effectiveness are also
goals of monitoring. The possibility of effective monitoring of patients in their homes adds
advantages not only for them and their families, but also for doctors and health professionals. After
all, it is not necessary for chronic patients, for example, to go to a hospital or clinic, or remain
hospitalized to receive the follow-up they need. It is enough that your doctor contacts the patient
through the system or via application and cell phone. Thanks to the combination of digital devices
and systems that integrate with them, it is also possible to record, store and transmit data about
the patient in real time, via the internet and sharing platforms. The main purpose of home
monitoring is to ensure the monitoring of patients with chronic diseases or mobility
difficulties. Monitoring at home also serves for greater convenience, privacy and avoids exposing
the patient to hospital infections. Reducing overcrowding in hospitals, freeing beds for
hospitalization and reducing costs are other objectives of this type of monitoring. This specialty
has been increasingly used to support patient monitoring, combined with a process called
telemonitoring. Through a safe and intuitive platform, doctors and other health professionals can
assess patients' exams remotely, whether at home or in hospitals located in geographically distant
regions, advising on the best conduct at the moment. Remote telemonitoring is usually used when
it is necessary to collect continuous data, obtained through examinations performed
automatically. For the process to be made possible, the doctor, nurse or health professional
places the necessary equipment on the patient, tests the measurements and explains how the
technology works. In the case of the holter (continuous electrocardiogram), electrodes are
positioned and fixed on the patient's chest, with the aid of an electrically conductive gel. The
digital holter device has the ability to convert the data into graphics formed by pixels, and transmit
it to the database. Thus, the information is protected and can be accessed through login and
password by the responsible doctor, caregiver, patient and their families. The data can also be
interpreted, giving basis to the medical report at a distance. These professionals must register all
treatment, medications and evolution of the patient's health in a specific medical
record. The advantages of remote patient monitoring are: hnnization in the environment and,
consequently, in patient care, reduction in physical wear and tear, travel expenses, automatic
calculation and greater security for data, organization and union of patients data in the same
database. Examinations in radiology, pulmonology, cardiology and neurology can be used
to remotely monitor patients: the routine (at rest) and the exercise (exercise test) and 24-hour
holter can be monitored remotely, with the aid of a digital electrocardiograph, free and
portable, equipment for continuous monitoring of blood pressure , spirometry is known as
pulmonary function test, this is the main test to assess the capacity of the lungs, helping in the
diagnosis of diseases Respiratory diseases such as asthma , Magnetic Resonance Imaging uses
a magnetic field to generate high resolution images of internal parts of the human body
and performed with equipment capable of converting the images into pixels, it can benefit from
distance reports , one of the exams diagnostic imaging, the X-ray made with a digital device
produces images in pixels, which can be shared on the telemedicine and ana
platform Listed remotely, Computerized Tomography generates several cross-sections that, when
overlapped, can form 3D images and the digital tomograph allows the transmission of records via
the internet, enabling their interpretation and in issuing results from a distance,
the Electroencephalogram is used in assessment of brain electrical activity, signals abnormalities
present in neurological diseases and disorders of consciousness and the digital
electroencephalograph can also be used for remote monitoring of patients. 
The system is useful for feeding the patient's electronic medical record, gathering all health
information in a centralized way and keeping it available for research or cross-checking of data. In
addition, it is possible to reduce the costs of hiring specialists on the spot, leaving the reports with
the specialists. Home care and hospital teams can also count on a qualified second opinion
whenever it is necessary to clarify doubts about the exams. Both medical documents and patient
information are stored respecting the rules of secrecy and protection, with barriers such as the
requirement of login and password to access patient data with the latter's permission. The world
today faces a major challenge: facing the pandemic for the new Corona virus, maintaining order
in health institutions, having resources available to all those in need, and preserving the integrity
of the health of the professionals responsible for the care of patients. In the midst of so many
uncertainties about a new disease, something is already certain: preventive measures are able
to reduce the rate of spread of infection in the community, allowing public health systems the best
support for critically ill patients. Among the preventive measures, we have personal hygiene
habits, behavioral changes and social distance. In this scenario of distancing, it is essential that
we make the best possible use of health technology to connect with our patients. Without a
shadow of a doubt, telemedicine can be a great ally, both in monitoring patients in the quarantine
phase, as well as in screening new cases to define which ones have real warning signs, and who
should attend a hospital unit. Recent studies point m that telemedicine is a solution "virtually
perfect" for a pandemic scenario like this the Covid-19. In many countries, we have an additional
challenge: access to intensive care. The challenge of a pandemic that consumes intensive care
resources is difficult in the private sector, and extremely challenging in the public
sector. Telemonitoring can assist health care by allowing the monitoring of several beds remotely
by multidisciplinary teams, and less direct contact between the health professional and the
patient, since the capture of vital signs and data from devices connected directly to the patient
are automatically inserted into the electronic medical record after validation. This data can assist
directly TeleConsult oria where medical specialists and more experienced can remotely help in
conducting complex cases, overcoming geographical barriers of a large country. Monitoring
becomes even more efficient when combined with telemedicine, enabling the issuance of results
in a simple and quick way.

## Teleregulation
Set of actions in regulatory systems with the aim of considering appropriate responses to existing
demands, promoting access and equity to services, enabling health care. It also includes the
evaluation and planning of actions, providing management with operational regulatory
intelligence. Teleregulation aims to strengthen care in Primary Health Care, allowing to qualify
and reduce the queues for specialized care. The regulation of health care has the primary function
of ordering access to health actions and services, in particular, the priority allocation of medical
appointments and diagnostic and therapeutic procedures for patients at greatest risk, need and /
or clinical indication arising from health services in a timely manner. In addition, the regulation
should serve as a filter to referrals unnecessary and should select the access of patients to
appointments and / or the procedures only when they had a clinical indication to realize them,
avoiding the exposure of patients to consult and / or unnecessary procedures. In addition, it
optimizes the use of health resources, prevents unnecessary travel and brings greater efficiency
and equity to the management of waiting lists. There are successful experiences of regulation
between telehealth and public health policies in various parts of the country. The study noticed a
significant drop in the number of cases referred via government system after the beginning of the
flow that includes teleconsulting in the discussion of cases prior to
referrals. The Program Telehealth is gaining v isibilidade and becoming the focus of interest of
management from the evidence presented, making If a tool important of regulation, acting on
the reduction and ncaminhamentos to specialties, reducing queues of waiting for
care with specialists and costs to the management. It is known that the integration of information
systems in the public sector would define success in achieving the objectives and make it possible
to reduce development costs. If related sectors focused on their specific service areas and also
prepared their databases for the exchange of information, there would be a consequent use of
data, and this would significantly reduce rework. At the national level, there is a tendency in the
search for viable alternatives for the reuse of public information and that the focus should be on
the integration of the data produced. In this way, the integrated database system is the most
viable solution to unite all patient data in one place where it can be accessed in an updated, safe
and fast way. Some tests are d and relatively high cost and therefore their s offer s should m be
restricted s to real indications of achievement. The inadequate request for tests often creates
bottlenecks in the health system, in which demand exceeds supply, creating queues that
compromise the health of individuals. These bottlenecks require, in order to overcome
them, strategies to impact Primary Health Care in the access regulation processes, from the
requesting services to the regulatory centers, as well as in the organization of specialized care. 
In this perspective, the study aims to provide better regulation criteria for requesting tests in
the public health network, making use of the system, optimizing the process and improving the
resolution of appointments. From this first analysis, you can see that the flow teleregulação with
support d the system can evit air forwarding unnecessary to test requests made. That is, possible
requests that can go to the regulation queue can be solved with the help of the system, from
which management suggestions were made in Primary Care. In this respect, there is a direct gain
both for the service user, who receives attention and care more quickly, and for the health system,
which can direct its resources more efficiently. Only from a detailed analysis by a properly trained
professional, it is possible to check the quality of the exam requests being made. Thus, with the
identification of incomplete test requests or off the display protocols defined by the Ministry of
Health, may permit go through d the database, be one tool for diagnosis and continuing education
of health professionals. This is because the refusal of requests to request exams is centered on
the observation of a concrete need for learning by the Primary Care physician, with the potential to
increase its resolution in cases of the emergence of future demands that are similar to those that
have already occurred. Besides that, there - is an important positive impact on the greater agility
to perform d and exams, particularly the urgency, promoting thus greater equity. On the other
hand, the system also contributes greatly to which the management max regulating, which is
recommended by technical. From from this first analysis, it is possible to verify that
the teleregulation flow with the support of the system can avoid the unnecessary routing of exam
requests made in the period. That is, possible requests that would go to the regulation queue
were resolved with the help of the system, from which management suggestions were made in
Primary Care. In this respect, there is a direct gain both for the service user, who receives
attention and care more quickly, and for the health system, which can direct its resources
more efficiently. Only from a detailed analysis by a properly trained professional, it is possible to
check the quality of the exam requests being made. In this way, with identification, you can assess
the demands for exam requests and redirect health policies based on this information. Thus, the
system for exam regulation is consolidated as a tool that supports, on the one hand, the health
professional who needs some specialist support, on the other, the end user who ends up receiving
a more efficient health service. In addition, resource management itself can be more
assertive, since based on the analysis of demands, with more qualified regulation, the manager
can actually assess the real scale and need to be met. From a more detailed analysis it is also
possible to verify cases of concentrations of occurrences in a given region and, therefore, the
definition of strategies to identify and solve the cause. One of the main obstacles found in
the implementation of the regulation process in exams through the use of the system lies in the
fact that government system does not currently allow the integration of other systems. Due to this
impediment, it is necessary to establish a manual stage in which the data of exam
requests regulated by telehealth are entered into government system manually. Thus, a rework
is generated, as the request data was already registered on the telehealth platform. This fact is
extremely relevant, including for a good solution for reading government system data and
including this data in the patient's database since the data belongs to the patient. In this sense, the
project team has already established some dialogues with the Ministry of Health and
GOVERNMENT DATA so that this integration between the tools is made possible. The process
of interaction between the system and the government demonstrates a clear increase in the
efficiency of the provision of health services with a direct counterpart for the qualification
of primary care medical professionals. In this context, the regulation process is one of the main
pillars for health services to be properly directed and resources can be used according
to needs. In addition, regulation, when carried out on the basis of a directive signed in a solid
process, provides that health service offerings are correctly guided. Waiting queues tend
to decrease, since unnecessary requests caused by poorly formulated requests do not enter the
queue; therefore, that user who has a real need to use the service should not be
left unattended. We can observe from d and research carried out, that the design of 72 hours to
meet the request of the requesting physician can make the response time to the much smaller
request than is practiced. Thus, it becomes evident, once again, the importance of research
carried out by educational institutions acting as a provider of technology and innovation to society.
Teleducation
Teleducação provides several continuing education actions such as courses, applications,
web lectures and educational materials. Availability of interactive learning objects on topics
related to health, taught at a distance, with a focus on learning at work, which in turn, occurs
across their fields. Teleducação offers distance education actions for health professionals in
Primary Health Care / Primary Care and undergraduate students in the areas of health. The
actions of permanent and continuing education aim to update health professionals to qualify the
service provided to users. All Teleducação actions are based on current demands and / or arising
from our services. In addition to being created from suggestions sent by our channels. 
This opportunity is extremely useful for doctors, nurses and other health professionals, who need
to be always up to date, but have a busy schedule. Thanks to distance training, they can acquire
new knowledge in a practical and agile way, without the need to travel to an educational institution
or establish a strict study routine. Another facility promoted by teleducation is that there is no need
to gather a minimum number of students to open a new class, as in the face-to-face
modality. The internet is the largest current vehicle for disseminating information, and is now used
as a strategy for the implementation of the Permanent Education Program. In this case, the
system can assist by providing the database with patient information for medical studies that can
help assess diseases and their developments for possible control of localized outbreaks and
create models using artificial intelligence to guide public health in how to resolve such problems.

## Second Formative Opinion
Although the name is similar, the second formative opinion is not the same as a second medical
opinion given during teleconsulting. It starts from questions, which takes into account criteria of
relevance and relevance with regard to GOVERNMENT DATA guidelines. Its purpose goes
beyond clarifying an issue, becoming a reference for future doubts. Therefore, the answer must
be prepared based on a bibliographic review and clinical and scientific evidence. The Second
Training Opinion is a source of information on important topics in Primary Health Care, published
in the Virtual Health Library. Its structure is composed of questions originating from teleconsulting
and answers based on good scientific evidence, with the possibility of answering questions and
needs of other health workers, with the aim of expanding the resolution capacity in similar cases
or situations. The goal is to have a systematic response, originated from teleconsulting based on
the best scientific evidence. They address priority themes for Primary Health Care and aim to
expand the resolution capacity of health professionals and teams. Because they are built from
the questions and doubts of the workers of the Family Health Teams, they have a strong potential
for transmission and production of knowledge and support to the daily issues of Primary Health
Care. The main objective is to provide support through the exchange of knowledge and
specialized information to professionals working in the primary health care network (doctors,
dentists, nurses, technicians and community health agents and others), members of the Family
Health Strategy. This action aims to reduce health expenses through professional updating,
reducing the amount of unnecessary displacements for patients and offering disease prevention
activities, combining knowledge produced in the most important university centers in the country
with the latest advances in information technology. Communications and information technology
necessary to promote the integration and enhancement of health professionals. It is a source of
information that presents evidence-based questions and answers as content related to priority
problems. They originate from teleconsulting that deal with relevant issues with the possibility to
answer questions and needs of health workers, with a view to expanding the resolution capacity
in similar cases or situations and support health professionals in daily practical issues. They are
prepared by the Telehealth Centers and submitted, which sends them to review professionals
with specialization and / or experience in Family and Community Medicine. The question and
answer goes through an adaptation, structuring and complementation process, classified by the
degree of the recommendation. The question or question that has been answered, without
mentioning the names of patients or persons, should be as direct as possible, avoiding the use of
acronyms and abbreviated forms. The evidence-based response must be synthesized, but
complete, it must include the strength of the recommendation using the criteria developed by
Project Guidelines. It should be explained to making decision and the evidence that and mbasam,
indicating the references of the main studies that defined the response option, bibliografy
rfferent studies or sources that supported the response. The requesting professional Indication of
the category of the professional who asked the question or who submitted the question or u to
whom it applies. We use d writers or terms for indexing and retrieving questions and
answers. Health Sciences Descriptors and the International Classification of Primary Care are
used. This data will be generated at the time of publication question relevant and comprehensive,
and may be of clinical character or on p ro cesses work and legislation. Issues related to
the p common health problems; relationships between individuals, their families and
communities; work process; clinical cases of patients and complex and interdisciplinary health
issues are candidates. Well-defined health situations should be used, since it is difficult to create
it with very complex situations. It should be the proper language to the public that is
proposed as doctors, nurses, agents with health omunitários, patients and all health
professionals. You should use r bibliographic efferent containing indication of at least one APS
book and an international reference, except and specific issues and multidisciplinary teamwork is
used literature in and exterior. In addition, references must be updated no later than the last 5
years. The p arágrafo initial should be short answering questions in an objective and
direct and complementary paragraphs expanding discussion the subject, compared with
attributes, as recommended by the Telehealth Manual for Primary Care. 
The indication of the degree of evidence and level of recommendation should use the criteria of
the Project Guidelines. The system manages this entire information database and can generate
real-time and safe answers to health professionals' questions in real time.

## Telesurgery
One of the specialties within Telemedicine is Telesurgery, also called distance surgery. We are
moving towards an unprecedented technological world and the person who takes a concrete
position today, may be testing theories that will fall apart in a very short time. It involves performing
a surgery in a place where the specialist is not present, using all the technology available
today. Be it teleconferencing, robotics guided at a distance by computers connected to the
internet, among others. We currently use the word Tele surgery because it is a nomenclature
within Telemedicine which is the care of patients at a distance. The interest in investing in this
area is based on taking the specialist represented by robotics in distant places where only general
practitioners routinely exist. In the current scenario, we can list the 5 advantages offered by
telesurgery : the incision, the cut in the skin is much smaller and how robotic arms are
used , without the need to introduce the surgeon's hands inside the patient, the reduction in the
surgical field is surprising; the surgery is highly accurate because as the s commands are
accurate, mathematical, with no chance of error in the final result of the action performed by the
mechanical arm to from the distance the surgeon's command so n will exist hesitation, tremor,
anxiety, excitement, everything it is accurate; bleeding is much less because as we are talking
about reducing the incision, reducing the internal manipulation of the patient, obviously we will
have less trauma and less bleeding and with less bleeding, we will have less blood transfusions
and less risk of contracting the disease by repeated transfusions; metter ergonomics, to say that
movements occur in three dimensions within the operative field and brings with it less surgical
stress and the result is less pain and less need for analgesics; r Faster recovery and
healing , using the same principle explained above, with less trauma, less tissues are injured and
the end result is a significant reduction in recovery time and since these are less affected tissues,
healing will be much faster. We can also use the machine learning process,
called machine learning will completely change the direction of research and incorporate artificial
intelligence into our lives and use it to our advantage. Certainly she will be able to replace the
surgeon, who today is required to be present within the operating room where the procedure takes
place. We can visualize the virtual doctor interpreting the exams remotely and contributing a lot
to make diagnoses of diseases that only the specialist is able to document. Using the system, the
doctor from a remote location sends the file of the exam done to your patient, using the internet
and in a few minutes the specialist using the system interprets the exam and releases the medical
report with his opinion that will be decisive to save the patient's life. As an example, we can use
a patient with chest pain, suspected of having an acute myocardial infarction, going to the health
center in a city with 2,000 inhabitants. It is known that there is no cardiologist, nor doctor on duty,
within a radius of 100 km. It is usually a nurse who screens patients and calls the clinical doctor
who is at home. At the clinic there is an electrocardiogram device and the nurse quickly performs
the exam and sends it to the system database using the internet. In minutes, the cardiologist
interprets, confirms that the patient is infarcted and immediately guides the immediate
management of medication and transfer to a hospital with greater resources. The surgeries can
be transmitted over high speed internet in real time or having been previously recorded. Realtime surgeries, similar to what is done in some courses, have the advantage of allowing full
monitoring of operations, with discussions involving the surgeon himself and other eventual
debaters. The various technical aspects, the inherent difficulties and the decision-making process
are shared, which can increase the level of understanding. Recorded surgeries allow you to
experience all the moments of the operations, which can expand learning. They do not impede
the discussion between surgeon and debaters. On the other hand, they use less transmission
time than live surgeries, with lower costs. Since it is a recording, the transmission of the surgery
does not, in principle, have legal implications. From an ethical point of view, it is up to the patient
to consent to having his surgery recorded and the responsible physician to preserve the identity
of his patient. We can download the recorded surgeries from the database, which will give the
opportunity for doctors to watch, from a virtual video library, the surgeries that interest them, with
the surgeons of their choice, at the time of their convenience. In this way, telesurgery can also
function as a pedagogical resource, facilitating the access of students from anywhere in the world
to the knowledge of specialists. In this way, future surgeons can learn complex operations or
deepen techniques. In addition, surgeries performed with the aid of robots are more accurate,
which reduces the chances of errors. The professional can also guide the entire procedure, taking
the step by step to a non-specialist surgeon, or command the robots that will perform the surgery
through controls and in these cases, there is a medical team with the patient, not only the robot. In
cases where the patient needs specialized care but does not have the health or financial
conditions to be taken to a specialist surgeon, telesurgery allows him to have access to the
procedure he needs without him or the doctor having to move. 
This represents an even greater advantage for remote and difficult-to-reach locations, where the
devices needed to perform telesurgery can be sent, benefiting several people. This represents
greater security, even for those who are on missions at sea, in places like Antarctica or even in
space. One issue is that, even if the surgeon in charge is in another location, the surgery cannot
be performed without the presence of an anesthetist, a secondary surgeon, who should take over
the procedure in case something unexpected happens, and a medical team. Thus, in a remote
location, telesurgery will also only be possible if a team is available. Ethically, there are still
discussions about responsibility in case something happens. Using the system, we can have the
entire database and patient information at the hands of the health professionals involved.

## Teletriagem
Telescreening is the tool to verify the existence of benefits of information and guidance services
in health remotely with the use of information and communication technology resources could
bring to health systems and their users, including the National Health System. N the emergency
units or emergency care units is motivated by very simple, low complexity problems, which could
very well be attended satisfactorily in basic units or outpatient units of small and medium
complexity. The structuring and organization of health services can establish baskets of services
that paradoxically relate to the needs of its users and this allows them to seek alternatives to
satisfy them wherever they find availability in emergency care units, emergencies and emergency
rooms. In failing to understand the real needs of users, local health systems, even if they are
organized to offer basic baskets of services, promote distortions in the use of the system, as
supply is absolutely detached from demand, both in volume and in kind and definition of
services. There is no point in offering consultations, exams, free medicines and procedures, if the
users' needs are related to socioeconomic issues, poor living conditions, violence, loneliness,
need to establish a bond, work, access to a technology that provides them with some satisfaction
status. The perception of low resolution and quality of health services and the absence of policy
definitions lead the population to seek care where there is availability. And, the greater the
restriction of services, the surplus will tend to seek care wherever there is a greater concentration
of immediate entries, even if there is overcrowding, impersonality and performance only in the
main complaint, which in principle is insufficient for those seeking care, as discussed earlier. The
search for non-urgent care in services that should be dedicated to care for more serious cases is
not a particular feature of public health services. Private hospitals face this same problem, which
sometimes causes difficulties in managing the services, dissatisfaction of their clients, whether
these patients and family members, whether doctors and partners, or health insurance
companies. For service provider units, such as hospitals, the attendance of non-urgent cases on
the premises of their services and emergency, causes difficulties in the satisfaction of the users
of their services, which sometimes, when their cases are classified as non-urgent, they see others
patients who checked in minutes or hours later should be prioritized. The greater the number of
patients with higher priority, the longer the waiting time for those with low or no urgency cases,
therefore, the greater the risk of dissatisfaction. Getting humanization, welcoming and
dimensioning measures to reduce the feeling of waiting in those whose problems by clinical
criteria can wait, has been a constant challenge for hospital managers and health
systems. Attentive to this, and also considering that the costs of care in urgent
and emergency units, due to the nature and characteristic of the service, are naturally higher than
in an outpatient unit, many health organizations have been looking for alternatives to better direct
their patients. Is ruled out the possibility of the patient to direct search that suits you. They are not
prevented from seeking urgent and emergency services directly. The search for alternatives for
assistance, based on information and health guidance at a distance, has been one of the choices
of many organizations, not only to diversify their service lines, but also to reduce their
costs. The use and application of information and communication technology to facilitate the
expansion of multicentric research, encourage the exchange of knowledge in the medical field,
and enable the exchange of knowledge for the transfer and shared development of
new technologies, as well as creating opportunities for improving the training and qualification
of professionals and researchers in the medical field. They also aim to strengthen the sharing
of information between the country's various research centers and assistance institutions
to provide network diagnostics. Finally, a more determined dimension with the purpose
of optimizing education, using technological solutions in multicentric research and regulating
care. The topic of telehealth is still quite incipient, limited to the fields of research, education and
information sharing in the medical field and aimed mainly at the interaction between professionals,
and between health, education and research institutions, for telediagnosis and support of
therapeutic guidance. In other countries, the advances in information and communication
technology, the expansion of its dissemination with lower costs, provided that telehealth also
encompassed the relationship between the population and health systems and, thus, guidance
and information products from were able to reach health professionals directly from patients. 
In recent years, there has also been a phenomenon of the expansion of the diffusion of information
and communication technologies, with lower costs of access. Having greater access to these
communication technologies, which breaks distance barriers, population could benefit from health
services supported by this type of technology. There could be benefits to citizens and health
systems of services such as, for example, teletriagem, as occurs in other countries. The Ministry
of Health had an expense too high with the average service and high complexity and with the
urgency and emergency services. Many of these resources were used with patients who could
have been seen in less complex instances, as long as they had adequate information on how to
access the services or had the services accessible to meet their needs. Re- orienting the flow of
entry into the health system towards an optimized use of scarce resources also becomes an
action to be pursued by health service managers. Studies indicate that worldwide the demand for
users for urgent and emergency services increases, agree that the costs of these services are
high and increasing, and become higher when used by users who could be served in services
with simpler technologies. Studies say that the attendance of an urgency and emergency unit of
a large hospital center could be performed in basic health units and also agree that unnecessary
demands are often met in urgency and emergency units and in its qualitative study it was
demonstrated that the perception and belief of users are determining factors for them to opt for
these more specialized services when they could seek care in basic units, they consider that in
order to meet these demands, the services need to be reorganized and there is a need for
structuring screening services called “reception and risk classification ”as a way to reorder
emergency room services and minimize the effects, caused by high demand and overcrowding,
of overload on health professionals and demotivation. The consultations performed in an urgency
and emergency unit are 'routine', that is, appointments that could occur in the routine” of
an outpatient unit, either by appointment or by appointment, when a vacancy for the same day is
obtained between scheduled appointments. The misuse of urgent and
emergency services for care that could occur in outpatient units of countries with low educational
and cultural predominance, countries such as France, Canada, Spain and the United States
coexist with emergency services performing care of low complexity and non-urgent cases, which
could be solved in pre- scheduled care units. It discusses the sense of guilt that is attributed
to users for the distortion of the mission of the urgency and emergency units. It puts this thought
present in the speeches of health professionals and generates a state of real conflict between the
person who seeks care and the service provider, where the health professional who considers
himself to have knowledge of human health and therefore, understand what it is truly urgent and
emergent, it understands the user as a lay person and, as such, without the capacity to discern
what is urgency and emergency, and when he diagnoses it as non-urgent, he sees it, therefore,
as the cause that prevents him from attending cases of greater severity with greater dedication of
time, that is, he perceives the patient as one who makes it more difficult to fulfill his mission of
saving lives at imminent risk. The conceptions and identifying signs of urgencies are multiple and
can be different depending on the context of care and the individuals who give them
meaning. Health professionals, for example, are usually guided
by anatomophysiological parameters to define what is urgent; on the other hand, users try to
express, through their urgencies, the disorders and suffering present in their insecure living and
surviving everyday. This diversity of perceptions makes emergency care a complex and
emblematic issue in the context of the implementation of the Unified Health System, especially in
relation to the ways in which health services are organized and structured for care of this
nature. It is understood that the patient and their family members or companions, in turn, when
not attended in an emergency or urgent condition, attribute to health professionals judgment of
insensitivity, inhumanity and unwillingness towards their pain and suffering, not making an effort
to understand its urgency. So it describes: Feeling ignored and even annulled by the lack of
attention / consideration given to their physical and moral suffering, denied in the intimate
appreciation they had of the seriousness of their problem (or of someone else, loved one, known),
many are those who, resigned or indignant when telling their bad experience with the emergency
room or call center, end up questioning the goodwill, competence and even the humanity
of health professionals. This mismatch des understandings, many urgent and emergency
sectors are transformed in clashes arenas between patients and professionals. The population
has its own criteria, according to its interests and conveniences, to characterize the urgency, and
the user's view is different from that of those who assist him and is directly related to his selfassessment of his health status. The choice of the health service will be made according to your
perception of what is simple or serious, resulting, almost always, in a spontaneous search for
services. Some reasons that lead users to not use primary health care and follow their own
trajectories in the search for other services in the network are distrust in relation to the care
received in health units, the frantic search for tests and medications, the lack of doctors, the
difficulty of finding a place for a medical appointment on the day that you deem it necessary, the
difficulty of scheduling an appointment with specialists. 
In order to reduce overcrowding, optimize scarce human and material resources and improve the
fit between limited supply and high demand, the solution would go through the use of an artificial
intelligence system and health professionals remotely accessed for an initial screening. In order
to improve the situation, it would then be necessary to educate the population in such a way as to
adhere to the logic of good use of emergency rooms and seek them out for health problems within
their specific competence, that is, to provide emergency care to cases real emergency. Among
other objectives, the use of the screening system should aim to help the patient to inform air about
the symptoms and accidents, among the most common, justify the trip to the emergency room
and call a rescue vehicle; and those who, despite their sometimes spectacular character, do not
require immediate medical intervention. To disponibilizar this service to guide users c atom
resource education and counseling of patients, as given in some countries before users directing
to the primary care and emergency units, could be reduced demands of cases without urgency,
and thus, reduce the possibilities of conflicts. Services emergency care consume a high value
on calls. If you believe that many cases could have been treated in outpatient
units, could the use r less complex services lower costs to the health system, as the costs in
emergency units are well higher than the costs in outpatient clinics as basic attention. The federal
funds allocated to the Primary Care has an average annual cost per person less than the
cost average for care in emergency units and emergency. In view of the moment that the need
for fiscal adjustments is launched, as pointed out by specialists in the economic area, these data
demonstrate the explicit advantage for public coffers, of greater incentive to use Primary Care
programs. Thus, it is considered that strategies for strengthening, encouraging and retaining the
GOVERNMENT DATA user for Primary Care are very positive. Teletriaging services can fulfill
this role of encouraging that users, who autonomously seek urgent and emergency services, even
if they do not have typical problems with these services, are redirected to basic health
units, encouraging a more rational use of the health system. Technological advances in the areas
of information technology and telecommunications, with cheaper available technologies, have
been stimulating, in the world, the appearance and growth of remote nursing counseling
services. The s practices telescreening or telenursing is worthy of attention. The majority
of studies available refers to the economic viability of the services telescreening provide. The
results showed that the guidance provided by nurses to clinical cases reported by telephone in
most cases was considered adequate and that the errors were due to the tendency of nurses to
choose more cautious than risky behaviors. The satisfaction rate of service users was
high. Studies say that despite reducing unnecessary medical appointments, they did not cause
adverse events, that is, they did not produce risk situations for patient safety. The interest in
creating telemetry services lies in the idea that health care costs can be reduced
when patients who do not need immediate care can be redirected to low-cost care units instead
of going freely to services. Such as high-cost emergency departments. In addition, they add, these
services can reduce the number of patients going to outpatient clinics for care that can be
performed at home by the patient or family or caregiver. They emphasize that teletriaging is
distinguished from other telehealth services in that it manages to relate to the user remotely,
establishes a trusting relationship capable of producing information, which will make the health
professional establish the level of care appropriate to the problem presented and, thus,
determining the urgency of the action to be taken and oriented to the plaintiff, which may vary
from the self - care guidance to the dispatch of an ambulance. State that public health
actions should be guided r for prioritizing, strengthening and expansion of primary health care for
all citizens, for the integration of various health services and training to make informed choices
about their health and their care. Thus, the strategy for reaching these guidelines, among others,
the dissemination of teletriage services can be used in conjunction with information from the
database with patients' health history. In addition to the reasons for reducing costs with
unnecessary care to emergency departments, there are demands for information and health
guidelines and that these services can contribute to the reduction of hospital stay, by supporting
the families of patients in post-discharge, reducing hospital infection risks and hospital
costs. The s services could contribu go to reduce patient visits without care immediate emergency
services and unnecessary visits to outpatient medical services. There is a need for the services
to be structured with the provision of technological resources for service and monitoring of the
system and the use of its database with specific clinical protocols for telemetry to support decision
and conduct, continuous training of the professionals involved in teleservice. The deployments
of these services: provides r assessment of the reported problems, accurate health information
and guidance with reference forwarding; promoting self-care activities to allow people to
make health-conscious decisions; make individuals more self-sufficient to take charge of
the health and well-being of themselves and their loved ones; promote more appropriate use of
health, emergency and outpatient resources; reduce inadequate demands from emergency
departments; reduce costs; support and improve access to health services and health information
across the province; improve the quality of health services and health information; support
the proper management and use of health resources; promote health education; 
provide a centrally coordinated path to health care information and services for public and other
health professionals; help identify unmet health care needs for use in planning and developing
future programs and services; collaborate with other health care providers; improve access to the
most appropriate health service; improving access to information and health advice; improve
health education for the public; improve consumer satisfaction; increase awareness, acceptance
and understanding for non- urgent conditions , providing information on how to manage symptoms
more appropriately, increasing your capacity for self-care; and, thus, contribute to
the economic use of health care resources. These services, they used d the system to support the
decision and clinical protocols. All of them set up strategies for evaluating the quality of their
performance, with call performance indicators such as average service time, waiting time for
service, referral indicators, user satisfaction indicators, indicators on the knowledge of the health
problem and on the certainty of past guidance and others. The initiative was stimulated, that is,
before going to medical care, patients should call and talk to a nurse and patients who required
medical care, after being instructed by nurses, did not even visit and had their controlled health
conditions. The telescreening reduces the use of other health services without compromising the
safety of the patient. They also reinforce the reduction of assistance in emergency /
urgent services, medical assistance after hours and visits to the office, thus contributing to the
reduction of total health care costs. They state that telephone health counseling service is a model
to encourage public access to the most appropriate level of care, while increasing the ability of
users to take care of themselves. We have as a differentiating factor for the success and
achievement of results, not only technical knowledge, professional experience, but also discipline
with the moderation of parameterization of own indicators that, if not well dosed, would contribute
to a less favorable environment for development and application of attributes that are not able to
get the best out of the system and the database. The need and importance of information for
professionals working in teletriage services, so that they are better prepared for decision making,
in situations where situations of singular complexity are present so that health
professionals in teletriage services in emergency situations and can record the respective
decision making in high urgency situations. The decisions were made using symptom-based
heuristic rules and the decisions were mostly accurate, with explanations that demonstrated an
association between knowledge and action. However, the greater the complexity, the volume of
causal explanations to justify decision making was also greater, which revealed
more often inaccurate decisions, as well as their respective explanations, demonstrating a
dissociation between knowledge and action. They assessed that in situations of moderate to low
urgency, where contextual knowledge of situations could be exploited to identify the
needs to negotiate the best action plan to meet those needs, the decisions were more
accurate. This can be used with the aid of artificial intelligence. This use of artificial
intelligence strengthens help in the continuous training of teletriagem professionals with
experiential training, with realistic simulation models for using examples based on the experiences
of the services, with discussions of real cases and adaptation of protocols, in order to contribute
to the expansion individual experiences and to increase the precision in decisions taken
in situations where the context of the emergency determines the reduction of time to investigate
and contextualize the problem and in which decision-making has to take place in a shorter
time . S ervices of telescreening are instrumental in reducing the use of services emergency care
for cases that there was no need for immediate assistance and help in using the most appropriate
of the available outpatient medical resources generating resource savings in the health system
and bring another conclusion perspective: in addition to reducing unnecessary consultations with
the health system, telemetry can contribute to the management of the lack of immediate access
to medical services that residents of non-urban areas face. Thus, they compared the results of
teletriaging in urban and non-urban areas and concluded that the results of reversing the intention
of clients to go to more immediate medical services in residents in areas with greater difficulty of
access or with little flow of information were greater. Transit, suggesting that the access factor
contributes to the expected results most strongly obtained by teletriage services. In fact, whether
or not there is a telemetry service, the lack of geographic accessibility to health services is a
determining and discouraging factor in the search for health care. The telescreening contributes
to improved access when reduces flow patients would not need to be a certain service and service
oriented towards the most suitable. In areas where accessibility naturally reduces entry doors,
teletriagem prevents unnecessary trips from generating costs and burdens on the patient and his
family, when he would spend a greater effort to travel to a unit far from home in search of a solution
that lack of knowledge could be obtained by saving efforts in the nearest locations or even in their
territory, in addition to generating an unnecessary cost to the health system. The telescreening
services enable expansion of access to remote areas where residents generate information to
managers about not you identify needs or unmet, demand identification for creating new services
and health programs. 
It reveals the need for patients to obtain reliable health information and guidance by commenting
that health professionals receive many calls from patients asking for help and advice to
clarify health issues. However, as the number of patients increases, and the duration of
hospitalization decreases, the needs for care and evaluation of specialists remain, since patients
return home earlier from the hospital. Home care services, community hospitals and family
doctors are inadequate to meet the needs of a growing patient base, whether due to inadequate
access to professionals or inadequate supply of professionals, making many patients have to wait
for weeks before consulting your family doctor after leaving the hospital. When developing a
decision support system containing protocols for the different problems reported by patients in
their consultations with nurses, you can see that there is a significant improvement in the quality
of the assessment made by nurses with the use of the tool, the improvement in the quality of
recommendations and the number of questions asked were also measured and the results
showed that with the use of the tool the number of questions is greater than without the use of
the system and protocols, and these additional questions were predominantly classifiable as
essential or beneficial for a good evaluation. In the development of the system, some premises
were on the agenda: a system focused on the user, usability, flexibility, both for recording
information and for assessing the need to interrupt with the electronic questionnaire whenever
necessary, caution in the use of an answer system. Due to the uniqueness of the service, the
system should encourage its use, the user should feel comfortable using the system. D highlight
the importance of using protocols and training for the continuous improvement and training of
professionals who work in teletriaging to achieve results, they state that informal learning based
only on experience and observation is insufficient and inappropriate for teletriaging work, reinforce
the need for a formal training structure so that nurses acquire more and more skills in the use of
work tools, become familiar with the use and how to conduct connections with the use of protocols,
how to record in the systems, how to produce data for case studies and improvement of protocols
and systems, how and when to have to interrupt with one protocol and use another, or even be
assertive in interrupting one protocol and directing care showing safety and reliability to the
patient. It was observed the performance of a group of health professionals who worked on their
previous personal experiences and whose admission training took place in the work sector
through the daily monitoring of other professionals who were passing on their work routine. F hi
verified that these professionals in the care of patients could not collect basic information and
complete the tables clinical patient and often provided guidelines and behaviors without
obtaining historical Clínic the is suitable. Then, the results of teletriagnosis services performed by
professionals who received formal training and others who learned the dynamics of teletriagnism
services were compared by working with other professionals on a daily basis using the system
and information from the database, and it was observed that the the group with formal training and
dedicated to reducing patient trips without immediate need for medical services was greater and
that in the group with observational and practical day-to-day training, their results generated
a smaller reduction in the trips of patients who made contact with them previously to the offices
doctors, suggesting then that with formal training in teletriage , nursing professionals can be more
effective in solving the patient's problem through the system and reduce the need for time and
resources from other services and health professionals. Challenges for the telescreening is
a paradigm shift for which the training of the health professional is given and that is the fact that
the telenursing care are forced to evaluate and advise patients without actually seeing
them. Thus, they must seek to rely completely on the system and information in the database. So
consider that telescreening professionals should be prepared and trained to
do procedures corret the s, at the right time of the interaction, to investigate the maximum of
information, especially because in some cases the patient may be in a state of criticality that
require intervention immediate medical attention. The s nurses are not allowed to make telephone
diagnostics and instead of that, their missions are just identify the signs and symptoms of patients
and classify them according to the severity, and therefore should refrain from trying to determine
what caused the symptoms, and warns that care in communication is essential so that patients
do not misinterpret the service and have the impression of having received
a diagnosis remotely. They reinforce the importance of teleattendance records, as there is a risk
that teletriatry nurses are subject to potential liability problems. They state that the insufficient
documentation of the teleattendance can generate possible medical-legal contingencies,
especially if it is vague, incomplete or the adherence to the protocols is not well demonstrated
and the orientation was not clear. Positive aspects of using the system with the patient's database:
o 24 hours a day, seven days a week; access for people with hearing impairments and people
who do not speak the language; r egistro of all calls in the system itself; the nurses' guidance
supported by a clinical decision support system; guarantee the patient confidentiality; r activity
and performance reports; ability to connect with other services and transfer calls; calls
answered immediately and small call abandonment rate. With this reinforces hands the
importance of investment in capacity building and training, knowing little time demand for
nurses can begin to use the system and for nurses to acquire skills needed to achieve the goals
and performances with use of the system and its database and data. 
The nurses' performances were assessed by the system based on criteria that can guarantee
patient safety: control of the situation; call log; obtaining relevant data; accuracy in data
recording; use of approved information and guidelines; primary assessment; identification of the
presented need; choice of direction; need to replace routing and closing and difficult call
management. With this, the need to use intelligent and reliable systems in the health area is more
than demonstrated.

## Telepidemiology
Telepidemiology is the application of telecommunications to epidemiological research and
application, including space and Internet-based systems. Telepidemiology applies satellite
communication systems to investigate or support investigations of infectious disease outbreaks,
including disease emergencies. In this way, space systems such as GIS, GPS and SPOT5 use
natural index and data to assess the health risk of human and animal populations. Space
applications of telepidemiology extend to surveillance and emergency response. That is, in the
field of epidemiological surveillance, models to predict the risk of epidemics can be established
by comparing satellite data resulting from environmental observation with remote sensing with
health data collected on land. Telepidemiology can be described as the survey, clarification of
doubts and dissemination of data on risks and diseases with the potential to generate epidemics,
with the support of information and communication technologies. One of the uses
in telepidemiologia, is observed tion of remote sensing images in what happens in the
environment for vector - borne diseases appear, that is, the means by which T ransmite a
disease. Telepidemiology identifies fauna, flora, aquifers, temperatures, atmospheric pressures
and growth of the population spot. With that, we can create preventive, predictive and reactive
models for a possible epidemic. Telepidemiology is a recent area that combines epidemiology
and space technology applied to human and animal health. It is an area of study
that allows a spatial and temporal study of events that affect the disease development process. It
involves the monitoring and control of the distribution of diseases in animals and humans
strongly linked to climate ee m environmental variations. The telepidemiologia is particularly
interesting for the study and monitoring of emerging diseases and vectors r and emerging, since
the transmission of viruses or bacteria by vectors whose population movements and are often
influenced by character ísticas environmental. We can detect, monitor and control outbreaks and
pandemics using information from the system database together with a global guidance system
such as GPS. Telepidemiologia is then usad the to model the spread of disease and map risks
of outbreaks and vector s know n the environmental changes. The picture analysis enables
rapid identification of specific locations and which can be used are for field validation of the
presence of a vector infected or outbreak of a disease. The images are useful for environmental
determination of sites involved in contamination. Invisible bacteria, for satellite is possible of the
space for detecting the sources of contamination and determinants involved in the transport
and transmission. The risk assessment is possible with the use of spatial
tools geographical and by integrating factors involved in the information based on the database
and system data, providing the information needed for decision making, management of public
health surveillance and control and disease. Internet-based telepidemiology applications include
providing epidemiological data for generating reports on the internet and mapping diseases in
real time. This involves collecting and structuring epidemiological data from the media and news
and mapping or disseminating that data for application in research or public health
organizations. Telepidemiology is studying the interaction between environment, climate and
health. With regard to epidemic monitoring, the merging of health data with environmental and
climatic data collected on the ground or by observation satellite with data on water, air, vegetation
and soil to be used to identify conditions that can cause disease and develop greater depth. The
use of space techniques in this field is a major step forward in the battle to prevent diseases
transmitted by water, air or carriers that cause millions of deaths each year worldwide. The
ultimate goal is to establish early warning systems to predict epidemics. Clinical
applications f ornece m real - time information on the prevalence of diseases among the
population to public health, medical and citizens around the world. It decreases the risk of
communicable diseases, mobilizing local medical efforts to respond to disease outbreaks,
especially in vulnerable populations. Increases the ability to manage the proliferation of
communicable pathogens. It can be used as a public health management tool to discover,
evaluate and act on epidemiological data. For example, gathering and identifying risk factors
relevant to the disease helps to identify treatment interventions and implement prevention
strategies that can decrease the effects of the outbreak in the general population and improve the
clinical results in the individual, at the patient level. It can be useful for commerce, travelers, public
health agencies and federal governments and diplomatic efforts. Public health agencies and
federal governments can take advantage of telepidemiology to predict the spread of
communicable diseases. Provides users and governments with information for early warning
systems. Relevant data can be used for research and is accessible via the system database. 
Data can be disseminated through disease outbreak reports for real-time disease mapping for
public use. Internet-based platforms can be used by the general public to determine outbreaks of
local and international diseases. The patients can also contribute their own relevant
epidemiological data for these services. Space telepidemiological initiatives, using satellites, are
able to collect relevant environmental information to track disease outbreaks. The information on
vegetation, meteorology and hydrology are relevant and, in conjunction with clinical data from
humans and animals, they can be used to build predictive mathematical models that may allow
the prediction of disease outbreaks. The system with information from its database is able to
aggregate information from several different sources to provide information on disease
surveillance and possible disease outbreaks. In conjunction with other systems collect information
in several different languages to collect epidemiological information worldwide. These services
are free and allow health professionals and lay people to access reliable information about
disease outbreaks from around the world and in real time. The system manages surveillance and
electronic alerts; makes the relationship between environment and
health; makes management disasters; early warning and epidemic
management; bio terrorism; remote ensortion and collection of environmental data for the
construction of risk prediction models for environmentally dependent diseases.

## How I Got The Concept & Information
Gathering such a type of information is very hard, but at the same time: Interesting. I mostly referred research papers by **M.I.T** and the [abpi.com]. I first understood that how the blockchain works and what exactly is decentralization. Later on, I read on the research papers provided by M.I.T to understand on how problems can be tackled using Blockchain technology for Covid 19. As an extra flavor, I also referred articles on **abpi**.

## Challenges I Ran Into
The hardest challange I ran into was about making all of this work. I have low (to zero) experience in coding and mostly in Blockchain. So, making this work was beyond my means. And thus, it's just an idea which can surely be executed. The next challenge was about getting information. I just couldn't go on a random website and copy-paste their material without even knowing what exactly it is. Thus, I read and made my own.

## Accomplishments That I'm Proud Of
The biggest accomplishment for me was that I was not even aware that what exactly is Blockchain and Data Lakes and how can I even use it to solve such a vulnerable purpose. And on top of that, I am a beginner in coding. So, first I had to learn a bit to understand the naming system and then I started with my research.

## What I Learned
I learnt that even if you are totally unaware of a subject or a field, you could still shine like a star in it. I also learnt about blockchain and many other topics like data lakes, telecom connectivity, html, css, data management, and a lot more.

## What's next for Covid Health Data Management
There is one and only future plan for this: **Make it a reality. Maybe not in a day or two, but surely sometime soon.**

