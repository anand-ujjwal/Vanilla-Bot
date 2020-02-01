##SDMCET ADMISSION ASSIST BOT(VANILLA)

#ABSTRACT
The communication of potential students with the college is performed manually
and it is a very time consuming procedure. The opportunity to communicate with on a
one-to-one basis is highly valued. However with many hundreds of applications each
year, one-on-one conversations are not feasible in most cases. The communication
will require a member of academic staff to spend several hours to find suitable
answers and contact each student. It would be useful to reduce his costs and time.
The project aims to reduce the burden on the head of admissions, and potentially
other users, by developing a convincing chatbot . A suitable algorithm must be
devised to search through the set of data and find a potential answer. The program
then replies to the user and provides a relevant web link if the user is not satisfied by
the answer. Furthermore a web interface is provided for both users and an
administrator. Basic registration will also be offered using the bot for the initial
admission processes.

#OBJECTIVE
1. To make admission related enquiry efficient.
2. To reduce student’s time and effort involved in admission procedure.
3. To reduce staff' time and effort involved in attending the new students one-to-one.
4. 365X24X7 Support — Unlike support staff, Chatbots don’t need any breaks, they
happily work and learn 24 hours a day. They have a robust cloud architecture.
5. Reduce operational and service expense.
6. Eliminate mobile app-fatigue
7. Multiply reach, increase breadth and depth of engagement

#PROBLEM STATEMENT
To build an admission assist BOT named VANILLA that will help the students to query their
problems that generally occurs during the time of admissions in the college. Queries can be
regarding the admission procedure , fees , course plan , program outcome , college
accreditations , facilities available in the campus , placements , etc.
The bot will also offer a basic registration of the student by providing the token number for
each new registration. The token number can further be used during the admission process
and to get the form status.

#HARDWARE REQUIREMENTS
1. i3 Based processor or higher preferred
2. Memory : 1 GB RAM or higher preferred
3. Hard Drive : 50 GB or higher preferred

#SOFTWARE REQUIREMENTS
1. Windows 7 or higher preferred
2. nodeJs
3. ExpressJs
4. Javascript
5. Code Editor
6. Web Browser(heroku/aws lambda,dialogflow)

#FUNCTIONAL REQUIREMENTS

1. Chatting:
a. The system should allow users to chat.
b. The system shall inform the user if an answer is not available.
c. The system shall inform the user about spelling mistakes.
d. The system shall inform the user about the validity of the sentence.

2. Searching:
a. The system should allow users to search for information about admissions.
b. The system should allow users to search for information about tuition fees.
c. The system should allow users to search for information about accommodation.

3. Logs:
a. The system should maintain a log of the current question and answer if the user is
not satisfied.

4. Feedback:
a. The user should be able to leave feedback, which is comprised of a text message
and a rating.

5. Administrative system
a. Information management: The administrator should be able to add, update and
delete questions, answers and keywords.
b. Log management: The administrator should be able to view and delete logs.
c. Feedback management: The administrator should be able to view and delete
feedback.

#NON-FUNCTIONAL REQUIREMENTS

1. User Interface:
a. The system shall maintain an easy to use interface across all functionality and for
all users
b. The clients’ user interface should be compatible with all commonly used browsers,
such as Internet Explorer, Firefox, Google Chrome and Safari.

2. Scalability:
a. The system shall be able to scale based on the number of users .

3. Security:
a. The administrative system should be protected from unauthorized access.
b. The database should be protected from attacks and unauthorized access.
c. The interface should be protected from attacks.
d. All passwords should be stored as a secure hash of the administrator password.

4. Third party interactions:
a. The system should be able to interact with the Google sheets API, which handles
the storage of the registration data of students.
b. The system should be able to interact with the Heroku/AWS Lambda, which is used
for the storage of downloadable items and the code.

5. Portability:
a. The system should run on a variety of operating systems that support any browser.
b. The system should run on a variety of hardware.

6. Maintainability:
a. The system should be easy to maintain.
b. There should be a clear documentation of the code written along with the proper
description of the methods.

7. Exception handling:
a. Exceptions should be reported effectively to the user if they occur.

8. Ethics:
a. The system shall not store or process any information about its users.

#METHODOLOGY
The design and development of the system followed the waterfall model as described below.

The waterfall model follows a series of processes, which are used during development.
Usually the stages will require the gathering of requirements and their analysis. The design of
the system is the next stage, followed by coding the actual system. Then evaluation, testing
and debugging, if necessary, is the next step. Finally the system will either be accepted and
therefore maintained or rejected. It is vital to move to the next process of the waterfall model
if the previous step has been completed.

#VERSIONING
Version 1.0 : Using regular expression
1) Implementing basic intents and cards using dialogflow(Without Code)
2) Coding and refining the answers i.e. redefining the basic model using JavaScript
3) Connecting it with third party API's like google sheets to store and retrieve the data.
4) Hosting it on HEROKU/AWS Server.
5) Testing
Version 2 : Using machine learning to train the model
1) Training the ML model with available intents to improve the prediction of possible FAQs.
2) Refinements of the answers provided.
3) Hosting
4) Testing
9
Version 3 : Additional features to be offered
1) Providing FAQs as button at the beginning
2) If user's entered intent is not matched then all the possible questions will be provided
3) Dynamic string matching while writing intent
4) Downloading and uploading of media files
5) Testing

#OUTCOME OF THE PROJECT
The produced BOT introduces an efficient way for students to query the problems they are
facing while admissions(FAQs).
The system proposed by us will run on many platforms like college’s website, facebook page,
whatsapp as well as the telegram channel.
This system also provides the online registration of the candidates, along with this it gives all
the brochures and further required forms to be filled by the user in a downloadable format.
The registration details taken by the bot will be directly stored in the GOOGLE SHEETS in
an editable format.
The student is also allowed to check his/her registration status by entering the unique ID
number provided at the time of registration.
Based upon machine learning the bot will continuously train itself with respect to time and
number of questions asked to it.This will refine the possible answers to the asked questions as
well as the FAQs.

#REFERENCES
IRCTC Website -
https://www.irctc.co.in/nget/train-search
Cornell University Computer Science Research Papershttps://
arxiv.org/abs/1408.6762
DIALOGFLOW Documentationhttps://
cloud.google.com/dialogflow/docs
nodeJS Documentation -
https://nodejs.org/en/docs/
2019 International Electronics Symposium (IES) Research Paperhttps://
sci-hub.tw/downloads/2019-11-
30/fd/10.1109@ELECSYM.2019.8901559.pdf?rand=5e2dd421a4952#view=FitH
DIALOGFLOW EBOOKhttps://
storage.googleapis.com/static-content-bucket-ucan/ebook/ebook_beta.pdf
Dinus Intelligent Assistance (DINA) Chatbot for University Admission Serviceshttps://
ieeexplore.ieee.org/abstract/document/8549797
Chatbot for education systemhttps://
pdfs.semanticscholar.org/b6fa/ce25015cbc558742f1f0dd66954b6645d86c.pdf
