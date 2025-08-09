# Contributing to Gentharvan - Crush Detector

Thank you for your interest in contributing to the Crush Detector! This document provides guidelines for contributing to the project.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/yourusername/gentharvan-crush-detector.git`
3. Install dependencies: `npm install`
4. Create a new branch: `git checkout -b feature/your-feature-name`

## Development Setup

### Prerequisites
- Node.js 18 or higher
- PostgreSQL database
- Git

### Environment Setup
1. Copy `.env.example` to `.env`
2. Fill in your database connection details
3. Run `npm run dev` to start the development server

## Code Style

### TypeScript
- Use TypeScript for all new code
- Follow strict type checking
- Use descriptive variable names
- Add JSDoc comments for complex functions

### React Components
- Use functional components with hooks
- Follow the atomic design pattern
- Keep components focused and reusable
- Use proper prop types with TypeScript interfaces

### Styling
- Use Tailwind CSS classes
- Follow the existing color scheme (crush-pink, crush-purple, etc.)
- Maintain responsive design principles
- Use the existing meme/gaming aesthetic

## Project Structure

```
├── client/src/
│   ├── components/     # Reusable UI components
│   ├── pages/         # Route-level components
│   ├── hooks/         # Custom React hooks
│   └── lib/           # Utilities and configurations
├── server/            # Express.js backend
├── shared/            # Shared TypeScript schemas
└── docs/              # Documentation
```

## Making Changes

### Frontend Changes
- Test components in isolation
- Ensure responsive design works
- Maintain accessibility standards
- Follow existing naming conventions

### Backend Changes
- Add proper error handling
- Include input validation with Zod
- Write clear API documentation
- Test with various file types and sizes

### Database Changes
- Use Drizzle ORM for schema changes
- Create migrations for structural changes
- Test with sample data
- Document schema relationships

## Testing

### Manual Testing
1. Upload various file types (images and videos)
2. Test questionnaire flow completely
3. Verify analysis results display correctly
4. Test on different screen sizes
5. Check error handling scenarios

### File Upload Testing
- Test with different file sizes (up to 50MB limit)
- Test supported formats: JPEG, PNG, GIF, MP4, WebM
- Test unsupported formats to ensure proper error handling
- Test very large files to verify size limits

## Submitting Changes

### Before Submitting
- [ ] Code follows existing style conventions
- [ ] All new features work as expected
- [ ] No console errors or warnings
- [ ] Responsive design maintained
- [ ] Error handling implemented
- [ ] Documentation updated if needed

### Pull Request Process
1. Update the README.md if you've made significant changes
2. Update the package.json version if applicable
3. Ensure your PR description clearly describes the changes
4. Link any relevant issues
5. Add screenshots for UI changes

### PR Template
```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] Manual testing completed
- [ ] Works on mobile devices
- [ ] Error scenarios handled

## Screenshots
(Include screenshots for UI changes)
```

## Feature Ideas

### Potential Enhancements
- Real AI integration with MediaPipe/DeepFace
- User accounts and history
- Social sharing features
- Advanced analytics dashboard
- Mobile app version
- Multi-language support

### Technical Improvements
- Add unit tests
- Implement caching
- Optimize image processing
- Add rate limiting
- Improve error messages

## Code Review Process

1. All submissions require review
2. Reviewers will check for:
   - Code quality and style
   - Functionality and testing
   - Security considerations
   - Performance impact
   - Documentation updates

## Community Guidelines

- Be respectful and constructive
- Help newcomers learn the codebase
- Share knowledge and best practices
- Report security issues privately
- Keep discussions focused and productive

## Getting Help

- Check existing issues before creating new ones
- Use descriptive titles and provide detailed descriptions
- Include screenshots for UI issues
- Tag issues appropriately (bug, feature, help wanted, etc.)

## Recognition

Contributors will be recognized in:
- GitHub contributors list
- Project documentation
- Release notes for significant contributions

Thank you for contributing to making crush detection more fun and accurate! 💕