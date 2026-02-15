# Project 1: QR Code Generator

## Skills Demonstrated

### Git & GitHub
- Created and managed GitHub repository
- Used feature branches for development
- Created pull requests with issue references
- Merged PRs to main branch
- Used git worktrees for parallel development

### GitHub Issues
- Planned project with 6 feature issues
- Tracked progress by closing completed issues
- Referenced issues in PR descriptions (Closes #X)

### HTML/CSS/JavaScript
- Built single-file HTML application
- Styled with CSS gradients, flexbox, and transitions
- Used vanilla JavaScript for interactivity
- Integrated third-party library (QRCode.js) via CDN

### Browser APIs
- localStorage for persisting history
- Clipboard API for copy functionality
- Canvas API for image generation and download
- Blob API for file creation

### Development Workflow
- Parallel feature development with worktrees
- Incremental commits with clear messages
- Testing features in browser before merging

## Challenges Overcome

1. **Clipboard API** - Learning async clipboard operations for copying images
2. **Canvas to PNG** - Converting QRCode.js canvas output to downloadable files
3. **History Management** - Deduplicating and limiting localStorage entries

## What I Would Do Differently

- Add more input validation
- Include QR code scanning functionality
- Add more export formats (SVG, PDF)
