# Think-Logger

A time stamp recorder to capture learners' processing. Users can capture or flag learners' thoughts and process by pressing buttons or keyboard shortcuts and classify them with colors.

## Features

- **Time-stamped recording**: Capture thoughts and processes with precise timestamps
- **Color-coded categories**: Classify entries with custom colors and categories
- **Keyboard shortcuts**: Use number keys (1-9) for quick categorization
- **Auto-save**: Sessions are automatically saved to browser localStorage
- **Export options**: 
  - CSV export for data analysis
  - JSON copy for programmatic use
  - Email export for sharing results
  - Summary copy for quick overview

## Usage

1. Click **Session Start** to begin recording
2. Add processing types/categories as needed
3. Click category buttons or press number keys (1-9) to log entries
4. Add optional notes/memos for each entry
5. Click **Session Finish** when done
6. Export your data using the available export options

## Deployment

This is a static HTML application that can be deployed to any static hosting service.

### Deploy to Vercel

1. Push this repository to GitHub
2. Import the repository in [Vercel](https://vercel.com)
3. Vercel will automatically detect it as a static site
4. Deploy!

Alternatively, use the Vercel CLI:

```bash
npm i -g vercel
vercel
```

### Deploy to Other Platforms

This single HTML file can be deployed to:
- **Netlify**: Drag and drop or connect GitHub repo
- **GitHub Pages**: Enable in repository settings
- **Any static hosting**: Upload `index.html` to any web server

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- Uses browser localStorage for data persistence
- Works offline (no server required)
- Responsive design

## License

Copyright © SeongYeup Kim. Open-access tool for educational and research purposes.

## Author

SeongYeup Kim

