# 🎵 Music Academy

A modern, responsive web application for a fictional **Music Academy** built with **Next.js 15**, **TypeScript**, and **Tailwind CSS**. This project showcases advanced UI components, smooth animations, and a clean design system perfect for educational institutions.

![Music Academy Banner](https://img.shields.io/badge/Next.js-15.3.1-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.0-06B6D4?logo=tailwindcss)
![React](https://img.shields.io/badge/React-19.0-61DAFB?logo=react)

---

## 🚀 Features

### 🎯 Core Features

- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, intuitive interface with smooth animations
- **Course Management** - Display of featured and all available courses
- **Interactive Components** - 3D cards, animated tooltips, and hover effects
- **Contact System** - Functional contact form with validation
- **Instructor Showcase** - Meet the team section with animated profiles
- **Testimonials** - Infinite scrolling customer reviews
- **Webinar Listings** - Upcoming events and workshops

### 🎨 Visual Features

- **3D Card Effects** - Interactive course cards with depth
- **Background Animations** - Dynamic beams, gradients, and wavy backgrounds
- **Spotlight Effects** - Eye-catching hero section animations
- **Infinite Scrolling** - Smooth testimonial carousel
- **Sticky Scroll Reveal** - Progressive content unveiling
- **Hover Interactions** - Enhanced user engagement

### 📱 Technical Features

- **Server-Side Rendering** - Next.js 15 with App Router
- **TypeScript Support** - Full type safety and IntelliSense
- **Component Architecture** - Reusable and modular design
- **Performance Optimized** - Image optimization and lazy loading
- **SEO Ready** - Meta tags and structured data
- **Dark Mode** - Built-in dark theme support

---

## 🛠️ Tech Stack

### Frontend

- **[Next.js 15.3.1](https://nextjs.org/)** - React framework with App Router
- **[React 19.0](https://react.dev/)** - UI library with latest features
- **[TypeScript 5.0](https://www.typescriptlang.org/)** - Type-safe JavaScript
- **[Tailwind CSS 4.0](https://tailwindcss.com/)** - Utility-first CSS framework

### UI & Animations

- **[Framer Motion 12.7.4](https://www.framer.com/motion/)** - Animation library
- **[clsx](https://github.com/lukeed/clsx)** - Conditional className utility
- **[Tailwind Merge](https://github.com/dcastil/tailwind-merge)** - Merge Tailwind classes
- **Custom UI Components** - Hand-crafted interactive elements

### Development Tools

- **[ESLint](https://eslint.org/)** - Code linting and formatting
- **[PostCSS](https://postcss.org/)** - CSS processing
- **[Turbopack](https://turbo.build/pack)** - Fast development builds

---

## 📁 Project Structure

```
music-academy/
├── public/                     # Static assets
│   ├── courses/               # Course images
│   │   ├── guitar.jpg
│   │   ├── piano.jpg
│   │   └── ...
│   └── *.svg                  # Icons and logos
├── src/
│   ├── app/                   # Next.js App Router
│   │   ├── contact/           # Contact page
│   │   ├── courses/           # Courses page
│   │   ├── globals.css        # Global styles
│   │   ├── layout.tsx         # Root layout
│   │   └── page.tsx           # Home page
│   ├── components/            # React components
│   │   ├── ui/                # Reusable UI components
│   │   │   ├── 3d-card.tsx
│   │   │   ├── animated-tooltip.tsx
│   │   │   ├── background-beams.tsx
│   │   │   ├── infinite-moving-cards.tsx
│   │   │   └── ...
│   │   ├── FeaturedCourses.tsx
│   │   ├── HeroSection.tsx
│   │   ├── Navbar.tsx
│   │   └── ...
│   ├── data/                  # Static data
│   │   └── music_courses.json # Course information
│   └── utils/                 # Utility functions
│       └── cn.ts              # className utility
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** 18.0 or higher
- **npm**, **yarn**, or **pnpm** package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/AnkitMishra2006/Music-Academy.git
   cd music-academy
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

### Available Scripts

```bash
npm run dev        # Start development server with Turbopack
npm run build      # Build for production
npm run start      # Start production server
npm run lint       # Run ESLint
```

---

## 📄 Pages & Components

### 🏠 Home Page (`/`)

- **Hero Section** - Engaging introduction with CTA
- **Featured Courses** - Highlighted course offerings
- **Why Choose Us** - Sticky scroll reveal content
- **Testimonials** - Customer feedback carousel
- **Upcoming Webinars** - Event listings with hover effects
- **Instructors** - Team showcase with tooltips
- **Footer** - Contact info and links

### 📚 Courses Page (`/courses`)

- **Course Grid** - All available courses with 3D cards
- **Interactive Cards** - Hover effects and animations
- **Course Details** - Title, description, and pricing
- **Responsive Layout** - Optimized for all screen sizes

### 📞 Contact Page (`/contact`)

- **Contact Form** - Email and message inputs with validation
- **Background Effects** - Animated beam background
- **Responsive Design** - Mobile-optimized layout

---

## 🎨 UI Components

### Interactive Elements

- **3D Cards** - Course display with depth effects
- **Animated Tooltips** - Instructor information on hover
- **Moving Borders** - Gradient button animations
- **Card Hover Effects** - Webinar cards with transitions

### Background Effects

- **Background Beams** - Dynamic light effects
- **Wavy Background** - Fluid wave animations
- **Spotlight** - Hero section highlighting
- **Background Gradients** - Smooth color transitions

### Navigation & Layout

- **Navbar Menu** - Responsive navigation with dropdowns
- **Sticky Scroll** - Progressive content revelation
- **Infinite Moving Cards** - Continuous testimonial scroll

---

## 🎯 Key Features Breakdown

### Course Management

- **Dynamic Course Loading** - JSON-based course data
- **Featured/All Course Views** - Filtered display options
- **Rich Course Information** - Images, descriptions, pricing
- **Responsive Course Grid** - Adaptive layout system

### Interactive Experience

- **Smooth Animations** - Framer Motion powered transitions
- **Hover States** - Enhanced user feedback
- **Progressive Loading** - Optimized content delivery
- **Mobile Touch Support** - Touch-friendly interactions

### Performance Optimization

- **Image Optimization** - Next.js automatic optimization
- **Code Splitting** - Component-level code splitting
- **SEO Optimization** - Meta tags and structured data
- **Fast Refresh** - Hot reload in development

---

## 🌐 Browser Compatibility

- ✅ **Chrome** (latest)
- ✅ **Firefox** (latest)
- ✅ **Safari** (latest)
- ✅ **Edge** (latest)
- ✅ **Mobile Browsers** (iOS Safari, Chrome Mobile)

---

## 📱 Responsive Design

The application is fully responsive and optimized for:

- **Desktop** - Full-featured experience (1200px+)
- **Tablet** - Adapted layout (768px - 1199px)
- **Mobile** - Touch-optimized interface (320px - 767px)

---

## � Customization

### Adding New Courses

1. Edit `src/data/music_courses.json`
2. Add course images to `public/courses/`
3. Update the course object with required fields

### Styling Modifications

- **Colors** - Modify Tailwind config or CSS variables
- **Animations** - Adjust Framer Motion parameters
- **Layout** - Update component structures

### Component Extensions

- **New UI Components** - Add to `src/components/ui/`
- **Page Components** - Create in `src/components/`
- **New Pages** - Add to `src/app/` directory

---

## � Deployment

### Vercel (Recommended)

1. Connect your GitHub repository to Vercel
2. Configure build settings (auto-detected)
3. Deploy with automatic CI/CD

### Other Platforms

- **Netlify** - Build command: `npm run build`
- **Railway** - Automatic Next.js detection
- **Digital Ocean** - App Platform deployment

---

## 🤝 Contributing

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

---

## � License

This project is open source and available under the [MIT License](LICENSE).

---


## 🙏 Acknowledgments

- **Next.js Team** - For the amazing React framework
- **Tailwind CSS** - For the utility-first CSS framework
- **Framer Motion** - For smooth animations and transitions
- **Vercel** - For seamless deployment and hosting
- **Unsplash** - For beautiful stock photography

---

## 📊 Project Stats

- **Lines of Code** - ~2,000+
- **Components** - 15+ reusable components
- **Pages** - 3 main pages
- **Build Size** - Optimized for web performance
- **Lighthouse Score** - 95+ across all metrics

---

_Built with ❤️ using Next.js, TypeScript, and Tailwind CSS_

