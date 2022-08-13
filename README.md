# Investigation of the Medical Appointment No-show dataset


        
## Introduction

In this project the Medical Appointment No-show data set is explored, albeit on a brief note. The dataset contains information on patients' attitude toward medical appointment schedules. Even more interesting is that the dataset contains information on Brazilian nationals who are enrolled on the [Bosla Familia] (https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia). A program which financially supports families with a focus on mitigating the adverse effects of poverty. I shall be investigating the significance of this scholarship on patients' response to medical appointment schedules. The dataset spans 2015-2016.

---

### Structure of the data
    
The Medical Appointment No-show dataset contains 110527 rows and 14 columns. Columns in the dataset include;
PatientId: Patient Identication
AppointmentID: Identification of each appointment
Gender: Whether patient is Male or Female
ScheduledDay: Day of week appointment is scheduled
AppointmentDay: Day of appointment
Age: Patient age 
Neighbourhood: Where appointment takes place
Scholarship: True or False [Bosla Familia] (https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia)
Hipertension: Whether patient has hypertension (True or False)
Diabetes: Whether patient has diabetes (True or False
Alcoholism: Whether patient is alcoholic (True or False)
Handcap: Whether patient is handdicaped (True or False)
SMS_received: Message sent to patient 
No-show: whether patient showed up for appointment schedule (True or False)

---

### Motivation

Questions of interest to be addressed in this analysis are as follows;
1. What is the average age of people who showed up for their medical appointments? 
2. Are patients enrolled on scholarship more likely to show up for their medical appointments?
3. Which day in the month recieves the most appointment schedules?

---

### Conclusion

From the analysis of the dataset based on the research questions, it was discovered that the age distribution of patients who 
kept to their appointment schedules and patients who did not are similar. With older patients tending not to keep to 
their schedules far more than the younger patients. The analysis however, did not try to investigate this pattern.  I will also add that females tend to be more proactive in terms of making use of health care provisions. The investigation also indicates that patients on scholarship tend to miss their appointment sechedules far more than patients who are not on scholar
ship. In addition, the number of daily appointment schedules over the years seems to be fairly constant from 2015 to 2016, with the 2, 3, and 6 days having the highest appointments, and the 21, 22, and 23 days having the least appointment schedules. This analysis is limited to the research questions, with no further investigations of the findings. A possible limitation of conclusions based on this analysis might be the data sampling technique. The dataset does not seem to be representative by equal proportion of the gender of the entire population of patients to the health care facility. There seem to have been some bias in the sample collection process resulting in large amount of samples from one category (__female__) of the population, which might not allow for generalization of results from this analysis. Hence, improvement could be made in the results by applying more robust sampling techniques. 
