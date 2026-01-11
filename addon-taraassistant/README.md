# Tara Assistant Add-on

Run Tara Assistant as a Home Assistant Add-on.

## Installation

Add this repository to Home Assistant:
1. Go to Settings → Add-ons → Repositories
2. Add the repository URL
3. Find "Tara Assistant" and click Install

## Configuration

The add-on will automatically:
- Pull the latest image from `ghcr.io/tarahome/taraassistant:latest`
- Expose the application on port 8000
- Persist data in `/data`
- Automatically restart unless stopped

## Access

Access Tara Assistant at: `http://[your-home-assistant-ip]:8000`

## Support

For issues, visit the repository: https://github.com/tarahome/taraassistant
