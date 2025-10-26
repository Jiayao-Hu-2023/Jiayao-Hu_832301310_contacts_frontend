# Contact Management System - Frontend

## Project Overview
This is the frontend application for the Contact Management System, designed to provide a user-friendly interface for managing contact information. The application allows users to view, add, edit, delete, search, and sort contacts with ease.

## Features
- **Contact List View**: Display all contacts with essential information including name, category, phone number, email, and address
- **Add New Contacts**: Intuitive form for creating new contacts with validation
- **Edit Contacts**: Modify existing contact information through a modal interface
- **Delete Contacts**: Remove contacts with confirmation prompt
- **Search Functionality**: Filter contacts by name, phone number, email, or address
- **Sorting**: Organize contacts by name (ascending/descending) or category
- **Responsive Design**: Optimized for both desktop and mobile viewing
- **Visual Feedback**: Toast notifications for successful operations and error handling

## Technologies Used
- HTML5 (Semantic Markup)
- CSS3 (With Bootstrap 5)
- JavaScript (ES6+ Features)
- Bootstrap 5 (Responsive Design Framework)
- Font Awesome (Icon Library)
- Fetch API (For Backend Communication)

## Getting Started
### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Backend server running at `http://localhost:5000`

### Installation
1. Clone or download the repository
2. Navigate to the frontend directory:
   ```bash
   cd Jiayao Hu_832301310_contacts_frontend
   ```
3. Open the application:
   ```bash
   # Windows
   start src\contacts.html
   ```
   Or
   ```bash
   # macOS/Linux
   open src/contacts.html
   ```
   Alternatively, you can simply double-click the `src/contacts.html` file in your file explorer.

## API Configuration
The frontend is configured to communicate with a backend server running at `http://localhost:5000`.
This setting can be modified in the JavaScript code within `contacts.html` by changing the `API_BASE_URL` variable.

## File Structure
```
Jiayao Hu_832301310_contacts_frontend/
├── README.md           # Project documentation
├── codestyle.md        # Code style guidelines
└── src/                # Source code directory
    └── contacts.html   # Main application file (HTML, CSS, JavaScript)
```

## Browser Compatibility
- Chrome (90+)
- Firefox (88+)
- Safari (14+)
- Edge (90+)

## Known Issues
- The application requires the backend server to be running for full functionality
- Offline functionality is not currently supported

## License
This project can be used for grading purposes only. Do not use it for production purposes.
Strictly follow the code style guidelines in `codestyle.md`
