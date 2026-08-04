# Customer Churn Analytics Dashboard

An interactive Tableau dashboard built to help telecom executives explore customer churn, spot the groups most at risk, and support data driven retention decisions.

## Overview

Telecom providers lose customers to competitors constantly, and acquiring a new customer costs far more than keeping an existing one. This project analyzes customer level churn data and packages the findings into a dashboard that nontechnical business leaders can use on their own, without needing a data analyst in the room.

## What the dashboard includes

* Two key performance indicators showing total customers and overall churn rate at a glance
* A churn rate by state map to surface geographic patterns
* A churn by contract type chart to compare month to month, one year, and two year customers
* A churn rate by age group chart
* A churn rate versus customer contacts chart, showing whether repeated support contact is tied to churn
* Two interactive filters, one for contract type and one for customer area, so a viewer can narrow the view to any segment
* A color palette chosen to remain readable for users with colorblindness

## How to open it

1. Download `dashboard/customer_churn_dashboard.twbx`
2. Open it with Tableau Desktop or the free Tableau Reader
3. Use the Contract filter on the right to isolate a contract type
4. Use the Area filter on the left to isolate a customer region
5. Both filters update every chart and KPI at once, so you can compare segments quickly

More detail on navigating the dashboard is in `docs/user_guide.md`.

## Why this design

The dashboard follows a problem to insight to action structure. The KPIs establish the scale of the churn problem, the charts explain where and why it is happening, and the filters let a leader test their own hypotheses about which customers to prioritize for retention efforts. Color and placement are used deliberately to draw the eye to the highest value findings first.

The full design reasoning, including how the approach would change for a technical audience versus a business audience, is written up in `docs/design_notes.md`.

## Tools used

Tableau, for data modeling and interactive visualization design.

## Author

Mitzi Evans
