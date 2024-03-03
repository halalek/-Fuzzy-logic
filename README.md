# Fuzzy Logic
Build an expert system to diagnose a patient's illness based on symptoms, age, and medical history We built two systems for heart disease and diabetes based on Fuzzy logic .

The system displays an interface for the user to enter age, medical history, and symptoms
Accordingly, the disease is diagnosed and the result is shown to the user.

A system has been built for each disease, treating its cases, setting its own rules, and building an interface for it

## System design :
### 1-  Diagnosing heart disease based on age, medical history, and symptoms:
#### System Input:
![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/04431881-6e98-4abd-92cb-33dc8dba7a03)

#### System output: Diagnose the type of heart disease healthy,sick1,sick2,sick3,sick4.

#### The system goes through stages :

1- Fuzzification (Linguistic Term):

2-Rules Construction :

3-Fuzzy Inference System:

4-Defuzzification:

5-Testing and validation :

##### Membership Function  :
Both Trapezium and Triangle were applied to the input and output and obtained good accuracy

###### Membership Function for inputs :

![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/a2682836-3552-490f-921a-32073e6207d6)

###### Membership Function for output:
![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/47a434e8-4501-4d0d-80df-834b73acc538)

##### User Interface: 
The user first enters maximum heart rate, then low-density lipoprotein (LDL) cholesterol, systolic blood pressure, resting ECG, and age.
Then press the Evaluate button
Then the output chart is displayed, and the output (bottom of the chart image) indicates the types of heart disease in the patient. It is a text value that indicates the type of risk (type of heart disease), either healthy or sick1 or sick2 or sick3 or sick4
![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/470af248-9071-4b9b-8426-24aa2437c39e)





### 2-Diagnosis of Diabetes based on age, medical history, and symptoms:
#### The system Input: age - glucose concentration - body mass - history of diabetes for a specific person.

![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/c7306cda-869a-43a4-a9b8-438cfc50ec44)

#### System output: Diabetic or non-diabetic .

#### The system goes through stages :

1- Fuzzification (Linguistic Term):

2-Rules Construction :

3-Fuzzy Inference System:

4-Defuzzification:

5-Testing and validation :

##### Membership Function  :
Both Trapezium and Triangle were applied to the input and output and obtained good accuracy

###### Membership Function for inputs :

![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/5d498599-9d75-449c-9a21-d25594dca717)
![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/861153f1-9589-40d2-a0fd-fd2bbbeb27d8)

###### Membership Function for output:
![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/ef34d94e-b4f7-4a18-a077-dce80b1a89bc)

##### User Interface: 
The user first enters the body mass index or enters height and weight to calculate the body mass, then glucose concentration, then age, then the history of diabetes for a specific person.

Then press the Evaluate button
Then the output chart is displayed, and the output (below the chart image) indicates stage of diabetes
![image](https://github.com/halalek/-Fuzzy-logic/assets/112726630/89c5b8e1-475e-47b3-9b72-853646200827)



