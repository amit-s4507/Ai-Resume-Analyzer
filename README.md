# AI Resume Analyzer 🚀

A modern, AI-powered resume analysis platform that provides comprehensive feedback on resumes using advanced Applicant Tracking System (ATS) optimization and AI-driven insights.

[![React Router](https://img.shields.io/badge/React%20Router-7.7.0-blue.svg)](https://reactrouter.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-4.1.4-38B2AC.svg)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## ✨ Features

### 🤖 AI-Powered Analysis
- **Comprehensive Resume Scoring**: Multi-dimensional analysis across 5 key areas
- **ATS Optimization**: Specialized scoring for Applicant Tracking System compatibility
- **Real-time Feedback**: Instant analysis with detailed improvement suggestions
- **Job-Specific Analysis**: Tailored feedback based on job title and description

### 📊 Detailed Scoring Categories
- **Overall Score**: Comprehensive resume rating (0-100)
- **ATS Score**: Applicant Tracking System compatibility
- **Tone & Style**: Professional communication assessment
- **Content Quality**: Information relevance and completeness
- **Structure**: Layout and organization evaluation
- **Skills Assessment**: Technical and soft skills analysis

### 🎯 User Experience
- **Drag & Drop Upload**: Seamless PDF resume upload
- **Visual Resume Preview**: Image conversion for easy viewing
- **Progress Tracking**: Real-time upload and analysis status
- **Responsive Design**: Mobile-first, cross-device compatibility
- **Dark/Light Theme**: Modern UI with accessibility features

### 🔒 Security & Privacy
- **Secure Authentication**: Puter.js integration for user management
- **File Encryption**: Secure file storage and processing
- **Privacy-First**: No data retention beyond analysis
- **Cloud Storage**: Scalable file management system

## 🛠️ Tech Stack

### Frontend
- **React 19.1.0** - Modern React with latest features
- **React Router 7.7.0** - Full-stack routing solution
- **TypeScript 5.8.3** - Type-safe development
- **Tailwind CSS 4.1.4** - Utility-first CSS framework
- **Zustand 5.0.6** - Lightweight state management

### Backend & Services
- **Puter.js** - Cloud platform for authentication, file storage, and AI
- **PDF.js** - PDF processing and conversion
- **React Dropzone** - File upload handling

### Development Tools
- **Vite 6.3.3** - Fast build tool and dev server
- **ESLint & Prettier** - Code quality and formatting
- **Docker** - Containerized deployment

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Modern web browser

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ai-resume-analyzer.git
   cd ai-resume-analyzer
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

### Environment Setup

The application uses Puter.js for backend services. No additional environment variables are required for development.

## 📁 Project Structure

```
ai-resume-analyzer/
├── app/
│   ├── components/          # Reusable UI components
│   │   ├── ATS.tsx         # ATS scoring component
│   │   ├── Details.tsx     # Detailed feedback display
│   │   ├── FileUploader.tsx # File upload interface
│   │   ├── ResumeCard.tsx  # Resume preview cards
│   │   └── Summary.tsx     # Score summary component
│   ├── lib/                # Utility libraries
│   │   ├── puter.ts        # Puter.js integration
│   │   ├── pdf2img.ts      # PDF to image conversion
│   │   └── utils.ts        # Helper functions
│   ├── routes/             # Application routes
│   │   ├── home.tsx        # Dashboard page
│   │   ├── upload.tsx      # Resume upload page
│   │   ├── resume.tsx      # Resume analysis page
│   │   └── auth.tsx        # Authentication page
│   └── root.tsx            # Root component
├── constants/              # Application constants
├── public/                 # Static assets
├── types/                  # TypeScript type definitions
└── package.json           # Dependencies and scripts
```

## 🔧 Available Scripts

- `npm run dev` - Start development server with HMR
- `npm run build` - Create production build
- `npm run start` - Start production server
- `npm run typecheck` - Run TypeScript type checking

## 🐳 Docker Deployment

### Build and Run with Docker

```bash
# Build the Docker image
docker build -t ai-resume-analyzer .

# Run the container
docker run -p 3000:3000 ai-resume-analyzer
```

### Supported Platforms
- **AWS ECS** - Elastic Container Service
- **Google Cloud Run** - Serverless containers
- **Azure Container Apps** - Managed container platform
- **Digital Ocean App Platform** - Managed app hosting
- **Fly.io** - Global edge deployment
- **Railway** - Modern deployment platform

## 📊 Performance Features

- **Server-Side Rendering (SSR)** - Fast initial page loads
- **Code Splitting** - Optimized bundle sizes
- **Image Optimization** - Efficient file processing
- **Caching Strategy** - Intelligent data caching
- **Progressive Enhancement** - Graceful degradation

## 🔍 Analysis Methodology

### ATS Scoring Criteria
- **Keyword Optimization**: Job-specific terminology matching
- **Format Compatibility**: Standard resume format adherence
- **Readability**: Clear, scannable content structure
- **Relevance**: Content alignment with job requirements

### Content Quality Metrics
- **Information Completeness**: Required sections presence
- **Professional Tone**: Appropriate language and style
- **Achievement Quantification**: Measurable accomplishments
- **Skill Relevance**: Technical and soft skills alignment

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Puter.js** - Cloud platform services
- **React Router** - Full-stack routing solution
- **Tailwind CSS** - Utility-first CSS framework
- **Claude AI** - Advanced resume analysis capabilities

## 📞 Support

- **Documentation**: [Project Wiki](https://github.com/yourusername/ai-resume-analyzer/wiki)
- **Issues**: [GitHub Issues](https://github.com/yourusername/ai-resume-analyzer/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/ai-resume-analyzer/discussions)

---

Built with ❤️ using modern web technologies to help job seekers optimize their resumes for success.
