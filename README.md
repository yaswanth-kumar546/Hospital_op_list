****📝 Program Explanation****
This Python program simulates a simple Hospital Outpatient (OP) Registration System. It allows hospitals to register patients and automatically assign them a unique OP number.
Key Components:
- Class HospitalOPSystem
- __init__: Initializes the system with current_op_number = 0 and an empty patient list.
- register_patient(patient_name):
- Increments the OP number by 1.
- Creates a dictionary entry with the patient’s name and OP number.
- Stores the entry in the patient list.
- Returns the patient’s registration details.
- show_all_patients(): Prints all registered patients with their OP numbers.


- Main Program (if __name__ == "__main__":)
- Runs an interactive loop where users can enter patient names.
- Assigns and displays OP numbers for each patient.
- Stops when the user types "exit".
- Finally, displays all registered patients.



**example flow:**
Enter patient name (or 'exit' to stop): John
Patient Registered: John | OP Number: 1

Enter patient name (or 'exit' to stop): Alice
Patient Registered: Alice | OP Number: 2

Enter patient name (or 'exit' to stop): exit

**All Registered Patients:**
OP No: 1 | Name: John
OP No: 2 | Name: Alice


**Future Improvements**
- Add patient details (age, gender, contact info)
- Save data to a file or database
- Search and update patient records
- user friendly access controlled

