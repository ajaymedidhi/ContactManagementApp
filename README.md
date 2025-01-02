# Contact Management Application

Contact Managment Application is a web application designed to manage contacts like add , update ,edit and delete. The application consists of a backend built with Django and Sqlite, and a frontend built with React.

## Project URL
You can access the project at: [Contact Management App URL](https://contactmanagement7.vercel.app/)

## Features
  ### Contact Model
  The application includes a `Contact` model with the following fields:

- **Full Name**: Text field.  
- **Phone Number**: Phone number field.  
- **Email Address**: Email field.  
- **Address**: Text field.  
- **Company Name**: Text field.  
- **Position**: Text field.  
- **Notes**: Text area.  
- **Date Created**: Auto-filled timestamp.  
- **Date Updated**: Auto-filled timestamp.  

### Pages and Views

#### 1. **Contact List Page**
- Displays a table of all contacts with the following columns:
  - Full Name, Phone Number, Email Address, Company Name, Position, Actions (Edit/Delete).
- **Features**:
  - Pagination for large datasets.
  - Search functionality to filter by name, phone, email, etc.
  - Filters to refine search results.

#### 2. **Add Contact Page**
- A form for creating a new contact.  
- **Features**:
  - Fields: Full Name, Phone Number, Email Address, Address, Company Name, Position, Notes.
  - Validation for all input fields with error messages for invalid inputs.
  - Auto-complete suggestions for fields like Company Name.
  - Redirects to the Contact List page upon successful submission with a success message.

#### 3. **Edit Contact Page**
- Allows editing of existing contact details.  
- **Features**:
  - Pre-populated form with current contact details.
  - Confirmation dialog for updates.
  - Validation and error handling for inputs.

#### 4. **View Contact Details Page**
- Displays detailed information about a single contact.  
- **Features**:
  - All contact details are shown.
  - Options to edit or delete the contact directly from this page.

#### 5. **Delete Contact**
- Deletes a contact from the database.  
- **Features**:
  - Confirmation dialog to prevent accidental deletions.
  - Displays a success message after successful deletion.

## Installation and Setup

### Prerequisites

- **Backend**: Python (v3.8+), Django (v4+)
- **Frontend**: Node.js (v14+), React.js (v18+)
- Database: PostgreSQL or sqlite3 other supported databases
