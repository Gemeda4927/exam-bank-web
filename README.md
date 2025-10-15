# ExamB - Modern Exam Management Platform

A beautiful, industry-standard exam management platform built with Next.js 15, React 19, and TypeScript.

## Features

- 🎨 Beautiful, modern UI with Tailwind CSS
- 🔐 Secure authentication and authorization
- 📊 Real-time analytics and dashboards
- 🎓 Comprehensive exam management
- 💳 Payment processing
- 📱 Fully responsive design
- ⚡ Lightning-fast performance
- 🛡️ Industry-standard security practices

## Tech Stack

- **Framework:** Next.js 15 (App Router)
- **UI Library:** React 19
- **Styling:** Tailwind CSS v4
- **UI Components:** Radix UI + shadcn/ui
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **HTTP Client:** Axios
- **Type Safety:** TypeScript

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm, yarn, or pnpm

### Installation

1. Clone the repository:
\`\`\`bash
git clone <repository-url>
cd examb-frontend
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
# or
yarn install
# or
pnpm install
\`\`\`

3. Create environment file:
\`\`\`bash
cp .env.example .env.local
\`\`\`

4. Update `.env.local` with your API URL:
\`\`\`env
NEXT_PUBLIC_API_URL=http://localhost:5000/api
\`\`\`

5. Run the development server:
\`\`\`bash
npm run dev
# or
yarn dev
# or
pnpm dev
\`\`\`

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

\`\`\`
examb-frontend/
├── app/                      # Next.js app directory
│   ├── dashboard/           # Dashboard pages
│   │   ├── admin/          # Admin dashboard
│   │   └── student/        # Student dashboard
│   ├── login/              # Login page
│   ├── signup/             # Signup page
│   └── page.tsx            # Landing page
├── components/              # React components
│   ├── ui/                 # shadcn/ui components
│   ├── AdminLayout.tsx     # Admin layout wrapper
│   ├── StudentLayout.tsx   # Student layout wrapper
│   └── ProtectedRoute.tsx  # Route protection
├── lib/                     # Utility functions
│   ├── api.ts              # Axios configuration
│   ├── auth.ts             # Authentication utilities
│   └── utils.ts            # Helper functions
├── services/                # API service layer
│   ├── adminService.ts     # Admin API calls
│   └── studentService.ts   # Student API calls
├── hooks/                   # Custom React hooks
├── public/                  # Static assets
└── styles/                  # Global styles
\`\`\`

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Import your repository in Vercel
3. Add environment variables in Vercel dashboard
4. Deploy!

### Other Platforms

Build the production bundle:
\`\`\`bash
npm run build
npm run start
\`\`\`

## Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| \`NEXT_PUBLIC_API_URL\` | Backend API URL | Yes |

## Features Overview

### Admin Dashboard
- User management
- University/College management
- Course and program management
- Exam creation and management
- Question bank management
- Payment tracking
- Real-time analytics

### Student Dashboard
- Exam browsing and taking
- Progress tracking
- Performance analytics
- Achievement system
- Payment history

## Error Handling

The application includes comprehensive error handling:
- Network error detection
- API timeout handling (15s)
- Automatic token refresh
- Graceful fallbacks with placeholder data
- User-friendly error messages

## Security Features

- JWT-based authentication
- Protected routes
- Role-based access control (RBAC)
- Secure token storage
- API request interceptors
- XSS protection
- CSRF protection

## Performance Optimizations

- Code splitting
- Lazy loading
- Image optimization
- API response caching
- Debounced search
- Optimistic UI updates

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (\`git checkout -b feature/amazing-feature\`)
3. Commit your changes (\`git commit -m 'Add some amazing feature'\`)
4. Push to the branch (\`git push origin feature/amazing-feature\`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Support

For support, email support@examb.com or join our Slack channel.

## Acknowledgments

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Radix UI](https://www.radix-ui.com/)
- [Lucide Icons](https://lucide.dev/)
