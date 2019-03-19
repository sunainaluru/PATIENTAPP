# PATIENTCONNECT
A full stack web application that allows users to search for currently active/enrolling clinical trials by medical condition or by zip code. PatientConnect aims to empower patients with information. With this information patients can choose to start the conversation about participating in cutting edge medical innovation, instead of waiting for their healthcare provider. PatientConnect integrates data and features from ClinicalTrials.gov API and Google Maps API.

### Access
PatientConnect has been deployed via AWS Lightsail and can be accessed via [this link](http://52.13.148.31).

### Tech Stack
Frontend: Javascript, Jinja, jQuery, Bootstrap, HTML, CSS
</br>
Backend: Python, Flask, SQLAlchemy, PostgreSQL, AWS LightSail
</br>
APIs: clinicaltrials.gov, Google Maps 

### Demo
Patients can search for specific conditions such as "bladder cancer" and then access the specific search results:
![alt text](https://github.com/sunainaluru/PATIENTCONNECT/static/READMEgifs/1.gif)


Patients can search for general condition categories such as "cancer" and then choose a specific condition from the generic search results:
![alt text](https://github.com/sunainaluru/PATIENTCONNECT/static/READMEgifs/giphy2.gif)

Patients can then see all the information provided about that trial from the clinicaltrial.gov API included how many patients are currently enrolled, what medications are used on this trial, what is the age range this trial accepts. Additionally, an zoom interactive Google Maps feature shows markers for the trial's locations worldwide:
![alt text](https://github.com/sunainaluru/PATIENTCONNECT/static/READMEgifs/giphy3.gif)
![alt text](https://github.com/sunainaluru/PATIENTCONNECT/static/READMEgifs/giphy4.gif)

The most exciting features of this app is that the user is able to search for trials by zipcode proximity. Say someone has Chron’s disease and they live near San Jose, zipcode 95129. They would like to know what trials are near to them so they can try different medications for their condition. Now they will see all of the detailed information that will help them determine if they are eligible for the trial or not, or if the medications are of any interest to them. Here you can see not only the trial’s sites near San Jose, but also where the same trial is being conducted worldwide. 
![alt text](https://github.com/sunainaluru/PATIENTCONNECT/static/READMEgifs/giphy5.gif)
![alt text](https://github.com/sunainaluru/PATIENTCONNECT/static/READMEgifs/giphy6.gif)
![alt text](https://github.com/sunainaluru/PATIENTCONNECT/static/READMEgifs/giphy7.gif)


### Future Features
* Add more categories for searching database (i.e. search by age range or by medication)
* Add more interactivity with the google maps feature with more filters (i.e. search map by condition)
