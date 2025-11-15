# Niranjan Vijayan - Disability Justice Advocate Website

A modern, accessible website for Niranjan Vijayan, featuring his work as a Disability Justice Advocate, Mindfulness Practitioner, and Inclusive Publisher.

## Features

- **WCAG 2.1 AA Compliant**: Built with accessibility as a priority
- **Responsive Design**: Works seamlessly on all devices
- **Modern Stack**: Next.js 14+ with TypeScript and Tailwind CSS
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Keyboard Navigation**: Fully accessible via keyboard
- **Screen Reader Friendly**: ARIA labels and semantic structure

## Technology Stack

- **Framework**: Next.js 14+ (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Deployment**: Ready for Vercel/Netlify

## Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn/pnpm

### Installation

1. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

2. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
├── app/                    # Next.js app directory
│   ├── about/             # About page
│   ├── advocacy/          # Advocacy page
│   ├── contact/           # Contact page
│   ├── mindfulness/      # Mindfulness page
│   ├── partnership/       # Partnership page
│   ├── public-service/    # Public Service page
│   ├── publishing/        # Publishing page
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── components/            # React components
│   ├── ContactForm.tsx   # Contact form component
│   ├── Footer.tsx        # Footer component
│   ├── Header.tsx        # Navigation header
│   ├── Section.tsx       # Reusable section wrapper
│   └── SkipLink.tsx      # Skip to content link
├── public/               # Static assets
│   └── profile.jpg       # Profile picture
└── package.json          # Dependencies
```

## Accessibility Features

- Skip to main content link
- Semantic HTML5 elements
- ARIA labels and landmarks
- Keyboard navigation support
- High contrast color ratios (WCAG AA compliant)
- Focus indicators on all interactive elements
- Alt text for all images
- Screen reader friendly structure

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Import your repository in Vercel
3. Deploy automatically

### Netlify

1. Push your code to GitHub
2. Import your repository in Netlify
3. Build command: `npm run build`
4. Publish directory: `.next`

## Contact Information

- **Email**: vniranjanin@gmail.com
- **Phone**: +91 9788606463
- **Location**: Kolliyangunam, Tamil Nadu, India

## License

All rights reserved. © 2024 Niranjan Vijayan

