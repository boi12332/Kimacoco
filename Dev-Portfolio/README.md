# Portfolio

This is a modern portfolio website and admin dashboard, powered by Supabase backend and hosted on GitHub Pages.

## Features
- Modern UI (2025 trends): card/grid layouts, icons, animated backgrounds
- Fully dynamic admin dashboard: manage Home, About, Contact, Projects, Skills, Qualifications
- Image upload/preview, modal confirmations, toast alerts
- Strong client-side validation, input sanitization, secure authentication
- Undo/redo actions for admin changes
- Supabase backend for data management and authentication
- Easy deployment on GitHub Pages

## Technology Stack
- HTML5, CSS3 (Poppins font, Unicons icons)
- JavaScript (ES6+)
- Supabase (PostgreSQL database, Auth, Storage)
- GitHub Pages (static hosting)
- Swiper.js (portfolio slider)

## Tools Used
- Visual Studio Code (development)
- Git & GitHub (version control, hosting)
- Supabase Dashboard (database, auth, storage management)
- Figma (UI/UX design)
- Chrome DevTools (debugging)
- Node.js (optional, for local development server)

## Deployment Steps
1. Create a Supabase project at [supabase.com](https://supabase.com)
   - Set up tables: home, about, contact, projects, skills, qualifications, users
   - Get your Supabase project URL and anon/public API key
2. Clone this repository or upload your files
3. Update Supabase config in all admin pages with your project URL and API key
4. Push all files to your GitHub repository
   ```sh
   git add .
   git commit -m "Initial commit"
   git push -u origin main
   ```
5. Enable GitHub Pages in repository settings (set source to main branch)
6. Access your site at `https://yourusername.github.io/your-repo/`

## How to Use
- Log in via `admin-login.html` (Supabase Auth)
- Manage all portfolio sections via admin dashboard
- All changes are saved to Supabase and reflected on the main site

## Future Updates
- Integrate notifications and activity logs for admin actions
- Add multi-user roles and permissions
- Enable file uploads to Supabase Storage for larger assets
- Add analytics dashboard for site visits and user interactions
- Support for custom themes and branding
- API integration for blog, newsletter, or external services
- Progressive Web App (PWA) features for offline access
- Automated backups and export/import of portfolio data

---

© 2025 Raviraj Sarangan & contributors
