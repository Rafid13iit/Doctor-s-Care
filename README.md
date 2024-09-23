<img src="https://github.com/Rafid13iit/Doctors_Care/blob/master/public/assets/images/Cover.png?raw=true" width="750" height="400" align="center">

# Doctor's Care Web Application

Doctor's Care is a comprehensive healthcare management web application built using Next.js and Appwrite. It allows users to register patients, manage appointments, and view patient details in an intuitive and efficient manner.

## Features

- Patient Registration
- Appointment Scheduling
- Patient Details Management
- Secure Document Storage
- User Authentication

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- Appwrite Project Setup (API keys, Database, Storage)
- Tailwind CSS for styling

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Rafid13iit/Doctors_Care.git
   cd Doctors_Care
2. Install dependencies:
    ```bash
    npm install
3. Create a .env.local file in the root directory and add your environment variables:
    ```bash
    NEXT_PUBLIC_PROJECT_ID=your_project_id
    NEXT_PUBLIC_API_KEY=your_api_key
    DATABASE_ID=your_appwrite_database_id
    PATIENT_COLLECTION_ID=your_appwrite_patient_collection_id
    DOCTOR_COLLECTION_ID=your_appwrite_doctor_collection_id
    APPOINTMENT_COLLECTION_ID=your_appwrite_appointment_collection_id
    NEXT_PUBLIC_BUCKET_ID=your_bucket_id
    NEXT_PUBLIC_ENDPOINT=your_edpoint
    NEXT_PUBLIC_ADMIN_PASSKEY=your_admin_passkey
4. Run the development server:
    ```bash
    npm run dev
Open your browser and go to http://localhost:3000.

## Usage
- Patient Registration: Register new patients by providing their details and uploading identification documents.
- Appointment Scheduling: Admin Easily schedule appointments for registered patients from admin dashboard.
- View Patient Details: Access and manage the registered patients' details in a secure and efficient manner.

## Acknowledgements
Special thanks to **Adrian Hajdin** for his helpful tutorials and guidance on YouTube.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or improvements.