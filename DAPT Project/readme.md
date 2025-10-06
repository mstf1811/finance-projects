# Real-Time Intrinsic Valuation Model for the Tunisian Dinar (TND)
Developed for FIN460 — Dynamic Asset Pricing Theory at Tunis Business School.  
This project builds a **real-time hybrid stochastic model** to estimate the intrinsic value of the Tunisian Dinar (USD/TND) by combining economic theory with state-space modeling and machine learning.

## Highlights
- Modeled **USD/TND log returns** as a stochastic basket of major FX pairs (EUR/USD, GBP/USD, USD/JPY).  
- Implemented **Kalman Filter** and **Double Kalman Filter** frameworks to estimate time-varying basket weights and a latent liquidity-spread state.  
- Integrated a **Neural Network residual corrector** to capture nonlinear deviations and improve interbank-rate nowcasting.  
- Achieved **MAPE 0.145 %**, **RMSE 0.0063**, and **ρ = 0.9919** correlation with actual interbank data — outperforming regression and baseline ML benchmarks.  
- Framework demonstrates how **global FX fundamentals** and **local liquidity frictions** interact in real-time valuation.

📄 [Open report](./DAPT%20Project%20Group%209.pdf)
