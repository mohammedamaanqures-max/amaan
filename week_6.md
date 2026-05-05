# Evaluation & Deployment: Airline Passenger Satisfaction

**Feature Analysis, EDA, Model Evaluation & Recommendations**  
Name | Course | Date

---

## Agenda
- Business problem & objective  
- Best model & why it wins  
- Top feature insights  
- Summary statistics  
- Key visualizations  
- Business interpretations  
- Recommendations  
- Conclusion

---

## Business Problem
**Problem:**  
Airline customer satisfaction is declining due to service issues, competition, and loyalty loss.  
**Focus area:** Customer care & service quality.  

**Goal:**  
Identify key satisfaction drivers and predict satisfaction for new passengers.

---

## Best Model (Scenario 7)
**XGBoost + SMOTE + LASSO**  

**Performance:**  
- **AUC:** 0.995  
- **G‑Mean:** 0.963  
- **Accuracy:** 0.965  
- **Sensitivity:** 0.947  
- **Specificity:** 0.978  

**Meaning:** Excellent class separation + balanced performance.

---

## Why This Model?
- **SMOTE** fixes class imbalance  
- **LASSO** removes noise → keeps only key drivers  
- **XGBoost** learns from errors → strong predictive power  
- Metrics show **high separation + reliability**

---

## Top Features (Positive Impact)
**Key satisfaction boosters:**  
- Online boarding  
- Inflight Wi‑Fi  
- Check‑in service  
- On‑board service  
- Leg room  
- Cleanliness  
- Baggage handling  
- Inflight entertainment  

**Insight:** Strong service + digital journey = higher satisfaction.

---

## Top Features (Negative Impact)
**Drivers of dissatisfaction:**  
- Personal travel  
- Disloyal customers  
- Economy / Eco Plus class  
- Arrival delays  
- Inconvenient departure/arrival time  
- Online booking friction  

**Insight:** These groups need targeted improvement.

---

## LASSO Coefficient Visualization
**Explain the chart:**  
- Positive bars = higher satisfaction  
- Negative bars = lower satisfaction  
- **Strongest positives:** online boarding, inflight Wi‑Fi  
- **Strongest negatives:** personal travel, disloyal customers  

*(Insert your coefficient plot here)*

---

## Summary Statistics
**Key pattern:**  
Satisfied passengers give higher ratings across all service features.  
Dissatisfied passengers are more likely to be:  
- Personal travel  
- Disloyal  
- Economy class  

*(Insert table snapshot)*

---

## Bivariate Visualizations
**Boxplots & satisfaction rate charts show:**  
- Satisfied group scores higher on all service ratings  
- Delay is a negative driver but weaker than service quality  
- Class & loyalty have large satisfaction gaps  

*(Insert top 5 boxplots + binary satisfaction bars)*

---

## 9 Business Recommendations
1. Improve **online boarding UX**  
2. Upgrade **Wi‑Fi reliability**  
3. Strengthen **check‑in & onboard service training**  
4. Reduce **arrival delays**  
5. Fix **online booking friction**  
6. Improve **schedule convenience**  
7. Target **personal travel segment**  
8. Convert **disloyal customers**  
9. Boost **economy value perception**

---

## Conclusion
- Best model achieved **near‑perfect performance**  
- LASSO revealed **clear satisfaction drivers**  
- Service quality + digital experience are top levers  
- Targeting negative segments yields biggest impact  

**Final takeaway:**  
Improving service + digital journey + economy experience will most improve satisfaction.

---

## Design (Attractive Theme)
- **Primary:** Deep Blue (#1F3C88)  
- **Accent:** Teal (#00B3B8)  
- **Highlight:** Orange (#FF8A00)  
- **Background:** Light Gray (#F7F9FB)  
- **Font:** Poppins / Calibri

---

## Convert to PPTX (Optional)
If you want to convert this Markdown to PowerPoint:
1. Install Marp CLI: `npm install -g @marp-team/marp-cli`
2. Run: `marp week_6.md --pptx`
