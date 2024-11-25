# Geopolitical Market Analysis System

Real-time analysis of geopolitical events and their market impact using LLMs and financial data.

## Features

- Event collection from global news sources
- Market data integration (prices, volatility, sector performance)
- AI-powered impact analysis using Claude API
- Risk scoring and sector-specific recommendations
- Real-time market regime detection

## Requirements

```bash
pip install pandas numpy yfinance anthropic newsapi-python scipy scikit-learn ta
```

## API Keys Required

- Anthropic API key for Claude
- NewsAPI key for event collection

## Core Components

1. **EventCollector**: Gathers and categorizes geopolitical events
2. **MarketDataCollector**: Real-time market metrics and sector analysis
3. **GeopoliticalAnalyzer**: AI-powered event impact analysis
4. **Market Impact Assessment**: Sector-specific recommendations

## Usage

```python
# Run analysis pipeline
if __name__ == "__main__":
    await execute_analysis()
```

## Output Format

- Event details
- Regional impact
- Sector-specific analysis
- Trading recommendations
- Risk metrics

## Data Models

- GeopoliticalEvent
- MarketMetrics
- MarketImpact

## Contributing

Pull requests welcome. Please run tests before submitting.

## License

MIT


Need any specific section expanded?