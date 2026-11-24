# life-and-car-exhibition
An interactive Algebra 2 exhibition (Exponential Functions Project) about buying a first car, credit, budgeting, and modeling with data.

**index.html** is the 7-step project, built around one question: *will you be underwater on your first car?*

1. **Paycheck**: a 15-question habits quiz about teen spending, with no dollar amounts and no mention of the car until it is finished, sets living costs, then a real San Diego job and rental give take-home pay and a monthly budget. The report shows any number a student changes afterward
2. **Credit**: a simplified score simulator using FICO's five published category weights (the simulated tier sets the loan APR), 24% APR credit card checks, a doubling-time question, a payoff simulator, and research on a real card
3. **Car**: a real listing from 2016 or newer, plus an insurance quote, tanks of gas, CO₂ (EPA 8,887 g/gal), and maintenance
4. **Loan**: down payment, term, and tax and fees; the first two months of the payoff schedule worked by hand, which unlocks the rest of the schedule and the loan comparisons; a 3/5/7/10-year comparison; 20% down; and leasing, balloon and upside-down explainers. The payoff schedule is data set #1
5. **Value data**: asking prices for older model years of the same car. This is data set #2
6. **Model it**: exponential V(t) = a·bᵗ for value and quadratic D(t) = pt² + qt + c for the balance. Students guess with sliders, run both regressions in Desmos, enter the results, find V(3) by hand, and solve for the crossing before the site shows the underwater graph. The value model must match the regression on their own data; the loan model is judged by its biggest miss in dollars. Students whose plan is never underwater (or under 3 months) get a fourth part, "Break it": build a loan that is underwater for at least a year, model it, and solve for its crossing
7. **Fix it & defend it**: what-if changes, original vs. now, a five-year true cost, a decision, and a visitor question

The written questions from the original Google Doc are built into each step. **Project ▾ → My report** prints every answer and check for grading. **Exhibition board** is the poster. **How you're graded** is a 20-point rubric (`RUBRIC` in the code), also printed at the end of the report.

Three teacher checkpoints sit at the end of steps 2, 4 and 6 with a checklist, questions to ask out loud, and a box for initials. The report shows each sign-off and the numbers at that moment. Initials are not secure and nothing is locked behind them.

`classic.html` is the previous 14-step version. `car-lab.html` is the standalone loan and value calculator and Desmos data page.

Photos: Wikimedia Commons, CC BY-SA 4.0 (MercurySable99, Elise240SX, Vauxford).
