# 🏙️ CivicLens - AI-Powered Smart City Issue Reporter

[![React](https://img.shields.io/badge/React-18.3.1-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.1-blue.svg)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-5.4.2-purple.svg)](https://vitejs.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Making cities better through AI-powered issue reporting** 🚀

CivicLens is a modern, citizen-facing platform that revolutionizes how people report city infrastructure issues. Using AI-powered classification and intelligent routing, it transforms simple photo uploads into actionable government reports.

![CivicLens Demo](https://images.unsplash.com/photo-1449824913935-59a10b8d2000?w=800&h=400&fit=crop&crop=center)

## ✨ Features

### 🤖 AI-Powered Classification
- **Automatic Issue Detection**: Upload photos and get instant AI classification
- **Smart Categorization**: Potholes, streetlights, flooding, trash, graffiti, and more
- **Severity Assessment**: AI determines priority levels (Low, Medium, High, Critical)
- **Confidence Scoring**: Transparent AI decision-making process

### 📍 Location Intelligence
- **GPS Integration**: Automatic location capture with user permission
- **Manual Address Input**: Fallback for areas with poor GPS signal
- **District Mapping**: Automatic routing to appropriate municipal departments
- **Address Validation**: Geocoding for accurate location data

### 📊 Comprehensive Dashboard
- **Real-time Statistics**: Track total issues, new reports, and resolution rates
- **Advanced Filtering**: Search by status, severity, location, and date
- **Status Management**: Update issue progress from reported to resolved
- **Visual Analytics**: Charts and graphs for municipal insights

### 🎨 Modern User Experience
- **Mobile-First Design**: Optimized for smartphone reporting
- **Responsive Layout**: Works seamlessly across all devices
- **Intuitive Interface**: Clean, government-friendly design
- **Accessibility**: WCAG compliant for all citizens

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/civiclens.git
   cd civiclens
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Build for Production
```bash
npm run build
npm run preview
```

## 🏗️ Project Structure

```
src/
├── components/          # React components
│   ├── Header.tsx      # Navigation header
│   ├── ReportForm.tsx  # Issue reporting form
│   └── Dashboard.tsx   # Admin dashboard
├── types/              # TypeScript definitions
│   └── index.ts        # Core interfaces
├── utils/              # Utility functions
│   ├── aiClassification.ts  # AI simulation
│   ├── location.ts     # GPS & geocoding
│   └── storage.ts      # Local storage
├── App.tsx             # Main application
└── main.tsx           # Entry point
```

## 🎯 Use Cases

### For Citizens
- **Quick Reporting**: Snap a photo, add description, submit in under 2 minutes
- **Track Progress**: Monitor your reports from submission to resolution
- **Community Impact**: See all issues in your neighborhood
- **Anonymous Options**: Report without personal information if preferred

### For Municipal Governments
- **Automated Triage**: AI classifies and routes issues automatically
- **Resource Planning**: Analytics help allocate maintenance resources
- **Citizen Engagement**: Transparent communication about issue resolution
- **Data-Driven Decisions**: Historical data for infrastructure planning

## 🔧 Technology Stack

### Frontend
- **React 18** - Modern UI library with hooks
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Lucide React** - Beautiful icon library
- **Vite** - Fast build tool and dev server

### AI & Classification
- **Simulated AI Models** - Ready for Hugging Face integration
- **Image Classification** - Infrastructure issue detection
- **Text Processing** - Natural language understanding
- **Confidence Scoring** - Transparent AI decisions

### Data & Storage
- **Local Storage** - Client-side data persistence
- **JSON Structure** - Structured issue data
- **Image Handling** - File upload and preview
- **Export Capabilities** - Data portability

## 🌟 Key Features Deep Dive

### AI Classification Engine
```typescript
// Intelligent issue categorization
const classification = classifyIssue(description, images);
// Returns: { category, severity, confidence }
```

### Location Services
```typescript
// GPS location capture
const location = await getCurrentLocation();
// Geocoding for addresses
const coords = await geocodeAddress(address);
```

### Report Generation
```typescript
// Formal government reports
const report = generateReport(description, category, severity, location);
```

## 📱 Mobile Experience

CivicLens is designed mobile-first for on-the-go reporting:

- **Camera Integration**: Direct photo capture from mobile devices
- **Touch-Optimized**: Large buttons and intuitive gestures
- **Offline Capability**: Queue reports when connectivity is poor
- **Push Notifications**: Updates on report status (future feature)

## 🔮 Future Enhancements

### Phase 2 - Advanced AI
- [ ] Real Hugging Face model integration
- [ ] Image segmentation for precise issue location
- [ ] Video analysis capabilities
- [ ] Multi-language support

### Phase 3 - Government Integration
- [ ] Municipal API connections
- [ ] Automated department routing
- [ ] Citizen notification system
- [ ] Performance analytics

### Phase 4 - Community Features
- [ ] Citizen voting on issue priority
- [ ] Community discussion threads
- [ ] Volunteer coordination
- [ ] Gamification elements

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit changes**: `git commit -m 'Add amazing feature'`
4. **Push to branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Development Guidelines
- Follow TypeScript best practices
- Maintain responsive design principles
- Add tests for new features
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Hugging Face** - AI model inspiration
- **Unsplash** - Stock photography
- **Lucide** - Beautiful icons
- **Tailwind CSS** - Styling framework
- **React Community** - Ongoing support and resources

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/civiclens/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/civiclens/discussions)
- **Email**: support@civiclens.com

---

<div align="center">

**Built with ❤️ for smarter cities**

[Demo](https://civiclens-demo.vercel.app) • [Documentation](https://docs.civiclens.com) • [API Reference](https://api.civiclens.com)

</div>
