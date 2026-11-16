# Hall Ticket Generation System

## Project Overview

The **Hall Ticket Generation System** is a Python-based application designed to simplify the process of creating examination hall tickets. It generates PDF hall tickets containing student information, examination details, subject schedules, and QR codes.

The system helps reduce manual work involved in preparing hall tickets and provides a structured format for presenting examination information.

## Features

- **PDF Hall Ticket Generation:** Automatically generates hall tickets in PDF format.
- **Student Information:** Displays student details and roll number.
- **Examination Details:** Includes examination dates and subject-wise schedules.
- **QR Code Generation:** Generates a QR code containing student and examination information.
- **Photo and Logo Support:** Provides spaces for student photographs and the college logo.
- **Organized Layout:** Presents examination information in a structured hall ticket format.

## Technologies Used

- **Programming Language:** Python
- **PDF Generation:** ReportLab
- **QR Code Generation:** qrcode
- **Image Processing:** Pillow

## Project Structure

```text
HallTicketGeneration/
│
├── HallTicketGeneration-main/
│   ├── README.md
│   └── hallticket10.py
│
└── README.md
```

*The structure above reflects the repository's current uploaded folder arrangement. You can simplify it by moving the project files to the repository root.*

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/madagirisaketh/HallTicketGeneration.git
```

### 2. Navigate to the Project Directory

```bash
cd HallTicketGeneration
cd HallTicketGeneration-main
```

### 3. Install Required Libraries

```bash
pip install reportlab qrcode pillow
```

### 4. Run the Application

```bash
python hallticket10.py
```

## How It Works

1. Provide the required student information.
2. Add examination details and subject schedules.
3. Generate a QR code containing the relevant information.
4. Prepare the hall ticket layout with student and college image spaces.
5. Generate the final hall ticket as a PDF document.

## Applications

- Educational institutions
- Colleges and universities
- Examination departments
- Student examination management

## Future Enhancements

- Database integration for storing student records.
- Bulk hall ticket generation for multiple students.
- User-friendly graphical interface.
- Automated student data import from Excel files.
- QR code scanning for hall ticket verification.

## Author

**Saketh**

GitHub: [https://github.com/madagirisaketh](https://github.com/madagirisaketh)

## License

This project is available for learning and educational purposes. Add an appropriate open-source license if you intend to permit reuse and redistribution.
