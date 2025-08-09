# Git Repository Setup Commands

## Step 1: Create Repository on GitHub/GitLab
1. Go to GitHub.com and click "New Repository"
2. Repository name: `gentharvan-crush-detector`
3. Description: `AI-powered crush detector with romantic theme and interactive questionnaire`
4. Make it Public (or Private if preferred)
5. DON'T initialize with README (we already have one)

## Step 2: Local Git Setup Commands

```bash
# Initialize git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: Gentharvan Crush Detector

✨ Features:
- AI-powered crush detection with questionnaire
- File upload support for images and videos  
- Romantic themed UI with meme aesthetic
- Real-time analysis with entertaining results
- Full-stack TypeScript application

🛠️ Tech Stack:
- React 18 + TypeScript frontend
- Express.js + Node.js backend
- PostgreSQL with Drizzle ORM
- Tailwind CSS + Radix UI
- TanStack Query for state management

🎨 Design:
- Discord-inspired dark theme
- Romantic color palette (pink, purple, red)
- Gaming aesthetic with meme culture
- Fully responsive design

Ready for deployment!"

# Connect to your GitHub repository (replace with your actual URL)
git remote add origin https://github.com/YOUR_USERNAME/gentharvan-crush-detector.git

# Set main branch and push
git branch -M main
git push -u origin main
```

## Step 3: Environment Setup for Others

After cloning your repository, users should:

```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/gentharvan-crush-detector.git
cd gentharvan-crush-detector

# Install dependencies
npm install

# Copy environment template
cp .env.example .env

# Edit .env with actual database credentials
# Then start development server
npm run dev
```

## Repository Topics/Tags to Add on GitHub:
- `crush-detector`
- `ai-analysis` 
- `react`
- `typescript`
- `express`
- `questionnaire`
- `romantic-theme`
- `file-upload`
- `entertainment`
- `meme-app`