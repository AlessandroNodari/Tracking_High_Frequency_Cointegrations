# Tracking_High_Frequency_Cointegrations

We looked into cointegrations among US stocks on a minute level. In this timeframe the price data are generally really noisy, hence also the cointegration coefficients. Moreover, cointegrations can vanish and reappear. This makes trading those really risky, so we developed a tool for risk-management and entry/exit purposes. Our tool relies on a Rao-Blackwellized Particle Filter with births&deaths.
