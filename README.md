# NIGERIAN PAPPORT TRAVELS - Ghana Road Trip Portal

A modern, responsive web application for managing road trip bookings and payments from Lagos to Ghana.

## 🚐 Project Overview

NIGERIAN PAPPORT TRAVELS is a comprehensive booking and payment management system for organizing road trips from Lagos, Nigeria to Ghana. The platform features:

- **User Registration & Authentication**: Simple signup and login
- **Payment Management**: Full payment or flexible installment plans
- **Dashboard**: Track payment progress and trip status
- **Payment Tracking**: Monitor all payments and outstanding balances
- **User Profiles**: Manage personal and trip information
- **Document Management**: Access trip documents and itineraries
- **Support System**: Get help from the support team

## 📋 Features

### 1. **Landing Page** (`index.html`)
- Attractive hero section
- Trip overview and pricing information
- Call-to-action buttons for registration
- Responsive navigation

### 2. **User Registration** (`auth/register.html`)
- Comprehensive registration form
- Personal information collection
- Address information
- Account security setup
- Payment option selection
- Form validation

### 3. **User Login** (`auth/login.html`)
- Simple login interface
- Email/username and password authentication
- Demo credentials for testing
- Forgot password link

### 4. **User Dashboard** (`dashboard/index.html`)
- **Overview Section**: Trip summary and payment progress
- **Payments Section**: Make payments and view history
- **Profile Section**: View and manage personal information
- **Documents Section**: Access trip documents
- **Support Section**: Contact support and FAQs

## 💰 Pricing & Payment Plans

### Trip Cost
- **Total**: ₦380,000 per person

### Payment Options
1. **Full Payment**: Pay entire ₦380,000 upfront
2. **Installment Plan**: Flexible payment schedule
   - Initial Deposit: ₦100,000 (minimum)
   - Remaining Balance: ₦280,000 (flexible installments)

## 🔐 Demo Credentials

For testing the application:
- **Email**: demo@example.com
- **Password**: Demo123456

## 📁 Project Structure

```
akwaba-portal/
├── index.html                 # Landing page
├── auth/
│   ├── login.html            # Login page
│   ├── register.html         # Registration page
│   └── forgot-password.html  # Password recovery (placeholder)
├── dashboard/
│   └── index.html            # User dashboard
├── styles/
│   ├── main.css              # Landing page styles
│   ├── auth.css              # Authentication styles
│   └── dashboard.css         # Dashboard styles
├── js/
│   ├── main.js               # Landing page scripts
│   ├── auth.js               # Authentication logic
│   └── dashboard.js          # Dashboard functionality
├── README.md                 # This file
└── .gitignore               # Git ignore file
```

## 🛠 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Storage**: Browser LocalStorage (Demo)
- **Responsive Design**: CSS Grid & Flexbox
- **No Dependencies**: Pure vanilla implementation

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Ogey2300/Akwaba-portal.git
cd Akwaba-portal
```

2. Open `index.html` in your web browser:
```bash
# On Windows
start index.html

# On Mac
open index.html

# On Linux
xdg-open index.html
```

Or simply double-click `index.html` to open it in your default browser.

## 💻 Usage

### For New Users
1. Click "Register" on the landing page
2. Fill out the registration form with your details
3. Select your payment option (Full Payment or Installment)
4. Submit the form
5. You'll be automatically logged in and redirected to the dashboard

### For Returning Users
1. Click "Login" on the landing page
2. Enter your email/username and password
3. Click "Sign In"
4. Access your dashboard

### On the Dashboard
- **Overview**: See your trip status and payment progress
- **Make Payment**: Click "Make Payment" to process a payment
- **View Profile**: See your registered information
- **Access Documents**: View trip-related documents
- **Get Support**: Contact support or view FAQs

## 🔒 Security Features

- Password validation (minimum 8 characters)
- Unique email and username constraints
- Form input validation
- Session management via localStorage
- Secure password confirmation

## 📊 Payment Tracking

The dashboard provides real-time payment tracking:
- Total amount due (₦380,000)
- Amount already paid
- Outstanding balance
- Payment progress percentage with visual progress bar
- Installment breakdown and status
- Payment history log

## 🎨 Design Features

- Modern, clean interface
- Responsive design (mobile, tablet, desktop)
- Gradient color scheme (Blue to Purple)
- Intuitive navigation
- Accessible forms and buttons
- Professional typography

## 📱 Responsive Breakpoints

- **Desktop**: 1400px and above
- **Tablet**: 768px - 1399px
- **Mobile**: Below 768px

## 🔄 Data Storage

The application uses browser's `localStorage` to store:
- User accounts
- Current session information
- Payment progress
- Payment history

**Note**: This is for demonstration. In production, use a backend database.

## 🚀 Future Enhancements

- [ ] Backend API integration
- [ ] Real payment gateway (Paystack, Flutterwave, etc.)
- [ ] Email notifications
- [ ] SMS reminders
- [ ] Admin dashboard
- [ ] Payment receipts
- [ ] Trip itinerary details
- [ ] User profile photo upload
- [ ] Advanced reporting

## 🐛 Known Issues

- Data persists only in browser localStorage
- No real payment processing (demo only)
- No email verification
- No password reset functionality (yet)

## 📞 Support

For support and inquiries:
- **Email**: support@nigerian-papport-travels.com
- **Phone**: +234 (0) XXX XXX XXXX
- **Live Chat**: Available on dashboard

## 📄 License

MIT License - See LICENSE file for details

## 👨‍💻 Developer

**NIGERIAN PAPPORT TRAVELS**
- Website: Coming soon
- Repository: https://github.com/Ogey2300/Akwaba-portal

## 🙏 Acknowledgments

Built with modern web technologies and best practices for optimal user experience.

---

**Version**: 1.0.0  
**Last Updated**: June 2026  
**Status**: Active Development
