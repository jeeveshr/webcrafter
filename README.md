# Lovable Portfolio - 3D Interactive Portfolio Website

A high-performance, visually immersive portfolio website featuring 3D interactive elements, smooth animations, and responsive design.

## 🚀 Features

### 3D Design & Interactivity
- **Three.js Integration**: Immersive 3D floating shapes and interactive elements
- **React Three Fiber**: Optimized 3D rendering with React
- **Interactive Elements**: Hover effects, mouse tracking, and smooth transitions
- **3D Skill Visualization**: Floating skill spheres on the About page
- **Performance Optimized**: Lazy loading and code splitting for 3D components

### Responsive Design
- **Mobile-First**: Fully responsive across all devices
- **Touch-Friendly**: Optimized for touch interactions
- **Adaptive 3D**: Simplified 3D elements on mobile for better performance
- **CSS Grid/Flexbox**: Modern layout system

### Full-Stack Features
- **Form Validation**: Zod schema validation with client-side error handling
- **SEO Optimized**: Dynamic meta tags for each page
- **Performance Monitoring**: Web Vitals tracking (LCP, FID, CLS)
- **Security**: Input sanitization and validation

### Design System
- **Glassmorphism**: Modern glass-effect UI components
- **Gradient System**: Custom gradients (purple-blue theme)
- **Animation Library**: Framer Motion for smooth transitions
- **Semantic Tokens**: Consistent design tokens throughout

## 📦 Tech Stack

- **Frontend**: React 18 + TypeScript
- **3D Graphics**: Three.js + React Three Fiber + Drei
- **Animations**: Framer Motion
- **Styling**: Tailwind CSS
- **Routing**: React Router v6
- **Form Validation**: Zod
- **UI Components**: shadcn/ui
- **Build Tool**: Vite

## 🛠️ Installation

```bash
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to project
cd <YOUR_PROJECT_NAME>

# Install dependencies
npm install

# Start development server
npm run dev
```

## 📁 Project Structure

```
src/
├── components/
│   ├── three/           # 3D components
│   │   ├── Scene3D.tsx
│   │   ├── FloatingShapes.tsx
│   │   ├── ProjectCard3D.tsx
│   │   └── SkillSphere.tsx
│   ├── Navigation.tsx
│   ├── SEO.tsx
│   └── PerformanceMonitor.tsx
├── pages/
│   ├── Home.tsx         # 3D hero section
│   ├── Work.tsx         # Filterable project gallery
│   ├── About.tsx        # Skills + 3D visualization
│   └── Contact.tsx      # Validated contact form
├── index.css            # Design system tokens
└── App.tsx
```

## 🎨 Design System

### Colors (HSL)
- **Primary**: `hsl(262 83% 58%)` - Purple
- **Secondary**: `hsl(221 83% 53%)` - Blue
- **Accent**: `hsl(328 85% 55%)` - Pink
- **Background**: `hsl(250 100% 4%)` - Dark

### Gradients
- `--gradient-primary`: Purple to blue
- `--gradient-accent`: Pink to purple
- `--gradient-subtle`: Background gradient

### Typography
- **Font**: Inter (Google Fonts)
- **Weights**: 400-900

## 🚀 Performance

### Optimizations Implemented
- ✅ Lazy loading for 3D components
- ✅ Code splitting with React.lazy
- ✅ Optimized 3D assets (minimal geometry)
- ✅ Web Vitals monitoring
- ✅ Semantic HTML for SEO
- ✅ Dynamic meta tags

### Target Metrics
- **LCP**: < 2.5s
- **FID**: < 100ms
- **CLS**: < 0.1

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔒 Security

- Input validation with Zod schemas
- Client-side and server-side validation ready
- XSS prevention through React's built-in escaping
- No sensitive data in client-side code

## 📝 Pages

### Home (`/`)
- 3D hero section with floating shapes
- Call-to-action buttons
- Stats showcase

### Work (`/work`)
- Filterable project gallery
- Category-based filtering
- 3D hover effects on project cards

### About (`/about`)
- Interactive 3D skill spheres
- Skills grid with categories
- Experience timeline

### Contact (`/contact`)
- Validated contact form
- Real-time error feedback
- Contact information cards

## 🎯 SEO

Each page includes:
- Unique title tags
- Meta descriptions
- OpenGraph tags
- Twitter cards
- Canonical URLs

## 🔧 Environment Setup

No environment variables required for basic functionality.

For backend integration, add:
- Email service API keys (optional)
- Analytics tracking (optional)

## 📈 Future Enhancements

- [ ] Backend API integration for contact form
- [ ] CMS integration for projects
- [ ] Blog section
- [ ] Advanced WebGL shaders
- [ ] Sound effects
- [ ] Dark/light mode toggle

## 📄 License

MIT License - feel free to use this project as a template!

## 🤝 Contributing

Contributions welcome! Please open an issue or submit a pull request.

## 📞 Contact

For questions or collaboration: hello@lovable.dev

---

Built with ❤️ using Lovable
