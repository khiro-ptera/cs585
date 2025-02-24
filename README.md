# CS585: Assignment 1

**Author:** Steven Xie
---

## Rationale:
I created this ER diagram to most conveniently organize entities in a way that clearly provides the monthly costs and revenue of running the dental business.
This allows a streamlined approach to maximizing ROI, because who doesn't love money?
A dentist business must employ staff, buy equipment (including software and misc supplies), and rent offices. 
Each staff must undergo some form of training, with variable time and monetary costs. 
Rent, training, salary, and equipment costs are all incurred monthly. 


Patients and doctors schedule appointments for treament/operation, which must occur in unoccupied rooms. 
Each operation involves only one patient, and can involve one or more doctors. 
A treatment will cost the patient a bill, which usually is paid mostly by the insurance that covers the patient. 
This paid bill goes toward the monthly revenue. 

## Additional relations:
Doctors may hold lisences that may have an expiration date, which must be tracked by the business.
The business must track the insurance of its patients, including the coverage type. 
