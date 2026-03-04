# Mark Wamutitu - Cybersecurity Portfolio

A modern, interactive cybersecurity analyst portfolio built with HTML, CSS, and JavaScript.

## Features

- **Profile Picture**: Circular profile photo with cyber-themed glowing border
- **Interactive Terminal**: A functional command-line interface with various security-related commands
- **Animated Backgrounds**: Cyberpunk-themed visual effects including particles, binary rain, and glowing orbs
- **Responsive Design**: Fully responsive layout that works on all devices
- **Project Showcase**: Display of security projects with tags and descriptions
- **CTF Writeups**: Capture The Flag challenge writeups with code examples
- **Contact Form**: Functional contact form (simulated)

## Projects

The portfolio showcases these featured security projects:

1. **Enterprise SIEM Deployment** - Wazuh SIEM configuration and deployment
2. **Secure CRM Deployment** - Hardened SuiteCRM with access controls
3. **Network Traffic Analyzer** - Python-based network analysis tool

Additional projects available at: [Google Drive Folder](https://drive.google.com/drive/folders/14It1RPetcJcHqKeJv6fqcReIo2eaI5dJ?usp=sharing)

## Skills

- SIEM (Wazuh, Splunk)
- Programming (Python, Bash, Regex, PowerShell)
- Operating Systems (Linux, Windows Server, Kali Linux)
- Network Security & Analysis
- Incident Response
- Vulnerability Assessment

## Deployment

This is a static HTML website that can be deployed to any static hosting service:

### Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

### Deployment Options

- **GitHub Pages**: Push to a GitHub repository and enable GitHub Pages
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your GitHub repository or drag and drop
- **Firebase Hosting**: Deploy using Firebase CLI

## File Structure

```
.
├── index.html          # Main portfolio website
├── profile.png        # Profile picture (optional)
└── README.md          # This file
```

## Customization

### Add Profile Picture

Place your profile photo named `profile.png` in the same directory as `index.html`. The image will automatically appear as a circular photo with a glowing cyan border in the hero section.

### Update Personal Information

Edit the following sections in `index.html`:

- **Name**: Search for "Mark Wamutitu" and replace
- **Email**: Search for "markwamutitu610@gmail.com" and replace
- **Social Links**: Update GitHub, LinkedIn URLs in the footer
- **Projects**: Add/remove project cards in the Projects section
- **Skills**: Modify skill bars in the Skills section

### Add More Projects

1. Copy a project card section
2. Update the title, description, and tags
3. Add the new card before the "More Projects" link

## Terminal Commands

The interactive terminal supports these commands:
- `help` - Show available commands
- `about` - Display information about Mark
- `skills` - List technical skills
- `projects` - Show featured projects
- `contact` - Display contact information
- `ctf` - Show CTF achievements
- `whoami` - Display current user
- `clear` - Clear terminal screen
- `hack` - Easter egg command

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## License

MIT License - Feel free to use this portfolio template for your own website.

## Contact

- Email: markwamutitu610@gmail.com
- GitHub: github.com/WAMUTITU610
- LinkedIn: linkedin.com/in/markwamutitu

