# IT Issues & Helpful Tricks

A curated collection of 100+ IT troubleshooting topics, guides, and quick solutions for Windows, macOS, Mobile, Networking, Security, Productivity, and Emerging Tech.  
This project is designed to help users and content creators quickly find, explain, and share solutions to common IT problems.

## Features

- **Topic Explorer:** Browse and search a wide range of IT topics.
- **Detailed Guides:** Each topic includes quick solutions and a detailed, multi-page explanation.
- **PDF Export:** Download any topic as a formatted PDF.
- **Modern UI:** Responsive, clean design using Tailwind CSS.
- **YouTube Integration:** Placeholder links for related video content.

## Usage

1. **Open `index.html`** to browse all topics.
2. **Click a topic** to view its detailed guide in `topic.html`.
3. **Export as PDF** using the "Download as PDF" button on any topic page.

## Structure

- `index.html` — Main topic explorer.
- `topic.html` — Detailed view for each topic.
- `README.md` — This documentation.
- `100+ YouTube Topic Ideas_ IT Tricks & Troubleshooting.pdf` — Reference PDF (optional).

## How to Add or Edit Topics

- Topics are stored in the `topicsData` array in `topic.html`.
- Each topic should have:
  - `title`
  - `category`
  - `solutions` (array of quick tips)
  - `details` (HTML-formatted, multi-page guide)

## Customization

- **Images:** Update the `getTopicImage` function in `topic.html` to change topic images.
- **YouTube Links:** Update the `getYoutubeLink` function for real video URLs (use `https://youtu.be/p4kQbt0QUkY`).
- **Styling:** Modify Tailwind classes in the HTML for custom look and feel.

## License

MIT License.  
Content and code are free to use and adapt for educational or non-commercial purposes.

---

*Created by [cybertech](https://youtu.be/p4kQbt0QUkY). Powered by IT Topic Explorer.*
