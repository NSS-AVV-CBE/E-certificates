# NSS E-Certificate Distribution Portal

A web application for distributing e-certificates to NSS (National Service Scheme) volunteers at Amrita University. This portal allows participants to download their certificates by selecting the event and entering their roll number.

## Features

- **Event Selection**: Choose from available NSS events
- **Certificate Retrieval**: Enter roll number to fetch personalized certificates
- **Secure Download**: Direct download of PDF certificates from Firebase Storage
- **Responsive Design**: Works on desktop and mobile devices
- **Error Handling**: Clear messages for invalid inputs or missing certificates

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6 Modules)
- **Backend**: Firebase Storage for certificate hosting
- **Styling**: Custom CSS with CSS Variables for theming
- **Deployment**: Firebase Hosting

## Setup and Installation

### Prerequisites

- Node.js and npm installed
- Firebase CLI installed (`npm install -g firebase-tools`)
- Firebase project set up

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd Certificates
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Configure Firebase**:
   - Update `firebase.json` if needed
   - Ensure Firebase project is configured with Storage enabled

4. **Deploy to Firebase**:
   ```bash
   firebase deploy
   ```

## Usage

1. Open the deployed URL in a web browser
2. Select the NSS event from the dropdown
3. Enter your roll number in the provided field
4. Click "Get Certificate" to retrieve your certificate
5. Download the PDF certificate

## Project Structure

```
Certificates/
├── index.html          # Main application file
├── firebase.json       # Firebase configuration
├── package.json        # Project dependencies
└── README.md          # This file
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request
