# Missing-medical-appointments
> Not showing up is an issue that can increase the bottlenecks in the healthcare system. The No Show dataset conatins 100,000+ appointments along with demograghic and health infromation about the patinets. 
>
**The main aim of this analysis is to invesitgate determinates of missing medical appointments.** The analysis attempt to answer the following questions 
>
>**1) What are the demographic pridectors for missing a medical appointment?**
>
>**2) What are the health related pridectors for missing a medical appointment?**
>
> The dataset has 13 coloumns, the following is the description of the variables included in the dataset:
>>**PatientId** is a unique identifier for the patients in the dataset
>
>>**AppointmentID** is a unique identifier for the booking episode in the dataset
>
>>**Gender** is the gender of the patinet 
>
>>**ScheduledDay** is the date and time of booking 
>
>>**AppointmentDay** is the date and time of actual appointment 
>
>>**Age** is the age of the patient 
>
>>**Scholarship** is whether the patient is covered under a health insurance
>
>>**Hypertension** is whether the patient has Hypertension 
>
>>**Diabetes** is whether the patient has Diabetes 
>
>>**Alcoholism** is whether the patient suffers from an alcohol problem 
>
>>**Handicap** is the level of disability of the patient 
>
>>**SMS received** indicates if the patient recievd a reminder for the appointment via SMS 
>
>>**No-show** this vraible describes whethere the patient showed up for the appoint or not. To avoid counter-intuation, this variable will be recoded as a new varible called **Showed** where *Yes* means the patient showed up for the medical appointment and *No* means that the patient did not show up.

The following features have been engineered:

>>**No_of_Appointments** indicates the number of appointemnts each patient has 
>
>>**AppointmentWeekDay** indicates which day of the week was the appointment on 
>
>>**WaitingTime** indicates the difference between schedualing date and appointment date 
