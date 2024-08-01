# -Student-Management-System
Student Management System
Description:
Developed a comprehensive Django-based Student Management System to manage student data and courses. Features include student enrollment with ListView and DetailView, project management with model forms, CSV and PDF generation using csv and reportlab, AJAX integration for dynamic updates, and robust error handling and validation.

Features:

  Student Enrollment: Utilized Django's ListView and DetailView to create a seamless interface for displaying a list of students and their detailed information.

  Project Management: Designed model forms for adding and managing student projects, including details such as project topic, languages used, and duration.

  CSV and PDF Generation: Implemented views to export student data into CSV and PDF formats using the csv library and reportlab.

  AJAX Integration: Enhanced user experience by implementing AJAX for searching students and dynamically displaying their enrolled courses without page refresh.

  Error Handling and Validation: Ensured robust error handling and data validation throughout the application to maintain data integrity and provide meaningful feedback to users.

Technologies Used:
  Django
  HTML
  CSS
  JavaScript
  AJAX
  SQLite
  reportlab

Installation
1. Clone the repository:
   git clone https://github.com/yourusername/student-management-system.git
cd student-management-system

2. Create a virtual environment:
   python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install the dependencies:
   pip install -r requirements.txt

4. Apply the migrations:
   python manage.py migrate

5. Run the development server:
   python manage.py runserver


Usage:
1. Navigate to the home page to view the list of students.
2. Click on a student's name to view their details.
3. Use the export links to download student data in CSV or PDF format.
4. Use the search functionality to find students and view their enrolled courses dynamically.


Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Django Documentation: https://docs.djangoproject.com/
reportlab Documentation: https://www.reportlab.com/docs/reportlab-userguide.pdf
