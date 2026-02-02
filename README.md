# Pothole Detection Web Application

A comprehensive web-based pothole detection system with user and admin functionality.

## Features

### User Features
- 🔐 User registration and login
- 📸 Upload and analyze road images for pothole detection
- 📊 View detection results with severity levels
- 📍 Submit reports with location information
- 📋 View personal report history
- 🗺️ Interactive pothole map
- 📈 Personal statistics and rankings

### Admin Features
- 🔒 Secure admin login
- 📊 System overview dashboard
- 📝 Manage all pothole reports
- 👥 User management
- 🔍 Filter and search reports
- ✅ Approve/resolve reports
- 📈 Analytics and statistics
- ⚙️ System settings

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Node.js, Express.js
- **Storage**: File-based JSON storage (LocalStorage + Server-side)
- **Icons**: Font Awesome 6
- **Design**: Responsive, modern gradient UI

## Installation

1. **Clone or download the project**
   ```bash
   cd Pothole_Detection
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the server**
   ```bash
   npm start
   ```

4. **Open in browser**
   ```
   http://localhost:3000
   ```

## Default Login Credentials

### Admin Login
- Username: `admin`
- Password: `admin123`

### Demo User Login
- Email: `user@demo.com`
- Password: `user123`

## File Structure

```
Pothole_Detection/
│
├── index.html          # Login page
├── dashboard.html      # User dashboard
├── admin.html         # Admin panel
├── style.css          # Global styles
├── auth.js            # Authentication logic
├── dashboard.js       # User dashboard functionality
├── admin.js           # Admin panel functionality
├── server.js          # Backend server
├── package.json       # Node.js dependencies
├── data.json          # Data storage (auto-generated)
└── README.md          # This file
```

## Usage

### For Users:
1. Register a new account or login
2. Upload a road image with potential potholes
3. Click "Analyze Image" to detect potholes
4. Review detection results (count, severity, confidence)
5. Add location details and submit the report
6. Track your reports and statistics

### For Admins:
1. Login with admin credentials
2. View system overview and statistics
3. Manage all user reports
4. Filter reports by status and severity
5. Approve or resolve pothole reports
6. View user activity and analytics

## API Endpoints

- `POST /api/signup` - User registration
- `POST /api/login` - User login
- `POST /api/admin/login` - Admin login
- `POST /api/reports` - Submit pothole report
- `GET /api/reports` - Get all reports (Admin)
- `GET /api/reports/user/:userId` - Get user reports
- `PUT /api/reports/:reportId` - Update report status
- `GET /api/users` - Get all users (Admin)
- `GET /api/statistics` - Get system statistics
- `GET /api/health` - Health check

## Features to Add (Future Enhancements)

- 🤖 Real AI/ML-based pothole detection using TensorFlow.js
- 🗺️ Google Maps integration for location tracking
- 📧 Email notifications for users and admins
- 📱 Mobile app version (React Native)
- 🗄️ Database integration (MongoDB/PostgreSQL)
- 🔐 JWT-based authentication
- 📊 Advanced data visualization with Chart.js
- 🌐 Multi-language support
- 📤 Export reports to PDF/Excel
- 🔔 Real-time notifications with WebSockets

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## License

MIT License - Feel free to use and modify for your projects.

## Support

For issues or questions, please create an issue in the repository.

---

**Note**: This is a demonstration project. The pothole detection is simulated with random results. For production use, integrate a real AI/ML model for accurate detection.
