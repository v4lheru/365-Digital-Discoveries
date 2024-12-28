# 365 Digital Discoveries

Discover a new fascinating website every day. Break out of your digital bubble and explore the vast, weird, and wonderful world of the internet.

## About The Project

This project was born from a simple realization: most of us visit the same few websites every day, missing out on the incredible diversity of the internet. The "365 Digital Discoveries" challenge aims to change that by automating the discovery of interesting, non-mainstream websites.

Using Obsidian (a note-taking app), OpenRouter API, and Perplexity AI, this script helps you discover and document unique websites daily while ensuring you never get the same suggestion twice.

### What It Discovers

The script focuses on finding websites in categories such as:
- Interactive art and experimental projects
- Fascinating databases and archives
- Unique communities and subcultures
- Digital museums and virtual exhibitions
- Interactive storytelling experiences
- Internet archaeology and digital history
- Experimental music and sound projects
- Citizen science and collaborative projects
- Personal websites and unique blogs
- Interactive maps and geographic discoveries

### What It Avoids
- Mainstream social media platforms
- Common news websites
- Standard entertainment platforms
- Regular shopping sites
- Corporate websites
- Basic informational sites

## Prerequisites

- [Obsidian](https://obsidian.md/) (Free)
- Dataview plugin for Obsidian
- OpenRouter API key
- Basic understanding of how to use Obsidian

## Installation

1. Install Obsidian from https://obsidian.md/
2. Open Obsidian and create a new vault (or use an existing one)
3. Enable Community Plugins in Obsidian settings
4. Install the Dataview plugin:
   - Go to Settings → Community plugins
   - Click "Browse" and search for "Dataview"
   - Install and enable the plugin
5. Get an OpenRouter API key from https://openrouter.ai/
6. Download the `website-discovery.md` file from this repository
7. Copy it to your Obsidian vault
8. Replace `YOUR_API_KEY` in the script with your actual OpenRouter API key

## Usage

1. Open the `website-discovery.md` file in Obsidian
2. Click the "🌐 Discover New Website" button
3. Wait a few seconds for the script to generate a new discovery
4. A new note will be created with today's date and the discovered website's name

Each note includes:
- Website name and URL
- Description of what the site is
- Why it's interesting/valuable
- Best use cases and scenarios

## File Structure

Each discovery is saved as a separate note with the following format:
```
YYYY-MM-DD - Website Discovery - [Website Name].md
```

The script automatically checks existing notes to avoid duplicate suggestions.

## Customization

### Modifying Focus Areas
You can customize what types of websites you want to discover by editing the `WEBSITE_TEMPLATE` constant in the script. Look for the `REQUIREMENTS` section and modify the Focus Areas and Exclude lists according to your interests.

### Changing the Note Format
The output format can be customized by modifying the `FORMAT RESPONSE AS` section in the `WEBSITE_TEMPLATE`.

## Contributing

Contributions are welcome! Here are ways you can contribute:
1. Improve the script
2. Add new focus areas
3. Enhance the documentation
4. Share interesting websites you've discovered

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

This project uses:
- [Obsidian](https://obsidian.md/)
- [OpenRouter API](https://openrouter.ai/)
- [Perplexity AI](https://www.perplexity.ai/)
- Dataview plugin for Obsidian

## Join the Challenge

If you're using this script as part of the 365 Digital Discoveries challenge:
1. Share your discoveries using #365DigitalDiscoveries
2. Connect with other participants
3. Share interesting websites you find
4. Document your journey of digital exploration

Let's make 2025 a year of digital discovery! 🌐

---

**Note**: This script is part of a personal challenge to discover a new website every day in 2025. Feel free to join in and customize it for your own digital exploration journey.
