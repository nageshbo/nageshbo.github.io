# nageshbo.github.io

Personal portfolio site for **Nagesh B O** — Solutions Architect, integration engineer, and AI tooling builder.

**Live:** [nageshbo.github.io](https://nageshbo.github.io)

## Stack

- Plain HTML + inline CSS + vanilla JS
- No build step, no dependencies, no framework
- Hosted on GitHub Pages (auto-deploys from `main`)

## Structure

```
.
├── index.html        # Single-page portfolio (all sections)
├── photo.jpg         # Profile photo
└── BadgePhotos.jpg   # Certification badges
```

## Sections

| Section | What's in it |
|---------|-------------|
| About | Summary — connects systems, people, and outcomes |
| Experience | Timeline from Dell → Birlasoft → Deloitte → Amazon India → Amazon UK |
| Education | BE in Information Science, Anthropic MCP certifications |
| Skills | REST APIs, SOA, AWS, Oracle ERP, SQL, Node.js, CloudWatch |
| Projects | AI ticket triage agent, SA command center, throttling system, MCP server |
| Blog | Medium articles on prompt engineering, AI teams, LLM privacy |
| Contact | LinkedIn, GitHub, Medium — all @nageshbo |

## Local Development

```bash
# Clone
git clone https://github.com/nageshbo/nageshbo.github.io.git
cd nageshbo.github.io

# Serve locally (pick one)
python3 -m http.server 8000
# or
npx serve .

# Open
open http://localhost:8000
```

No install step. Edit `index.html`, push to `main`, GitHub Pages deploys automatically.

## Deployment

Push to `main` branch. GitHub Pages serves from root. DNS is handled by GitHub's default `*.github.io` domain.

## License

Personal portfolio — not licensed for reuse.
