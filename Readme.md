# WhatsApp Chat Analysis Dashboard

## Overview
A Python-based dashboard that analyzes WhatsApp chat exports to provide insights into messaging patterns, activity trends, and conversation statistics.

## Project Description
An interactive analytics tool that processes exported WhatsApp chat data to reveal meaningful patterns and insights through visualizations and statistics. The dashboard analyzes message frequency, user activity, emoji usage, and temporal trends to help users understand their communication habits.

## Features
- Message frequency analysis
- User activity statistics
- Timeline visualization
- Most active hours/days
- Emoji usage analytics
- Word cloud generation
- Media sharing statistics
- Response time analysis

## Technology Stack
- Python 3.x
- Pandas (Data processing)
- Matplotlib/Plotly (Visualizations)
- Streamlit (Dashboard UI)
- NLTK (Text analysis)
- Regex (Message parsing)

## Installation

```bash
git clone https://github.com/Ropriya/WhatsApp-chat-analysis-dashboard-using-python.git
cd WhatsApp-chat-analysis-dashboard-using-python
pip install -r requirements.txt
streamlit run app.py
```

## Usage

### Export WhatsApp Chat
1. Open WhatsApp chat
2. Tap three dots → More → Export chat
3. Choose "Without Media"
4. Save the .txt file

### Analyze Chat
1. Run the dashboard
2. Upload exported chat file
3. View interactive analytics
4. Explore different metrics and visualizations

## Dashboard Features

### Statistics
- Total messages count
- Total words count
- Media files shared
- Links shared
- Most active user
- Average message length

### Visualizations
- **Timeline**: Messages over time
- **Activity Map**: Busiest hours and days
- **User Comparison**: Message distribution per user
- **Word Cloud**: Most frequently used words
- **Emoji Analysis**: Top emojis used
- **Monthly/Weekly Trends**: Activity patterns

## Analysis Insights
- Identify most active participants
- Discover peak conversation times
- Track messaging trends over time
- Analyze communication patterns
- Find commonly used words and emojis

## File Structure
```
WhatsApp-chat-analysis-dashboard-using-python/
├── app.py
├── requirements.txt
├── parser.py              # Chat file parser
├── analyzer.py            # Data analysis functions
├── visualizer.py          # Plotting functions
└── README.md
```

## Example Output
```
📊 Chat Statistics:
- Total Messages: 15,234
- Total Words: 89,456
- Most Active User: John (8,234 messages)
- Most Active Day: Saturday
- Peak Hour: 9 PM - 10 PM
```

## Privacy & Security
- All analysis is performed locally
- No data is uploaded to external servers
- Chat files remain on your device
- Secure and private analysis

## Future Enhancements
- Sentiment analysis
- Language detection
- Group vs individual chat comparison
- Export analysis reports (PDF)
- Advanced NLP insights

## Author
**Rohit Ranjan**
- GitHub: [github.com/Ropriya](https://github.com/Ropriya)
- LinkedIn: [linkedin.com/in/contact-rohit-ranjan](https://linkedin.com/in/contact-rohit-ranjan)

---

*Discover insights from your WhatsApp conversations!* 💬📊