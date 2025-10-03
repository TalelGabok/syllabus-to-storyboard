# Syllabus to Storyboard Generator

AI-powered tool that transforms training syllabi into production-ready microlearning storyboards. Converts comprehensive course outlines into engaging 3-5 minute lessons optimized for modern learners.

## 🎯 Purpose

This tool bridges the gap between curriculum design and content production by automatically generating:
- Slide-by-slide storyboards
- On-screen bullet points (30-70 words per slide)
- Natural voiceover scripts (60-90 words per slide)
- Timing specifications (20-30 seconds per slide)
- Layout recommendations for each slide

## 🌟 Features

- **JSON Input** - Upload or paste syllabus JSON from the Training Syllabus Generator
- **AI-Powered Generation** - Uses OpenAI GPT-4 or Anthropic Claude
- **Template-Based** - Follows proven microlearning storyboard structure
- **Editable Output** - Review and modify generated content inline
- **Multiple Export Formats** - Download as JSON or CSV
- **Production-Ready** - Includes timing, word counts, and layout specs

## 🚀 Quick Start

### Live Site

Visit: `https://YOUR-USERNAME.github.io/REPO-NAME/syllabus-to-storyboard.html`

### Getting Started

1. **Get an API Key**:
   - [OpenAI API Key](https://platform.openai.com/api-keys)
   - [Anthropic API Key](https://console.anthropic.com/)

2. **Prepare Your Syllabus**:
   - Use the Training Syllabus Generator, or
   - Use an existing syllabus JSON file

3. **Generate Storyboard**:
   - Enter your API key
   - Upload or paste your syllabus JSON
   - Click "Generate Microlearning Storyboard"
   - Review and edit the output
   - Download as JSON or CSV

## 📋 How to Use

### Step 1: Configure API
- Select your AI provider (OpenAI or Anthropic)
- Enter your API key
- Key is used only in your browser session

### Step 2: Load Syllabus
**Option A: Upload File**
- Click "Browse" and select your syllabus JSON file
- File is parsed immediately

**Option B: Paste JSON**
- Paste your syllabus JSON into the text area
- Click "Load JSON"

### Step 3: Generate
- Click "Generate Microlearning Storyboard"
- AI analyzes the syllabus and creates an optimal storyboard
- Generation takes 10-30 seconds depending on complexity

### Step 4: Review & Export
- Review each slide
- Check timing and word counts
- Download as JSON (for LMS) or CSV (for production teams)

## 📐 Storyboard Structure

Each generated storyboard includes:

### Slide Types
1. **Title Slide** - Course intro and target audience
2. **Why It Matters** - Business relevance and context
3. **Objectives Overview** - 3-4 key learning objectives
4. **Objective Details** (2-4 slides) - Deep dive on each objective
5. **Module Highlights** - Key curriculum topics
6. **Try It Now** - Practical application steps
7. **Prerequisites** (if applicable) - Required knowledge
8. **Tools/Materials** (if applicable) - Resources needed
9. **Recap** - Summary of key points
10. **Call to Action** - Next steps for learners

### Slide Specifications
- **Duration**: 20-30 seconds per slide
- **On-Screen Text**: 30-70 words (bullets/phrases)
- **Voiceover Script**: 60-90 words (natural, conversational)
- **Total Duration**: 3-5 minutes (180-300 seconds)
- **Total Slides**: 8-12 slides

## 📊 Output Formats

### JSON Format
Structured data including:
```json
{
  "course_title": "Course name",
  "target_duration_seconds": 240,
  "total_slides": 10,
  "slides": [
    {
      "slide_number": 1,
      "id": "title",
      "layout": "title",
      "title": "Slide title",
      "on_screen_points": ["Point 1", "Point 2"],
      "script": "Voiceover script text",
      "duration_seconds": 25,
      "notes": "Production notes"
    }
  ]
}
```

### CSV Format
Tabular format with columns:
- Slide #
- Title
- Layout
- On-Screen Points
- Script
- Duration (seconds)
- Notes

Perfect for production teams using tools like Excel, Google Sheets, or project management software.

## 🎓 Best Practices

### For Better Results
1. **Start with quality syllabi** - Detailed objectives and curriculum produce better storyboards
2. **Review objectives** - Ensure they're action-oriented and specific
3. **Check timing** - Verify total duration fits your target (3-5 minutes)
4. **Adjust scripts** - Edit for your brand voice and terminology
5. **Consider your audience** - Ensure language and complexity match learner level

### Production Workflow
1. Generate initial storyboard from syllabus
2. Review and edit scripts for clarity and brand voice
3. Adjust timing based on actual voiceover recording speed
4. Export CSV for production team handoff
5. Use JSON for LMS integration or system automation

## 🛠️ Technology

- **Pure JavaScript** - No dependencies, runs entirely in browser
- **Tailwind CSS** - Modern, responsive styling
- **OpenAI GPT-4** - AI generation option
- **Anthropic Claude** - AI generation option
- **No Backend** - Completely client-side processing

## 💡 Use Cases

- **Rapid Course Development** - Convert existing syllabi to microlearning quickly
- **Pilot Programs** - Test new training concepts with minimal investment
- **Outsourced Production** - Provide detailed specs to production vendors
- **LMS Integration** - Generate structured content for learning platforms
- **Quality Assurance** - Ensure consistent structure across courses
- **Resource Planning** - Estimate production time and costs accurately

## 📏 Design Constraints

Following proven microlearning principles:
- **3-5 minute lessons** - Optimal for retention and completion
- **Single learning objective per slide** - Prevents cognitive overload
- **Conversational scripts** - Natural tone increases engagement
- **Action-oriented** - Practical application in every lesson
- **Mobile-friendly duration** - Fits attention spans and schedules

## 🔒 Security & Privacy

- No data stored on servers
- API keys used only in browser session
- API calls go directly to OpenAI/Anthropic
- All processing happens client-side
- No tracking or analytics

## ⚠️ Important Notes

- Requires active API key from OpenAI or Anthropic
- API usage incurs costs per generation
- Generated content should be reviewed by subject matter experts
- Scripts may need editing for brand voice and terminology
- Timing estimates assume average speaking speed (140 WPM)

## 💰 Cost Management

- Each generation uses ~3,000-4,000 tokens
- OpenAI GPT-4: ~$0.03-0.05 per storyboard
- Anthropic Claude: ~$0.02-0.04 per storyboard
- Consider setting usage limits in your API dashboard

## 🔗 Related Tools

Works seamlessly with:
- **Training Syllabus Generator** - Creates the input syllabi
- **LMS Platforms** - Import JSON for structured content
- **Production Tools** - CSV exports work with Excel, Sheets, Airtable
- **Video Production Software** - Scripts ready for voiceover recording

## 📞 Support

For questions, issues, or feature requests, contact your development team.

## 📄 License

Proprietary - Internal Use Only

---

**Version**: 1.0.0  
**Last Updated**: October 2025
