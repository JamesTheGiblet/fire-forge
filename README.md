🔥 FireForge - Financial Independence Calculator

FireForge is an interactive simulation engine for the FIRE (Financial Independence, Retire Early) movement. It visualizes how "Micro-Habits"—small monthly savings or income boosts—compound over time to accelerate your retirement date.

Unlike static calculators, FireForge uses a "Stack" system, allowing users to dynamically add or remove lifestyle choices to see their immediate impact on long-term wealth.
✨ Key Features

    Compound Growth Engine: Real-time projection of portfolio value over 30 years using monthly compounding.

    Lifestyle Stacking: Gamified interface to add "Events" (e.g., Side Hustle +$500, Car Payment -$400). The tool calculates the net monthly cash flow and projects the long-term impact.

    Risk Modeling: Toggle between Conservative, Balanced, and Aggressive investment strategies to see how market returns affect your timeline.

    FI Metrics: Automatically calculates your "Retirement Readiness" and "Time to FI" based on the Rule of 25.

    Dynamic Visualization: Uses Plotly.js for responsive, interactive charting.

🚀 Quick Start

    Download the index.html file.

    Open it in any modern web browser.

    Configure:

        Set your Initial Savings.

        Choose your Risk Profile (Expected Returns).

        Add Items from the "Lifestyle" tab to build your monthly contribution stack.

🧮 The Math Behind the Tool

FireForge relies on the standard Future Value of an Annuity formula combined with the 4% Rule.
1. Compounding

The portfolio value grows monthly based on:
Pt​=Pt−1​⋅(1+12r​)+C

    P: Portfolio Value

    r: Annual Interest Rate (adjusted by risk profile)

    C: Net Monthly Contribution (from your Lifestyle Stack)

2. The Target (FI Number)

The tool calculates the "Finish Line" using the standard Fire Movement benchmark:
Target=AnnualExpenses×25

    Note: The current baseline assumes annual expenses of $40,000 (LeanFIRE benchmark), resulting in a target portfolio of $1,000,000.

⚙️ Customization

You can define your own "Lifestyle Presets" in the config object within the source code to match your specific audience (e.g., Students, Tech Workers, Parents).
JavaScript
