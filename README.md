# Ambience-AI Development Blog

A biweekly development blog documenting the Ambience-AI-1.5 clinical decision-support platform project. The blog covers research, design decisions, implementation challenges, and testing outcomes across a 24-week development timeline.

## Overview

This is a static, fully self-contained blog that runs on GitHub Pages. It features:

- **12 biweekly blog entries** covering the complete project lifecycle
- **Rich media**: code snippets, diagrams, screenshots, and UI design iterations
- **Research and reference materials**: key medical guidelines, evaluation methodology
- **Responsive design**: works on desktop, tablet, and mobile devices
- **No dependencies**: pure HTML, CSS, and JavaScript

## Blog Contents

### Key Topics Covered

1. **Problem Framing** (Weeks 1-2): Specialist interviews and A&G workflow analysis
2. **Requirements & Planning** (Weeks 3-4): MoSCoW prioritization and risk identification
3. **Infrastructure Setup** (Weeks 5-6): Gaudi 2 server configuration and Med42 70B deployment
4. **Stabilisation** (Weeks 7-8): Configuration hardening and citation mapping
5. **RAG Implementation** (Weeks 9-10): Document ingestion pipeline and database schema
6. **Product Decisions** (Weeks 11-12): Merging workflows and UI refinements
7. **Architecture Pivot** (Weeks 13-14): Intelligent routing strategy (local + cloud)
8. **Model Selection** (Weeks 15-16): Med42 8B quantization and RunPod deployment
9. **Integration** (Weeks 17-18): Retrieval quality improvements and evidence grounding
10. **Testing Phase** (Weeks 19-20): End-to-end scenarios and edge case validation
11. **Performance & Reliability** (Weeks 21-22): Benchmarking and failure handling
12. **Handover & Polish** (Weeks 23-24): Final evaluation and deployment readiness

### Content Features

- **Code snippets** from the RAG pipeline, model routing, and failure handling
- **Architecture diagrams** showing system design and data flow
- **UI design iterations** and HCI component sketches
- **Screenshots** of the final platform interfaces
- **Research callouts** highlighting key findings and metrics
- **MoSCoW tables** showing requirements prioritization
- **Performance benchmarks** and evaluation results

## File Structure

```
Public Blog/
├── index.html              # Main blog page with all entries
├── style.css               # Polished, responsive stylesheet
├── README.md               # This file
├── .gitignore              # Git ignore rules
└── assets/                 # Media files
    ├── demo/               # Platform screenshots
    ├── diagrams/           # Architecture and pipeline diagrams
    ├── ui-design/          # Design sketches and iterations
    ├── partners/           # Partner logos (UCL, NHS, Intel)
    └── team/               # Team member photos
```

## Viewing Locally

To view the blog locally, simply open `index.html` in a web browser:

```bash
open index.html
```

Or use a local web server for better performance:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Deploying to GitHub Pages

### Option 1: Using GitHub's Built-in Pages (Recommended)

1. **Create a new GitHub repository** named `ambience-ai-blog` (or your preferred name)

2. **Push this code to GitHub:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/ambience-ai-blog.git
   git branch -M main
   git add .
   git commit -m "Initial blog deployment with 12 biweekly entries"
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your blog:**
   - Your blog will be live at `https://YOUR_USERNAME.github.io/ambience-ai-blog/`
   - GitHub will build and deploy automatically after each push

### Option 2: Organization or User Site

If you want your blog at `YOUR_USERNAME.github.io/` directly:

1. Create a repository named `YOUR_USERNAME.github.io`
2. Push this content to that repository
3. GitHub Pages will automatically deploy to `https://YOUR_USERNAME.github.io/`

## Updating the Blog

To add new blog entries:

1. Edit `index.html` and add a new `<article class="post">` section
2. Include the post in the sidebar navigation
3. Commit and push to GitHub:
   ```bash
   git add index.html
   git commit -m "Add weeks 25-26 blog entry: [Title]"
   git push
   ```

GitHub will automatically rebuild and deploy your changes within seconds.

## Design Features

- **Sticky navigation header** with project branding
- **Responsive hero section** with project overview and screenshots
- **Sidebar navigation** with intelligent active state tracking
- **Rich post formatting**:
  - Code blocks with syntax highlighting
  - Image galleries and captions
  - Callout boxes for research and reference materials
  - MoSCoW requirement tables
  - Blockquotes and emphasis styling
- **Mobile-optimized** layout that works on all screen sizes

## Technology Stack

- **HTML5** for semantic markup
- **CSS3** for styling and responsive design
  - Custom CSS variables for theming
  - Flexbox and CSS Grid for layout
  - Smooth scroll behavior and transitions
- **Vanilla JavaScript** for interactivity
  - Header scroll detection
  - Sidebar active state tracking
  - Mobile navigation toggle

## Browser Support

Works in all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

To contribute improvements to the blog:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This development blog is part of the Ambience-AI-1.5 project. For licensing details, see the main project repository.

## Contact

For questions about the Ambience-AI project, see the main repository at [https://github.com/hyardim/Ambience-AI-1.5](https://github.com/hyardim/Ambience-AI-1.5)

For the technical report and comprehensive project documentation, visit [https://github.com/hyardim/SystemsEng-Team20-Website](https://github.com/hyardim/SystemsEng-Team20-Website)

---

**Last updated:** March 2026
**Blog entries:** 12 biweekly posts covering 24-week project timeline
