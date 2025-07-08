
# 2. The Analytical Approach

This document explains the methodology behind the Strategic Sales Scenario Simulator. The tool's design is based on a powerful yet simple "Baseline vs. Scenario" framework, which allows for a direct and intuitive comparison between a business-as-usual projection and a user-defined hypothetical future.

## The Framework: Baseline vs. Scenario

*   **The Baseline ("Actual Sales"):** The green-colored metrics on the dashboard represent the baseline performance for the selected time period. This is the factual, historical data that serves as the starting point for any analysis. The KPI card `Sales Metrics (vs last year)` provides context on how this baseline period performed against the prior year.

*   **The Scenario ("Sales Scenarios"):** The blue-colored metrics are the output of the simulation. This is a dynamic calculation that takes the baseline `Total Sales` and adjusts it based on the user's inputs in the control panel. This represents the projected outcome if the hypothetical changes were to be implemented.

## The Simulation Controls

A user can build a near-infinite number of scenarios by adjusting two simple but powerful levers on the left-hand panel:

1.  **Pricing Change:** This slider applies a universal percentage change to the `Unit Price` of every single transaction in the baseline data. It models the top-down impact of an across-the-board price adjustment.
2.  **Demand Change:** This slider applies a universal percentage change to the `Order Quantity` of every transaction. It models the expected market response to either the price change (elasticity) or external market forces (e.g., economic growth or recession).

## Answering Key Business Questions

The visuals on the dashboard are arranged to answer a logical progression of strategic questions:

1.  **What is the overall financial result?** (Answered by the `Scenario Metrics` KPI card)
2.  **How does this result accumulate over the year?** (Answered by the `Performance vs Scenario` cumulative chart)
3.  **Is the impact consistent each month?** (Answered by the `Monthly Performance vs Scenario` bar chart)
4.  **Which stores and customers are the biggest drivers of the change?** (Answered by the `Store Performance` and `Customer Performance` tables)

This guided analytical path allows a leader to quickly move from a high-level idea to a detailed understanding of its potential real-world impact.

