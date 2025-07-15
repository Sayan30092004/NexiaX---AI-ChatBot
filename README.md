# NexiaX - AI Chatbot with DeepThink Mode

![NexiaX Screenshot](public/screenshot.png)

NexiaX is a modern AI-powered chatbot application featuring:
- Gemini AI integration for intelligent responses
- Markdown rendering with syntax highlighting
- PDF document analysis capability
- DeepThink mode for comprehensive topic analysis
- Responsive design for all devices
- Dark/Light theme toggle
- Conversation history management

## Features

✨ **AI-Powered Chat** - Powered by Google's Gemini AI  
🧠 **DeepThink Mode** - In-depth analysis of complex topics  
📄 **PDF Analysis** - Upload and extract text from PDF documents  
📝 **Markdown Support** - Beautifully rendered markdown with code highlighting  
🌓 **Dark/Light Theme** - Toggle between midnight and light themes  
📱 **Mobile Optimized** - Fully responsive design  
💬 **Conversation History** - Save and switch between conversations  

## Technologies Used

- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS
- shadcn/ui components
- Gemini AI API
- PDF.js for PDF parsing
- Framer Motion for animations
- React Markdown for markdown rendering
- Sonner for toast notifications
- JS Confetti for celebration effects

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/nexiax-chatbot.git
cd nexiax-chatbot
```
2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```
3. Create a .env.local file in the root directory and add your Gemini API key:
```env
NEXT_PUBLIC_GEMINI_API_KEY=your_api_key_here
```
4. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

## Configuration
The project requires the following configuration:

  1. Gemini API Key: Obtain from Google AI Studio and add to .env.local
  2. PDF.js Worker: Automatically loaded from CDN in the component
  3. Tailwind Config: Included in the project

## Project Structure
```text
nexiax-chatbot/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── (other Next.js pages)
├── components/
│   └── ChatBot.tsx (main component)
├── public/
│   └── logo.png (application logo)
├── styles/
│   └── globals.css
├── package.json
├── tailwind.config.js
└── tsconfig.json
```
## Environment Variables
The following environment variables are required:

  NEXT_PUBLIC_GEMINI_API_KEY - Your Google Gemini API key

## Known Issues
PDF parsing may fail with very large files

DeepThink mode consumes more API tokens

Mobile performance may degrade with many conversation items
