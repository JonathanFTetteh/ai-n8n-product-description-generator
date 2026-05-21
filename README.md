# n8n AI Product Descriptions

AI-powered n8n workflow for automated product description generation using OpenAI.

## Features

- Automated AI-generated product descriptions
- Customizable product inputs
- Marketing-focused copywriting
- Simple and lightweight n8n workflow
- OpenAI integration

## Workflow Overview

This workflow generates professional and sales-oriented product descriptions based on:

- Product name
- Target audience
- Product features

The workflow uses OpenAI inside n8n to create optimized product copy automatically.

## Tech Stack

- n8n
- OpenAI API
- GPT-4o-mini

## How It Works

1. Input product data
2. Send prompt to OpenAI
3. Generate product description
4. Output formatted AI text

## Import Workflow

1. Download the workflow JSON file
2. Open n8n
3. Click "Import from File"
4. Select the workflow JSON
5. Add your OpenAI credentials

## Example Input

```json
{
  "produkt": "Bluetooth Speaker",
  "zielgruppe": "Techno Fans",
  "besonderheit": "Strong bass and long battery life"
}
```

## Example Output

> Powerful Bluetooth speaker with deep bass and long-lasting battery life — perfect for music lovers who want immersive sound anywhere.

## License

MIT License
