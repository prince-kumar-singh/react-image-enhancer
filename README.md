# React Image Enhancer

A powerful web application that leverages AI to enhance image quality using the PicWish API. Upload any image and get an enhanced version with improved resolution, clarity, and color balance in real-time.

## 🛠 Project Information
- **Type**: Web Application
- **Stack**: React 18 + Vite 4 + TailwindCSS 3
- **API**: PicWish Image Enhancement API v1.0
- **License**: MIT

## 🎯 Key Features
- **Drag & Drop Upload**: Intuitive file upload with drag-and-drop support
- **Real-time Enhancement**: Live preview of enhancement progress
- **Image Comparison**: Side-by-side view of original and enhanced images
- **Responsive Design**: Optimized for mobile, tablet, and desktop views
- **Loading States**: Smooth loading transitions with spinner animation

## 📦 Project Structure
```
react-image-enhancer/
├── src/
│   ├── components/           # React components
│   │   ├── Home.jsx         # Main page component
│   │   ├── ImagePreview.jsx # Image comparison component
│   │   ├── ImageUpload.jsx  # File upload component
│   │   └── Loading.jsx      # Loading spinner component
│   ├── utils/
│   │   └── enhanceImageApi.js # PicWish API integration
│   ├── App.jsx             # Root component
│   └── main.jsx           # Entry point
├── public/                # Static assets
├── .env                  # Environment variables
├── vite.config.js        # Vite configuration
└── eslint.config.js      # ESLint configuration
```

## 🏗 Architecture
- **Component Architecture**
  - [`Home`](src/components/Home.jsx): Main container managing state and image processing
  - [`ImageUpload`](src/components/ImageUpload.jsx): Handles file selection
  - [`ImagePreview`](src/components/ImagePreview.jsx): Displays original and enhanced images
  - [`Loading`](src/components/Loading.jsx): Shows loading animation

- **State Management**
  - Local state with useState in Home component
  - Props for component communication
  - File handling with URL.createObjectURL

- **API Integration**
  - Axios for HTTP requests to PicWish API
  - Polling mechanism for enhancement status
  - Error handling with try-catch blocks

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+)
- npm or yarn
- PicWish API Key

### Installation
1. Clone and install dependencies:
```bash
git clone https://github.com/yourusername/react-image-enhancer.git
cd react-image-enhancer
npm install
```

2. Add your PicWish API key in [.env](http://_vscodecontentref_/0):
```bash
PICWISE_API_KEY=your_api_key_here
```

3. Start development server:
```bash
npm run dev
```

## 🔧 Built With
- React.js 18 with Vite
- TailwindCSS for styling
- Axios for API calls



