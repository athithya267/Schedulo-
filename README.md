# Schedulo - Beauty Appointment Booking Platform

A full-stack web application for booking appointments at salons, spas, and beauty services. Built with Next.js, TypeScript, and Tailwind CSS.

## 🚀 Features

### Core Features
- **User Authentication**: Sign up and login with email, phone, or Google
- **Service Browsing**: Browse salons, spas, and beauty services by category
- **Appointment Booking**: Select date, time, and service with real-time availability
- **Booking Management**: View, edit, and cancel appointments
- **Responsive Design**: Works seamlessly on desktop and mobile devices

### Service Categories
- 💇‍♀️ Hair Services (Cut, color, styling)
- 💅 Nail Services (Manicure, pedicure)
- ✨ Skincare (Facials, treatments)
- 💆‍♀️ Massage (Relaxation therapy)
- 💄 Makeup (Beauty application)
- 👁️ Eyebrows (Shaping, styling)

### UI/UX Features
- Clean, modern interface with red and white theme
- Interactive service category filters
- Real-time search functionality
- Appointment status tracking
- Mobile-responsive design
- Intuitive booking flow

## 🛠️ Tech Stack

### Frontend
- **Next.js 15** - React framework with App Router
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Accessible component primitives
- **Lucide React** - Beautiful icons

### Styling
- **Tailwind CSS** - Utility-first styling
- **Custom CSS Variables** - Red and white theme
- **Responsive Design** - Mobile-first approach

### Development Tools
- **ESLint** - Code linting
- **TypeScript** - Static type checking
- **PostCSS** - CSS processing

## 📁 Project Structure

```
schedulo/
├── src/
│   ├── app/                    # Next.js App Router pages
│   │   ├── auth/              # Authentication pages
│   │   │   ├── login/         # Login page
│   │   │   └── signup/        # Signup page
│   │   ├── booking/           # Booking pages
│   │   │   └── [salonId]/     # Dynamic salon booking page
│   │   ├── dashboard/         # User dashboard
│   │   ├── globals.css        # Global styles
│   │   ├── layout.tsx         # Root layout
│   │   └── page.tsx           # Home page
│   ├── components/            # Reusable components
│   │   ├── ui/               # Base UI components
│   │   │   ├── button.tsx
│   │   │   ├── card.tsx
│   │   │   ├── input.tsx
│   │   │   └── badge.tsx
│   │   ├── SalonCard.tsx     # Salon display component
│   │   └── ServiceCategory.tsx # Service category component
│   ├── data/                 # Dummy data
│   │   └── salons.ts         # Salon and service data
│   ├── lib/                  # Utility functions
│   │   └── utils.ts          # Common utilities
│   └── types/                # TypeScript type definitions
│       └── index.ts          # Main type definitions
├── public/                   # Static assets
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd schedulo
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🎨 Design System

### Color Palette
- **Primary Red**: #dc2626 (Red-600)
- **Primary Dark**: #b91c1c (Red-700)
- **Primary Light**: #fef2f2 (Red-50)
- **Background**: #ffffff (White)
- **Text**: #171717 (Gray-900)
- **Muted**: #6b7280 (Gray-500)

### Typography
- **Headings**: Bold, clean sans-serif
- **Body**: Regular weight, readable
- **UI Elements**: Medium weight for buttons and labels

### Components
- **Cards**: Rounded corners, subtle shadows
- **Buttons**: Red primary, outlined secondary
- **Inputs**: Clean borders, red focus states
- **Badges**: Rounded, color-coded status indicators

## 📱 Pages Overview

### Home Page (`/`)
- Hero section with search functionality
- Service category browsing
- Featured salons grid
- Call-to-action sections

### Authentication (`/auth/`)
- **Login** (`/auth/login`): Email/password login with Google OAuth
- **Signup** (`/auth/signup`): User registration with validation

### Booking (`/booking/[salonId]`)
- Salon information display
- Service selection
- Date and time picker
- Customer information form
- Booking confirmation

### Dashboard (`/dashboard`)
- Appointment overview with stats
- Upcoming appointments management
- Past appointments history
- Search and filter functionality

## 🔧 Customization

### Adding New Service Categories
1. Update the `ServiceCategory` type in `src/types/index.ts`
2. Add the category to the `serviceCategories` array in `src/app/page.tsx`
3. Update the dummy data in `src/data/salons.ts`

### Styling Modifications
- Global styles: `src/app/globals.css`
- Component styles: Individual component files
- Theme colors: Update CSS variables in `globals.css`

### Adding New Features
- Create new pages in `src/app/`
- Add components in `src/components/`
- Update types in `src/types/index.ts`

## 🚧 Future Enhancements

### Planned Features
- **Online Payments**: Stripe integration for payment processing
- **Location Services**: GPS-based salon recommendations
- **Multi-language**: English and Tamil support
- **Mobile App**: React Native version
- **Admin Dashboard**: Business management interface
- **Real-time Notifications**: Email and SMS reminders
- **Reviews & Ratings**: User feedback system

### Technical Improvements
- **Database Integration**: MongoDB or PostgreSQL
- **Authentication**: NextAuth.js or Firebase Auth
- **API Routes**: Backend functionality
- **Testing**: Unit and integration tests
- **Deployment**: Vercel or similar platform

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For support, email support@schedulo.com or join our Slack channel.

---

**Schedulo** - Making beauty appointments effortless ❤️