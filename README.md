# Student Management System

## Functionality

Here is a detailed overview of the functions included in this script:

### 1. Register Student:
   - Purpose: Allows the user to register a new student in the cohort.
   - Usage: Users will be prompted to enter the student's email, age, and student ID. The script validates the email and checks for duplicate student IDs.

### 2. Update Student Record:
   - Purpose: Enables users to update a student's email and age based on their ID.
   - Usage: Users will provide the student's ID, and if the ID exists, they can enter a new email and age. Email format is validated.

### 3. Delete Student:
   - Purpose: Permits users to delete a student's record based on their ID.
   - Usage: Users provide the student's ID to be deleted. If the ID exists, the record is removed from the list.

### 4. View All Students:
   - Purpose: Displays the complete list of students in the cohort.
   - Usage: The script shows the list of students. If the list is empty, it prompts the user to add new students.

### 5. Extract and Sort Emails:
   - Purpose: Initiates the process of saving student emails in ascending order.

### 6. View Extracted Emails:
   - Purpose: Displays the extracted and sorted student emails.

### 7. Backup Data:
   - Purpose: Provides an option to back up data to an online server or backup directory.
   - Usage: Users are prompted to confirm the backup operation. If confirmed, data is backed up accordingly.

### 8. Exit Application:
   - Purpose: Closes the application.

## Usage

### 1. Clone the repository:

   `git clone https://github.com/reponseashimwe/shell-students-reg.git`

### 2. Execute the script:
   
   `./main.sh`
