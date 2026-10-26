# CareNet – Healthcare Appointment & Doctor Management System

CareNet is a full-stack healthcare scheduling application that connects patients with doctors. It enables patients to view available time slots, book appointments, and reflects real-time schedule updates across the platform.

## Features
- **User & Doctor Authentication**: Secure registration and login workflows.
- **Doctor Directory & Profiles**: Browse, view, create, update, and manage doctor records.
- **Appointment Scheduling**: Dynamic patient count tracking and real-time appointment booking updates.
- **Mobile Integration**: Designed to serve a Flutter cross-platform mobile frontend via RESTful APIs.

## Tech Stack
- **Backend**: Node.js, Express.js
- **Frontend**: Flutter
- **Database**: MongoDB 

## API Endpoints

### Authentication (`/api/auth`)
- `POST /api/auth/register` - Register a new user/doctor
- `POST /api/auth/login` - Authenticate user/doctor

### Doctor Management (`/api/doctors`)
- `GET /api/doctors` - Retrieve all doctors
- `GET /api/doctors/:id` - Retrieve a specific doctor by ID
- `POST /api/doctors` - Add a new doctor
- `PUT /api/doctors/:id` - Update doctor profile details
- `DELETE /api/doctors/:id` - Remove a doctor profile
- `PUT /api/doctors/:id/patient` - Increment dynamic patient count / book slot

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/shahdood1212/care-Net.git](https://github.com/shahdood1212/care-Net.git)
   cd care-Net
