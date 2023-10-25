# COS20019_Cloud_Computing_Architecture_Swinburne_2023
Assignments of COS20019 Cloud Computing Architecture
School of Science, Computing and Engineering Technologies
Unit Outline
COS20019
Cloud Computing Architecture
Semester 2 2023
Please read this Unit Outline carefully. It includes:
PART A Unit summary
PART B Your Unit in more detail
PART C Further information
COS20019_Unit Outline_S2_2023_UG Page 2 of 11
Version: Unit OutlineTemplate v4.0 2023
PART A: Unit Summary
Unit Code(s) COS20019
Unit Title Cloud Computing Architecture
Duration One semester
Total Contact Hours 48 (2 hrs online session and 2 hrs lab class per wk)
Requisites:
Pre-requisites 50 cp in the degree
Co-requisites Nil
Concurrent pre-requisites Nil
Anti-requisites
Assumed knowledge Familiarity with PHP, database concepts and SQL
Credit Points 12.5
Campus/Location Hawthorn
Mode of Delivery Blended, assignments, labs and tests. See details below.
Assessment Summary HED Graded Mark
Aims
This unit covers generic principles of "everything as a service" in cloud computing, plus
practical work doing design and development for one or more contemporary platforms, which
may vary from year to year. Cloud computing undergoes constant evolution, and there are
several competing platforms, such as Amazon Web Services.
Unit Learning Outcomes
Students who successfully complete this Unit should be able to:
1. Explain the principles and value of cloud computing
2. Create and manage cloud services using a cloud management platform.
3. Implement and deploy a cloud-based web site that is reliable, scalable, secure
and cost effective.
4. Research available cloud services, then design and justify an architectural
solution that uses these services.
Graduate Attributes
This unit may contribute to the development of the following Swinburne Graduate Attributes:
§ Communication skills
§ Teamwork skills
§ Digital literacies
Content
§ Introduction to cloud computing
§ Software as a Service (SaaS), Platform as a Service (PaaS), Infrastructure as a
Service (IaaS)
COS20019_Unit Outline_S2_2023_UG Page 3 of 11
Version: Unit OutlineTemplate v4.0 2023
§ Data management in the cloud
§ Virtualisation
§ Security and privacy in the cloud
§ State-of-the-art/practice R&D in the cloud
AWS Academy
This unit uses materials and infrastructure provided by Amazon Web Services (AWS) and
partners. It covers knowledge required for AWS Cloud Practitioner and Solutions Architect
(Associate) certifications. Swinburne is accredited to run this unit as part of the AWS
Academy Program.
Passing the Certification exams may require additional knowledge of AWS services for which
additional study and exam preparation is recommended.
Successful completion of this unit enables you to get access to free practice exams and
discounted certification exam vouchers from AWS.
COS20019_Unit Outline_S2_2023_UG Page 4 of 11
Version: Unit OutlineTemplate v4.0 2023
PART B: Your Unit in more detail
Unit Improvements
Feedback provided by previous students through the Student Survey has resulted in
improvements that have been made to this unit. Recent improvements include:
• Updated materials and assignments
Unit Teaching Staff
Name Role Email Consultation
Bijan Raminzad Unit Convenor
Lecturer
braminzad@swin.edu.au By appointment
Afzal Azeem Chowdhary
Ambrose Phey
Daniel Doan
Gamunu Dassanayake
Harsharan Kaur
Howard Hao
Jayson Paul
Man Lau
Matthew Mulvaney
May Yeo
Md Arafat Hossain
Mohammed Aquib
Naveed Ali
Naveed Ali
Phu Long Dinh
Ramya Kalivarapu
Sasikanth Alla
Thrisen Punithan
Waqar Khan
Lab Instructor Contact via Canvas By appointment
Learning and Teaching Structure
Activity Total Hours Hours per Week Teaching Period Weeks
Live Sessions 24 hours 2 hours Weeks 1 to 12
Tutorials 24 hours 2 hours Weeks 1 to 12
Independent
Learning
102 hours 8.5 hours Weeks 1 to 12
COS20019_Unit Outline_S2_2023_UG Page 5 of 11
Version: Unit OutlineTemplate v4.0 2023
Week by Week Schedule
Week Week
Beginning Teaching and Learning Activities Student Task or Assessment
1 31 Jul • Overview of the unit
• Introduction to cloud computing
o Virtualisation
o Cloud providers
o SaaS, PaaS, IaaS
• Overview of AWS infrastructure and
services.
Accessing AWS resources
Intro to Linux
2 7 Aug • Compute services
o Virtual machines – EC2
o Serverless computing - Lambda
o Other compute services
• Container-based/Serverless services
ACF Lab 3: Introduction to EC2 (~45 min)
3 14 Aug • Network services
o Virtual Private Cloud - subnets
o Security groups firewalls
o Designing your Environment
o Content Delivery Networks and
caching – Cloud Front
ACF Lab 2: Build a VPC and launch a
Web Server (~45 min)
ACA Module 11 Guided Lab - Streaming
Dynamic Content using Amazon
CloudFront (~30 min)
4 21 Aug • Storage services
o File Storage – EBS, EFS
o Object storage – S3, Glacier
• Web accessible content on S3
Assignment 1a Due - Progress check
ACF Lab 4: Working with EBS (~45 min)
Lab Exercise - Create a publicly
accessible S3 web page
5 28 Aug • Database services
o SQL and NoSQL databases
o RDS
o DynamoDB
o Other databases
ACF Lab 5: Build your DB Server and
interact with your DB using an App (~45
min)
6 4 Sep • Security
o Access Control concepts
o AWS IAM
o Authorization using Policies
o Securing your AWS account
o AWS Authentication
o Securing Data
o Auditing
Assignment 1b due
ACF Lab 1: Intro to AWS IAM (~45 min)
.
Assignment 2 Q & A.
Mid-Semester Break 11 Sep to 17 Sep (inclusive)
7 18 Sep • Scalable Architectures
o HA, Scaling and Fault tolerance
o Scaling to Demand
o Elastic Load Balancing
o Cloud Watch
o Auto-scaling
MCQ Test 1
ACF Lab 6: Scaling and Load Balance
your architecture App (~45 min)
8 25 Sep • Scaling (part 2) and Automation
o Fault tolerance
o Load balancing
o Scaling policies
o Lambda
• Automating Infrastructure
o Cloud Formation
ACA Lab Mod 9: Creating a
Highly Available Environment (~60 min)
ACA Lab Mod 10: Automating
Infrastructure Deployment with AWS
CloudFormation (~20 min)
COS20019_Unit Outline_S2_2023_UG Page 6 of 11
Version: Unit OutlineTemplate v4.0 2023
9 2 Oct • Decoupling applications
o Interaction paradigms
• Request-response
• Message driven/Event driven Archs
• Serverless apps - Lambda
Assignment 2 due
ACA Lab Mod 13: Implementing a
Serverless Architecture with AWS
Lambda (~30 min)
ACA Lab Mod 13: Implementing a
Serverless Architecture for the Cafe (~45
min)
10 9 Oct • DNS routing – Route53
• Design Patterns and Sample
Architectures
ACA Lab Mod 9 - Creating a Scalable and
Highly Available Environment for the Cafe
11 16 Oct • Architecture Evaluation
o Reliability
o Security
o Performance
o Cost
Assignment 3 discussion
12 23 Oct Assignment 3 presentation
MCQ Test 2
Assignment 3 due
Assessment
a) Assessment Overview
Tasks and
Details
Individual
or Group
Assessment
Prerequisite
Weighting Unit Learning
Outcomes that
this assessment
task relates to
Assessment
Due Date
Labs Individual None 20% 2, 3, 4 Weeks 2 - 11
Assignment
1a
Individual None 5% 2, 3 Week 4
Assignment
1b
Individual None 10% 2, 3 Week 6
Online Tests
1 and 2
Individual None 30% 1, 2, 3, 4 Week 7, 12
Assignment 2 Individual Genuine attempt1
for Assignments
1a, 1b, Labs and
Tests
15% 2, 3 Week 10
Assignment 3
(Design
Project)
Group of 2
or 3 students
Genuine attempt1
for Assignment 2
15% 2, 3, 4 Week 12
Assignment 3
presentation
Group of 2
or 3 students
Genuine attempt1
for Assignment 3
5% 2, 3, 4 Week 12
Interviews may
extend over
into Week 13
1
A genuine attempt in the context of student assignments refers to a sincere and earnest effort made
by a student to complete a given task. It implies that the student has devoted adequate time, energy,
and thought process towards understanding, addressing the requirements and submission of the
assignment.
COS20019_Unit Outline_S2_2023_UG Page 7 of 11
Version: Unit OutlineTemplate v4.0 2023
I. Labs:
Weekly labs and practical deployments can be submitted and marked by:
Live demonstration during your lab session. Your lab instructor would
observe your deployment and may ask simple questions.
OR
Lab report submission via Canvas. Lab reports must be written in IEEE
standard format, including relevant screenshots and explanations for each
step.
NOTE: Lab online submissions have deadlines (up to 7 days after your lab
class). Late submission and due date extensions are NOT applicable for lab
submissions.
II. Multiple Choice Questions Test 1 (MCQ Test 1):
No resit for this assessment if failed. Answer keys will not be published to
students.
III. Multiple Choice Questions Test 2 (MCQ Test 2):
Resit for this assessment is available only to students with an average mark less
than 50. Answer keys will not be published to students.
b) Minimum requirements to pass this Unit
To pass this unit, you must:
• achieve an overall mark for the unit of 50% or more
c) Examinations
If the unit you are enrolled in has an official examination, you will be expected to be
available for the entire examination period including any Special Exam period.
d) Submission Requirements
Assignments and other assessments are generally submitted online through the Canvas
assessment submission system which integrates with the Turnitin plagiarism checking
service.
Please ensure you keep a copy of all assessments that are submitted.
In cases where a hard copy submission is required an Assessment Cover Sheet must
be submitted with your assignment. The standard Assessment Cover Sheet is available
from the Current Students web site (see Part C).
e) Extensions and Late Submission
Late Submissions - Unless an extension has been approved, late submissions will result
in a penalty. You will be penalised 10% of your achieved mark for each working day the
task is late, up to a maximum of 5 working days. After 5 working days, a zero result will
be recorded.
f) Referencing
To avoid plagiarism, you are required to provide a reference whenever you include
information from other sources in your work. Further details regarding plagiarism are
available in Section C of this document.
Referencing conventions required for this unit are: Any as long as consistent
Helpful information on referencing can be found at
http://www.swinburne.edu.au/library/referencing/
COS20019_Unit Outline_S2_2023_UG Page 8 of 11
Version: Unit OutlineTemplate v4.0 2023
g) Groupwork Guidelines
A group assignment is the collective responsibility of the entire group, and if one
member is temporarily unable to contribute, the group should be able to reallocate
responsibilities to keep to schedule. In the event of longer-term illness or other serious
problems involving a member of group, it is the responsibility of the other members to
notify immediately the Unit Convenor or relevant tutor.
All group members must be satisfied that the work has been correctly submitted. Any
penalties for late submission will generally apply to all group members, not just the
person who submitted.
Required Textbook(s)
NA
Recommended Reading Materials
The Library has a large collection of resource materials, both texts and current journals. Listed
below are some references that will provide valuable supplementary information to this unit. It
is also recommended that you explore other sources to broaden your understanding.
Implementing AWS: Leverage AWS Features to Build Highly Secure, Fault-Tolerant,
and Scalable Cloud Environments
Wadia, Yohan ; Udell, Rowan ; Chan, Lúcás ; Gupta, Udita
Birmingham: Packt Publishing, Limited; 2019
COS20019_Unit Outline_S2_2023_UG Page 9 of 11
Version: Unit OutlineTemplate v4.0 2023
PART C: FURTHER INFORMATION
Student behaviour and wellbeing
All students are expected to: act with integrity, honesty and fairness; be inclusive, ethical and
respectful of others; and appropriately use University resources, information, equipment and facilities.
All students are expected to contribute to creating a work and study environment that is safe and free
from bullying, violence, discrimination, sexual harassment, vilification and other forms of unacceptable
behaviour.
The Student Charter describes what students can reasonably expect from Swinburne in order to enjoy
a quality learning experience. The Charter also sets out what is expected of students with regards to
your studies and the way you conduct yourself towards other people and property.
You are expected to familiarise yourself with University regulations and policies and are obliged to
abide by these, including the Student Academic Misconduct Regulations, Student General
Misconduct Regulations and the People, Culture and Integrity Policy. Any student found to be in
breach of these may be subject to disciplinary processes.
Examples of expected behaviours are:
• conducting yourself in teaching areas in a manner that is professional and not disruptive to
others
• following specific safety procedures in Swinburne laboratories, such as wearing appropriate
footwear and safety equipment, not acting in a manner which is dangerous or disruptive (e.g.
playing computer games), and not bringing in food or drink
• following emergency and evacuation procedures and following instructions given by
staff/wardens in an emergency response
Canvas
You should regularly access the Swinburne learning management system, Canvas, which is available
via the Current Students webpage or https://swinburne.instructure.com/ Canvas is updated regularly
with important unit information and communications.
Communication
All communication will be via your Swinburne email address. If you access your email through a
provider other than Swinburne, then it is your responsibility to ensure that your Swinburne email is
redirected to your private email address.
Academic Integrity
Academic integrity is about taking responsibility for your learning and submitting work that is honestly
your own. It means acknowledging the ideas, contributions and work of others; referencing your
sources; contributing fairly to group work; and completing tasks, tests and exams without cheating.
Swinburne University uses the Turnitin system, which helps to identify inadequate citations, poor
paraphrasing and unoriginal work in assignments that are submitted via Canvas. Your Unit Convenor
will provide further details.
Plagiarising, cheating and seeking an unfair advantage with regards to an exam or assessment are all
breaches of academic integrity and treated as academic misconduct.
Plagiarism is submitting or presenting someone else’s work as though it is your own without full and
appropriate acknowledgement of their ideas and work. Examples include:
• using the whole or part of computer program written by another person as your own
For further information on any of these topics, refer to Swinburne’s Current
Students web page http://www.swinburne.edu.au/student/.
COS20019_Unit Outline_S2_2023_UG Page 10 of 11
Version: Unit OutlineTemplate v4.0 2023
• using the whole or part of somebody else’s written work in an essay or other assessable
work, including material from a book, journal, newspaper article, a website or database, a set
of lecture notes, current or past student’s work, or any other person’s work
• poorly paraphrasing somebody else’s work
• using a musical composition or audio, visual, graphic and photographic work created by
another
• using realia created by another person, such as objects, artefacts, costumes, models
• submitting assessments that have been developed by another person or service (paid or
unpaid), often referred to as contract cheating
• presenting or submitting assignments or other work in conjunction with another person or
group of people when that work should be your own independent work. This is regardless of
whether or not it is with the knowledge or consent of the other person(s). Swinburne
encourages students to talk to staff, fellow students and other people who may be able to
contribute to a student’s academic work but where an independent assignment is required,
the work must be the student’s own
• enabling others to plagiarise or cheat, including letting another student copy your work or by
giving access to a draft or completed assignment
The penalties for academic misconduct can be severe, ranging from a zero grade for an assessment
task through to expulsion from the unit and, in the extreme, exclusion from Swinburne.
Student support
Swinburne offers a range of services and resources to help you complete your studies successfully.
Your Unit Convenor or studentHQ can provide information about the study support and other services
available for Swinburne students.
Special consideration
If your studies have been adversely affected due to serious and unavoidable circumstances outside of
your control (e.g. severe illness or unavoidable obligation), you may be able to apply for special
consideration (SPC).
Applications for Special Consideration will be submitted via the SPC online tool normally no later than
5.00pm on the third working day after the submission/sitting date for the relevant assessment
component.
Accessibility needs
Sometimes students with a disability, a mental health or medical condition or significant carer
responsibilities require reasonable adjustments to enable full access to and participation in education.
Your needs can be addressed by Swinburne's AccessAbility Services by negotiating and distributing
an 'Education Access Plan'. The plan makes recommendations to university teaching and
examination staff. You must notify AccessAbility Services of your disability or condition within one
week after the commencement of your unit to allow the University to make reasonable adjustments.
Review of marks
An independent marker reviews all fail grades for major assessment tasks. In addition, a review of
assessment is undertaken if your final result is between 45 and 49 or within 2 marks of any grade
threshold.
If you are not satisfied with the result of an assessment, you can ask the Unit Convenor to review the
result. Your request must be made in writing within 10 working days of receiving the result. The Unit
Convenor will review your result to determine if your result is appropriate.
If you are dissatisfied with the outcomes of the review, you can lodge a formal complaint.
Feedback, complaints and suggestions
In the first instance, discuss any issues with your Unit Convenor. If you are dissatisfied with the
outcome of the discussion or would prefer not to deal with your Unit Convenor, then you can complete
a feedback form. See https://www.swinburne.edu.au/corporate/feedback/
COS20019_Unit Outline_S2_2023_UG Page 11 of 11
Version: Unit OutlineTemplate v4.0 2023
Advocacy
Should you require assistance with any academic issues, University statutes, regulations, policies and
procedures, you are advised to seek advice from an Independent Advocacy Officer at Swinburne
Student Life.
For an appointment, please call 03 9214 5445 or email advocacy@swin.edu.au For more
information, please see https://www.swinburne.edu.au/current-students/student-services-
support/advocacy/
