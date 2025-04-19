# Google Slides to PDF Converter Bot 🤖📊➡️📄

Automatically convert Google Slides presentations to PDF documents with this Python-based automation tool. Perfect for archiving presentations, creating offline backups, or generating printable versions of your slide decks.

## Key Features
- 🖥️ **Automated Google Slides Capture**: Navigates through slides using keyboard simulation
- 📸 **Smart Screenshotting**: Captures high-resolution screenshots of each slide
- 📂 **PDF Compilation**: Bundles captured slides into a single PDF file
- ⚙️ **Customizable Workflow**: Adjust delays, output locations, and slide count
- 🤖 **Headless Browser**: Runs Chrome in background mode for efficient operation

## Use Cases
- Create printable versions of Google Slides presentations
- Archive important slide decks as PDFs
- Generate client-ready PDF deliverables automatically
- Convert presentations for offline viewing

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Chrome browser installed
- [ChromeDriver](https://chromedriver.chromium.org/)

# Install dependencies
pip install selenium pillow

# Basic Usage
# Configure and run
python slides_to_pdf.py \
  --url "YOUR_GOOGLE_SLIDES_URL" \
  --slides 25 \
  --delay 3

## Configuration Options

# Parameter	Description	Default Value
--url	Google Slides shareable URL	Required
--slides	Number of slides to capture	10
--delay	Seconds between slide transitions	2
--output-dir	Custom save location	C:\Users\...\printsbot\ (platform specific)

## 💡 Why This Exists?

-Many organizations use Google Slides for collaborative presentations but need PDF versions for:

-Client deliverables

-Compliance requirements

-Archival purposes

-Printed materials

-This bot solves the manual export process while preserving exact slide layouts.

## ⚠️ Important Notes

-Requires valid Google Slides publishing URL (File > Share > Publish to web)

-Ensure ChromeDriver version matches your Chrome browser

-Test in non-headless mode first using --no-headless flag

