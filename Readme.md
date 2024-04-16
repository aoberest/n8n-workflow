# This is a repository for examples N8N - workflow automation using IFTTT

## Quick start
You can run N8N in Docker

```bash
docker run -it --rm --name n8n -p 5678:5678 -v n8n:/home/node/.n8n n8nio/n8n
```

and then open URL http://localhost:5678/ in your browser to import json from a URL or file.

### Import From URL
Open the UI N8N and press the "Add New Workflow" button. Then, open "Import From URL" in the top right corner of the UI.
Paste URL https://raw.githubusercontent.com/aoberest/n8n-workflow/main/n8n-compare-datasets.json
