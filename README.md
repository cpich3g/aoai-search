# Azure OpenAI Search

A Perplexity-style search engine powered by Azure OpenAI Chat Completions with grounding through web sources. Get AI-powered answers to your questions with real-time web sources and citations.

Created by [@ammaar](https://x.com/ammaar)

![Kapture 2025-01-04 at 14 35 14](https://github.com/user-attachments/assets/2302898e-03ae-40a6-a16c-301d6b91c5af)


## Features

- 🔍 Real-time web search integration
- 🤖 Powered by Azure OpenAI Chat Completions
- 📚 Source citations and references for answers
- 💬 Follow-up questions in the same chat session
- 🎨 Clean, modern UI inspired by Perplexity
- ⚡ Fast response times

## Tech Stack

- Frontend: React + Vite + TypeScript + Tailwind CSS
- Backend: Express.js + TypeScript
- AI: Azure OpenAI Chat Completions API
- Search: Web search integration

## Setup

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn
- An Azure OpenAI API key

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ammaarreshi/Azure-OpenAI-Search.git
   cd Azure-OpenAI-Search
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory:

   ```
   AZURE_OPENAI_KEY=your_api_key_here
   AZURE_OPENAI_ENDPOINT=your_endpoint_here
   AZURE_OPENAI_DEPLOYMENT=your_deployment_id_here
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Environment Variables

- `AZURE_OPENAI_KEY`: Your Azure OpenAI API key
- `AZURE_OPENAI_ENDPOINT`: Your Azure OpenAI endpoint
- `AZURE_OPENAI_DEPLOYMENT`: Your Azure OpenAI deployment ID
- `NODE_ENV`: Set to "development" by default, use "production" for production builds

## Development

- `npm run dev`: Start the development server
- `npm run build`: Build for production
- `npm run start`: Run the production server
- `npm run check`: Run TypeScript type checking

## Security Notes

- Never commit your `.env` file or expose your API keys
- The `.gitignore` file is configured to exclude sensitive files
- If you fork this repository, make sure to use your own API keys

## License

MIT License - feel free to use this code for your own projects!

## Acknowledgments

- Inspired by [Perplexity](https://www.perplexity.ai/)
- Built with [Azure OpenAI API](https://azure.microsoft.com/en-us/services/cognitive-services/openai-service/)
- UI components from [shadcn/ui](https://ui.shadcn.com/)
