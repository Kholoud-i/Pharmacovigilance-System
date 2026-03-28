# Pharmacovigilance-System

This is a python based quantitative risk management system to support pharmacovigilance operations.It continuously evaluates patient safety signals by estimating, scoring, and prioritizing potential adverse drug risks using statistical models. The pharmacovigilance quantitative risk management system supports:

**Early detection of safety risks**
  
  Quantitative prioritization of adverse events
  
  Data-driven regulatory decision support
  
  Scalable integration into healthcare pipelines


**The system applies**

  
  Bayesian updating: for dynamic risk estimation
  
  Poisson & Binomial models: for adverse event frequency
  
  Z-score: for anomaly detection
  
  Exponential weighting: for recency effects
  
  Composite risk functions:  combining severity, frequency, and uncertainty


**Evaluation & Interpretation**

  
  The system evaluates each drug-event pair using:

  
  Observed vs expected event frequency
  
  Statistical deviation from baseline
  
  Model confidence & uncertainty
  
  Temporal acceleration of risk
  
  *These components are merged into a final composite risk index that drives alert thresholds.

**Application**:
  
  Clinical safety analytics
  
  Early warning systems for drug safety
  
  Regulatory reporting 
  
  Real-time patient risk dashboards


**System architecture**  
  risk_system/
  
  │
  
  ├── data_loader
  
  ├── signal_detection
  
  ├── risk_models
  
  ├── risk_engine
  
  ├── evaluation

