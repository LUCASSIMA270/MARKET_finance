# MARKET_finance

📈 MARKET_finance: Algorithmic Trading & Portfolio Analysis
Quantitative Insights into Asset Dynamics and Technical Indicators

This repository contains the analytical framework and algorithmic implementation for market finance analysis, developed for the L3 Economics & Finance program. The project focuses on technical analysis, risk-profile-based decision modeling, and backtesting trading strategies on major international assets.
🧐 The Big Question

How can quantitative indicators like Simple Moving Averages (SMA), RSI, and Bollinger Bands be leveraged to outperform simple market benchmarks? This project explores the effectiveness of rule-based trading when applied to diverse risk profiles—from risk-averse institutions to aggressive risk-takers.
🛠️ The Quantitative Toolkit

    The Language: Python (implemented via Jupyter Notebooks).

    Data Science Stack:

        Pandas & NumPy for financial time-series wrangling.

        Matplotlib for high-fidelity technical charting and cumulative return visualization.

    Financial Indicators:

        Moving Averages (SMA 20 & SMA 200/40).

        Volatility & Momentum: Bollinger Bands, RSI, and Stochastic oscillators.

        Advanced Theory: Elliot Waves and Support/Resistance mapping.

📂 Repository Map

    LUCAS_SIMATOVIC_MARIE_PIERRE_PEPE.ipynb: The primary algorithmic engine. It automates buy/sell signals based on SMA crossovers and calculates cumulative performance.

    DATA/: Historical .csv datasets for major Japanese and global equities:

        TAK.csv (Takeda Pharmaceutical).

        TM.BA.csv (Toyota Motor Corp).

        SONY.csv (Sony Group).

        AJI.MU.csv (Ajinomoto Co.).

    Assignment_Docs/: Theoretical guidelines including the TD Mini-portefeuille and TD 3 frameworks for risk-based decision rules.

📈 Key Features & Methodology

    SMA Crossover Strategy: A trend-following algorithm that generates buy signals when the short-term SMA (20) crosses above the long-term SMA (200).

    Multi-Asset Comparison: Easily switch between different tickers (Takeda, Sony, Toyota) to compare how trend-following performs across different sectors (Cyclic vs. Counter-cyclic).

    Risk Profile Modeling: Theoretical implementation of trading rules tailored for:

        Risk-Averse: Prioritizing capital preservation and low-volatility entries.

        Risk-Neutral: Standard utility maximization.

        Risk-Seekers: Exploiting high-momentum and high-volatility shocks.

    Performance Visualization: Automated generation of price charts overlaid with indicators and equity curves showing total returns over time.

🚀 How to Run

    Clone the repo.

    Upload the data: Ensure the .csv files are in the same directory as the notebook.

    Run the script: Open LUCAS_SIMATOVIC_MARIE_PIERRE_PEPE.ipynb in Jupyter or Google Colab.

    Execute the cells: The code will automatically process the Takeda (TAK) asset by default, generating the trading signals and performance graphs.

👥 Authors

    Lucas SIMATOVIC

    Marie-Pierre PEPE
