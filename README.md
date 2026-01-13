# MstryMessage

A sleek, privacy-focused platform for collecting anonymous feedback via customizable message cards. Users can share feedback links easily with URL copy functionality and manage sessions seamlessly with logout features.

##  Features

- **Anonymous Feedback Collection**: Users submit feedback without accounts or tracking
- **One-Click URL Copy**: Share feedback links instantly
- **Secure Authentication**: NextAuth.js for session management
- **Smooth Logout**: Clean session management

## Tech Stack

| Category | Technologies |
|----------|--------------|
| **Framework** | Next.js 14 (App Router) |
| **Language** | TypeScript |
| **Authentication** | NextAuth.js |
| **Validation** | Zod |
| **Email Verification** | Resend |
| **AI Integration** | OpenAI API |
| **Styling** | Tailwind CSS |
| **Database** | MongoDB |

## Quick Start

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/anonymous-feedback.git
cd mstrymessage
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. **Configure Environment Variables**
```env
# NextAuth
NEXTAUTH_SECRET=your-secret-key

# Database
DATABASE_URL=your-database-connection-url

# OpenAI
OPENAI_API_KEY=your-openai-key

# Resend
RESEND_API_KEY=your-resend-key
```

4. **Run the development server**
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.


# Screenshots

<!-- Add your screenshots here -->
![Home Page](/public/screenshots/home.png)
![Dashboard](/public/screenshots/dashboard.png)
![Public Profile Link](/public/screenshots/public-profile-link.png)