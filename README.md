# {{APP_NAME}} — policy pages

Public landing, terms, and privacy policy for {{OPERATOR}}'s private QuickBooks Online integration. Published via GitHub Pages and referenced by the Intuit App Assessment.

## Files
- `index.md` — Launch URL target
- `terms.md` — Terms of Use
- `privacy.md` — Privacy Policy

## Before publishing
Replace these placeholders across all files:
- `{{APP_NAME}}` — e.g. `Aqua Ridge QBO Bridge`
- `{{OPERATOR}}` — legal name of the operating entity, e.g. `Aqua Ridge Senior Living LLC`
- `{{CONTACT_EMAIL}}` — public contact address

Quick way to do all three at once (from this directory):

```bash
sed -i 's/{{APP_NAME}}/Aqua Ridge QBO Bridge/g; s/{{OPERATOR}}/Aqua Ridge Senior Living LLC/g; s|{{CONTACT_EMAIL}}|matt@example.com|g' index.md terms.md privacy.md _config.yml README.md
```
