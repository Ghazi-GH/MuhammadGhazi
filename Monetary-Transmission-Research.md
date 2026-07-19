# Econometric Research: Asset Price Monetary Transmission Mechanism (US vs. Pakistan)

## 🎯 The Problem
How do central bank policy choices transmit into real economic activity via asset valuations during aggressive global monetary tightening cycles. While qualitative differences between developed and emerging financial systems are widely recognized, there is a distinct shortage of quantitative comparative research that models the **wealth effect** and **Tobin's q** mechanisms under a single, unified econometric engine. This study captures the post-2022 global tightening cycle to map out these distinct channels side-by-side.

## 🛠️ The Technical Action
* Developed two distinct **5-variable Vector Error Correction Models (VECM)** utilizing high-frequency monthly macroeconomic time-series data spanning from July 2015 to January 2025.
* Extracted and structured variables from the **State Bank of Pakistan (SBP) E-Data Portal**, **Pakistan Bureau of Statistics (PBS)**, **Federal Reserve Economic Data (FRED)**, and **Yahoo Finance**.
* Executed rigorous time-series pre-estimation testing: verified uniform order of integration ($I(1)$) using **Augmented Dickey-Fuller (ADF)** and **Phillips-Perron (PP)** tests and evaluated lag configurations via **AIC/SC criteria**.
* Established long-run economic cointegration ranks ($r=1$) through the **Johansen Cointegration framework**.
* Mapped short-run structural innovations and volatility distributions by deriving **Impulse Response Functions (IRFs)** and **Forecast Error Variance Decompositions (FEVD)** over a 10-month horizon.

### 📊 Applied Variables Framework:
| Metric | Pakistan Model Lineup | United States Model Lineup |
| :--- | :--- | :--- |
| **Policy Instrument** | 6-Month KIBOR | Federal Funds Rate (FFR) |
| **Equity Valuation** | PSX Index | Dow Jones Industrial Average |
| **Real Estate Proxy** | House Rent Index (HRI 2005) | House Rent Index (HRI 2000) |
| **Macro Output Indicator**| Large Scale Manufacturing Index (LSMI) | Industrial Production Index (IPI) |
| **Price Stability Metric**| Consumer Price Index (CPI) | Inflation Rate |

## 🚀 The Result
The VECM estimation and innovation analysis exposed deep structural contrasts between the two economic frameworks:

1. **The Efficiency Gap:** The US equity market (Dow Jones) reacts with near-perfect information efficiency, collapsing immediately following an FFR shock. Conversely, the Pakistan Stock Exchange (PSX) exhibits a gradual, heavily lagged downward adjustment.
2. **Housing Market Stickiness:** The US House Rent Index reacts smoothly and predictably.In contrast, Pakistan's real estate channel is highly friction-bound and "sticky," reflecting a slow Error Correction speed of adjustment (**ECT = -0.040**) of just **4% per month** due to a lack of formal mortgage deep-linking.
3. **The Emerging Market "Price Puzzle":** Following a tightening shock, the US model shows a classic downward inflation path. Pakistan's model, however, uncovers a prominent **Price Puzzle** where a KIBOR surge drives consumer prices *upward* as local businesses pass their escalated cost of capital directly onto consumers.

### 📸 Impulse Response Function (IRF) Diagnostics
#### Quantitative Policy Transmission: United States
<img width="656" height="415" alt="image" src="https://github.com/user-attachments/assets/1cf4f95b-a79f-4b5e-b08f-b875c7f2f589" />


#### Quantitative Policy Transmission: Pakistan
<img width="648" height="481" alt="image" src="https://github.com/user-attachments/assets/5b0ad808-c5c4-4c35-9c2c-a8f4bb561708" />

---
### 🔗 Research Documentation & Artifacts
* 📄 **[Access Full Research Paper PDF](./Research-Project-MTP.pdf)** 
