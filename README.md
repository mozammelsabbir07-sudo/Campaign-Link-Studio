# Campaign Link Studio

A free, privacy-friendly browser tool for creating consistent UTM campaign tracking links.

## Why this project exists

Campaign links are often created manually, which can lead to inconsistent naming and messy analytics reports. Campaign Link Studio gives marketers and small teams a lightweight way to add UTM parameters to destination URLs.

## Features

- Creates links with `utm_source`, `utm_medium`, and `utm_campaign`
- Supports optional `utm_term` and `utm_content`
- Preserves existing destination URL parameters and fragments
- Copies generated links and exports a small CSV
- Runs entirely in the browser; no account, server, analytics, or cookies
- Responsive layout and basic keyboard-accessible controls

## Run locally

No build tools or dependencies are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Enter a destination URL and campaign details, then select **Generate link**.

For clipboard access, some browsers require the page to be served over HTTPS or localhost.

## Example

Destination URL: `https://example.com/sale`

- Source: `instagram`
- Medium: `social`
- Campaign: `autumn_launch_2026`

Generated URL:

`https://example.com/sale?utm_source=instagram&utm_medium=social&utm_campaign=autumn_launch_2026`

## Privacy

The tool processes values locally in your browser. It does not transmit campaign URLs to a server. Do not use UTM parameters to place personal or sensitive information in URLs.

## Roadmap

- [ ] Optional campaign naming presets
- [ ] Bulk URL generation from CSV
- [ ] Unit tests for URL construction and parameter preservation
- [ ] More guidance on consistent UTM naming

Roadmap items are proposals, not features already implemented.

## Contributing

Bug reports, accessibility improvements, documentation updates, and small feature proposals are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT. See [LICENSE](LICENSE).
