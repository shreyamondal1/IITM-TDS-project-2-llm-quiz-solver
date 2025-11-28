# LLM Quiz Solver

An automated quiz-solving system that uses AI models to understand, analyze, and solve data-related quizzes.

## Features

- **Automated Quiz Solving**: Handles chained quizzes with automatic navigation
- **JavaScript Rendering**: Uses Playwright to render dynamic web pages
- **Data Processing**: Can fetch PDFs, APIs, and other external data sources
- **Multi-Model LLM Integration**: Uses AIpipe OpenRouter with automatic fallback across multiple models
- **Time Management**: Respects the 3-minute time limit per quiz chain

## Testing

Test your endpoint with:

```bash
curl -X POST https://your-space.hf.space/solve \
  -H "Content-Type: application/json" \
  -d '{
    "email": "your-email@example.com",
    "secret": "your-secret-key",
    "url": "https://tds-llm-analysis.s-anand.net/demo"
  }'
```

## License

MIT License
