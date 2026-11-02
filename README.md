# Problem-Set-3

The most credible estimate of the programme's impact is the regression-adjusted estimate controlling for account size but excluding support tickets. Our simulation established that the programme's true effect is $25 per customer, and controlling for account size allows us to recover an estimate close to that value.

The initial comparison between West and other customers overstated programme impact because larger accounts were more likely to receive the programme and independently generated higher revenue. Controlling for account size addressed this confounding. However, adding support tickets made the estimate worse because ticket volume is influenced by both programme participation and revenue. Conditioning on tickets introduced a misleading relationship rather than removing bias.

Our simulation suggests the programme does work, increasing revenue by approximately $25 per customer. However, this conclusion comes from a controlled simulation with a known effect; in a real business setting, observational estimates alone would not establish causality.

Before any number goes on a slide, I recommend that the team:

Define the unit of analysis and verify that joins preserve what is intended

Check for missing data and understand who gets excluded, if any

Identify confounders using business logic, DAG, industry knowledge, and temporal ordering, not simply correlations

Avoid controlling for variables potentially caused by the programme or outcome

Compare unadjusted and adjusted estimates, document assumptions, and validate results against a randomized experiment whenever feasible

Overall, these safeguards will help ensure that our reported impact reflects actual programme performance.

