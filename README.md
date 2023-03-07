## Analyzing Fed Meeting Impact on Stock Market with OpenAI Whisper

The project aims to analyze the impact of Federal Reserve meeting speech on the stock market.

### Tools and Libraries
The project was implemented on Google Colab and utilizes various Python libraries including:

**1. Pytube:** A Python library for downloading YouTube videos which was used to extract the audio of the Federal Reserve meeting speeches.

**2. OpenAI Whisper:** A natural language processing tool that accurately transcribes the speeches.

**3. mplfinance:** A Python library for financial data visualization that was used to plot a candlestick chart of the stock market.

### Methodology
The project methodology involved several steps:

**1. Audio extraction:** Pytube was used to download the audio of the Federal Reserve meeting speeche from YouTube.

**2. Speech transcription:** OpenAI Whisper was used to accurately transcribe the speeches.

**3. Correlation analysis:** The speech transcripts were matched with the SPY data (in the form of a CSV) during the same time, and the correlation between the speech and the stock market was identified and analyzed.

**4. Data visualization:** The biggest down moves in the stock market were identified and charted using mplfinance, providing better visualization and understanding of the market trends. The speech causing the big down moves was identified.
