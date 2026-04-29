# SUPPLY_CHAIN_PROJECT
Supply Chain Delivery Performance Project




📦 Supply Chain Delivery Analysis — Project Summary

This project analyzes 172,765 e-commerce delivery orders (2015–2018) to uncover the root causes of chronic late deliveries and their impact on profitability. The study includes KPI assessment, profitability analysis, bottleneck detection, machine-learning prediction modeling, and strategic improvement recommendations.

🔍 Key Insights
54.71% of orders are delivered late, making delays the default customer experience.
$2.1M profit is at risk due to delayed shipments.
Total profit generated: $7.5M.
1–4 day delays account for 54.7% of all orders — indicating a systemic issue.
Shipping Mode is the biggest failure point:
First Class → 100% late
Second Class → 79.8% late
Standard Class performs best → 39.8% late
📈 Bottlenecks Identified
System-wide delivery issues across all regions (55–59% delay rate).
Payment review statuses cause high delays (up to 80% in some regions).
Seasonal spikes (Aug, Sep, Dec) push delays above 55%.
Certain departments (Outdoor, Golf, Health & Beauty) show higher delay rates.
🤖 Machine Learning Model

A Random Forest classifier was built to predict late deliveries:

74% accuracy
78% precision for late orders
SMOTE used to handle class imbalance
Usable as a real-time “at-risk order alert” system
📝 Strategic Recommendations
Audit and fix First & Second Class shipping modes immediately
Deploy predictive alert model in the order management system
Automate payment review escalations
Create seasonal surge capacity plans
Default to Standard Class when possible
Investigate high-delay product departments
Reduce loss-making orders (currently 18.7%)
Quarterly retraining of the ML model
✅ Final Conclusion

The project clearly shows that most delivery failures come from shipping mode misconfiguration, payment processing delays, and unmanaged seasonal spikes. With focused operational fixes and predictive modeling, the company can significantly lower its 54.71% delay rate, protect profits, and improve customer trust.
