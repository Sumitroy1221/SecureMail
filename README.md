## 🖼️ Screenshots

### Login Page
<img width="956" height="413" alt="login-page" src="https://github.com/user-attachments/assets/e5db4517-94d3-4603-be53-0be1695a2763" />

### SecureMail Inbox View
<img width="1909" height="824" alt="inbox-view" src="https://github.com/user-attachments/assets/cb280d07-6e00-41f0-99a5-e4b31cab63e1" />

### Compose Window
<img width="788" height="403" alt="compose-window" src="https://github.com/user-attachments/assets/0304dc0c-b41f-4546-b029-b874c6f2d9ed" />

### User Management
<img width="953" height="367" alt="user-management" src="https://github.com/user-attachments/assets/18ab1206-ab50-4b07-8767-c7516ee1ab73" />

### Reports
<img width="954" height="363" alt="reports" src="https://github.com/user-attachments/assets/3e3f6897-4826-412a-9fa5-f7ebe8af8962" />

### Live Queue
<img width="955" height="368" alt="live-queue" src="https://github.com/user-attachments/assets/49dfd084-154c-4793-afda-e91c423801c4" />


# ✨ SecureMail Enterprise
A powerful, secure internal-only email system built for enterprises, featuring real-time messaging, admin controls, and internal file attachments. Designed for complete internal communication within your organization, this system works both offline and online.

🔐 Complete Internal-Only Email Communication Solution

SecureMail Internal is a comprehensive platform designed to revolutionize enterprise communication. All emails stay strictly within your organization—no external email integration is possible.

Key Points:

🚫 No External Sending: You cannot send emails to Gmail, Yahoo, Outlook, or any external domains. Communication is strictly internal.
Example: Only User A and User B created in this system can email each other.

📧 Internal Sending Only: Emails can only be sent between users registered in the system by the administrator.

🚫 No External Receiving: Emails from external services (Gmail, Yahoo, Outlook) will not reach this system.

🛡️ Enhanced Security: Isolated architecture eliminates external hacking risks, phishing attacks, or unauthorized access to sensitive information.

⚡ Offline/Online Capability: Works seamlessly even when network connectivity is down; all internal emails remain accessible.

💰 Cost Savings: Designed to save ~₹16 lakhs yearly for an employee base of ~880 users, ensuring internal security.

📈 Scalable Architecture: Efficiently supports 10 users to unlimited scale.

🏢 Enterprise Ready: Built to meet enterprise-level internal communication requirements.

## ✨ Features


### 🔐 **Security & Authentication**
- Role-based access control (Admin, Manager, Agent)
- Secure login system with JWT authentication
- Session management and user authorization

### 📧 **Email Management**
- Real-time email messaging with Socket.IO
- Rich text editor for composing emails
- File attachment support (documents, images, etc.)
- Email threading and conversation view
- Read/unread status tracking

### 👥 **User Management**
- Admin dashboard with user controls
- User role assignment and permissions
- User profile management
- Account activation/deactivation

### 📊 **Admin Features**
- Live queue monitoring
- System statistics and analytics
- User activity tracking
- Bulk operations (mark read/unread/archive)

### 🗂️ **Organization**
- Email archiving functionality
- Trash system with permanent deletion
- Search and filtering capabilities
- Email categorization

## 🛠️ **Tech Stack**

### Frontend
- **React 18** with TypeScript
- **Vite** for fast development
- **Tailwind CSS** for styling
- **Socket.IO Client** for real-time updates
- **React Router** for navigation

### Backend
- **Node.js** with Express
- **MongoDB** for data storage
- **Socket.IO** for real-time communication
- **JWT** for authentication
- **Multer** for file uploads
- **Nodemailer** for email functionality

## 🚀 **Quick Start**

### Prerequisites
- Node.js (v16 or higher)
- MongoDB (local or cloud)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Sumitroy1221/internal-email-app.git
cd internal-email-app
```

2. **Install dependencies**
```bash
npm install
```

3. **Environment Setup**
Copy `.env.example` to `.env` and configure:
```bash
cp .env.example .env
```

Edit `.env` with your settings:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5050
```

4. **Start the application**
```bash
# Development mode
npm run dev

# Or use the one-click launcher
./StartSecureMail.bat
```

5. **Access the application**
- Frontend: http://localhost:3000
- Backend API: http://localhost:5050

## 👤 **Default Accounts**

| Role | Email | Password |
|------|-------|----------|
| Admin | admin@company.com | admin123 |
| Manager | manager@company.com | manager123 |
| Agent | agent@company.com | agent123 |

## 📁 **Project Structure**

```
internal-email-app/
├── public/                 # Static assets
├── server/                 # Backend code
│   ├── index.js           # Main server file
│   └── uploads/           # File uploads directory
├── src/                    # Frontend source code
│   ├── components/        # React components
│   ├── contexts/          # React contexts
│   ├── hooks/             # Custom React hooks
│   ├── types/             # TypeScript type definitions
│   └── utils/             # Utility functions
├── package.json           # Project dependencies
├── vite.config.ts         # Vite configuration
└── tailwind.config.js     # Tailwind CSS configuration
```

## 🌐 **Network Access**

### Local Development
- **Local:** http://localhost:3000
- **Network:** http://YOUR-IP:3000

### Custom Domain Setup
To use `securemail.com` instead of IP:
1. Edit your hosts file: `C:\Windows\System32\drivers\etc\hosts`
2. Add: `YOUR_IP securemail.com`
3. Access via: http://securemail.com:3000

## 🔧 **Available Scripts**

```bash
npm run dev          # Start both client and server
npm run client       # Start frontend only
npm run server       # Start backend only
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
```

## 🚀 **One-Click Deployment**

Use the included `StartSecureMail.bat` for easy deployment:
- ✅ Automatic dependency installation
- ✅ Network IP detection
- ✅ Server and client startup
- ✅ Browser auto-launch
- ✅ Custom domain instructions

## 📱 **Features in Detail**

### Real-Time Messaging
- Instant email delivery using WebSockets
- Live notifications for new emails
- Real-time status updates

### File Attachments
- Support for multiple file types
- Secure file upload and storage
- Download functionality
- Attachment preview

### User Roles
- **Admin:** Full system control, user management
- **Manager:** Team oversight, queue monitoring
- **Agent:** Email sending and receiving

### Security Features
- JWT-based authentication
- Role-based access control
- Secure file handling
- Session management

## 🤝 **Contributing**

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 **Support**

For issues and questions:
- Create an issue on GitHub
- Check existing issues for solutions
- Review the documentation

---

**⭐ Star this repository if you find it helpful!**
