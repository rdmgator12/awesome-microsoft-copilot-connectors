# Contributing

This list tracks every connector in the official [Microsoft 365 Copilot connectors gallery](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/connectors-gallery) (both Microsoft-built and partner-built). Contributions welcome.

> This is an independent, community-maintained project. Not affiliated with, endorsed by, or sponsored by Microsoft Corporation.

## What You Can Contribute

### New Connectors
When Microsoft or a partner adds a new connector to the official gallery, submit a PR adding it to the appropriate category with a publisher and description.

### Improved Descriptions
If a description is missing detail, marketing-fluffy, or could be clearer, submit a PR with a better one.

### Category Corrections
If a connector is in the wrong category, submit a PR moving it.

### Tier Marker Updates
If Microsoft has newly certified a connector for Microsoft 365 Copilot, add the `**★ Certified**` marker. If a connector exits preview, remove the `(preview)` tag.

### Field Reports
Tested a connector in production and have real-world notes? Add a brief field report below the connector entry:

```markdown
- [Connector Name](https://example.com) - *Publisher*. Description.
  > **Field report:** One paragraph on what worked, what didn't, what surprised you. Be specific.
```

## Guidelines

- One PR per change unless closely related.
- Keep descriptions concise — one sentence drawn from Microsoft's gallery description, trimmed of marketing copy.
- Don't add connectors that aren't in the official Microsoft 365 Copilot connectors gallery. This list tracks that one directory, not Power Platform connectors, Copilot Studio agents, or AppSource Copilot apps (those are different surfaces and warrant separate lists).
- Use ASCII hyphen (`-`) as the separator between link and description. Not en-dash or em-dash — `awesome-lint` enforces this.
- Maintain alphabetical order within categories.
- Multiple partners may list connectors for the same underlying service (e.g., Confluence has entries from BA Insight, RheinInsights, ServiceNow, and Accenture). List them all — that matches Microsoft's canonical directory and respects partner attribution.

## Tier Markers

- **`M`** = Built and maintained by Microsoft.
- **`★ Certified`** = Certified for Microsoft 365 Copilot — Microsoft's enterprise-ready validation for partner connectors.
- `(preview)` = Currently in preview per Microsoft's gallery.

## Weekly Updates

This list is updated weekly to stay in sync with the Microsoft Learn galleries. If you notice the official gallery has added connectors that aren't listed here, please open an issue or PR.
