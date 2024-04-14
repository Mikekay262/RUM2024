About the datasets used in this project

# Data to be analyzed:
Dataset file name: data.csv

##About the dataset
The data contains Patient Consultation Details From 01-12-2023 To 31-12-2023	
																																																		
## The Features of the dataset are as follows:
																																																		
Sr.No.: This is the serial number of the patient
Schedule Date: The date the appointment was scheduled		
Patient Name: The patient's name		
Age: The patient's age	
Gender	: The patient's gender
Modality: The patient's modality during the visit	
Provisional Diagnosis: The prescriber's provisional diagnosis for the patient
Principal Diagnosis: The prescriber's principal diagnosis for the patient	
Additional Diagnosis: The any additional diagnosis for the patient 
Medicine Prescribed: These are the drugs prescribed for the patient. This feature contains a list of drugs in the format "Tramadol [ Tramadol  | 50Mg | Capsule | BDS |  For 5 Days  ], Paracetamol (500 mg)[ Paracetamol | 500 mg | Tablet | TID |  For 5 Days  ],..." with "," as a separator between individual drug items.
after the name of each drug item in the said list, it is followed by details about it's generic name, strenght, dosage form, frequency and duration enclosed in "[]", with "|" as a separator between each value.


# Reference Databases
## 1. Dataset filename: antibiotics.csv

### About the dataset
This dataset contains antibiotics and their class
source: https://www.who.int/publications/i/item/WHO-MHP-HPS-EML-2023.04

### The Features of the dataset are as follows:
Antibiotic: The name of the antibiotic
Class: The class of the antibiotic

## 2.  Dataset filename:EML_2017.csv 

### About the dataset
This dataset contains a list of drugs included in the Essential Medicines list of Ghana

### The Features of the dataset are as follows:
Name of Drug: The name of the drug
Formulation: The dosage form of the drug
Strength: the strenght of the drug
