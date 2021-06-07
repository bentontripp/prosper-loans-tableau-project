## Tableau Story - Prosper Loans
#### A Brief Visual Overview of Prosper Loan Borrower Rates

*By Benton Tripp*

### Introduction

This project provides an overview of Prosper loan interest rates using visualizations in Tableau.<br>

On Prosper's website, the company is described as the following: <br>

"*Prosper was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than 18 billion dollars in loans to more than 1,100,000 people.* <br>

*Through Prosper, people can invest in each other in a way that is financially and socially rewarding. Borrowers apply online for a fixed-rate, fixed-term loan between 2,000 & 40,000 dollars. Individuals and institutions can invest in the loans and earn attractive returns. Prosper handles all loan servicing on behalf of the matched borrowers and investors.*"<br>

(*see* https://www.prosper.com/about *for more information about Prosper*)

### Summary and Project Overview

The project investigates the Prosper interest Rates, as well as the relationships between rates and: <br>
 - Year
 - Total Annual Income
 - Whether Income is Verifiable
 - Open Credit Lines
 - Location (State) 

*None of the visualizations within the project are suggesting that there is a causal effect between relationships. They are purely for an understanding of variable correllation, as well as a deeper understanding of the Prosper loan interest rates.*

The project contains 4 separate dashboards throughout the Tableau Story. Some of the plots utilized in these dashboards include: <br>

 - Histograms
 - Box-and-Whisker Plots
 - Line Plots
 - Horizontal Bars
 - Gantt
 - Maps

Where encodings were needed to provide further insight to variables and their relationships, I mainly used color-encodings to call out differences and key points. For example, on the map I used a color scale where the states more red had higher interest rates, and more green had lower rates. The plots below the map in the dashboard used the same colors to highlight the top/bottom 10 state interest rates. Where applicable (including in the prior example), I clarified the color meanings with a legend. <br>

There were 3 drafts to the project including the final draft. The changes were made following feedback from a peer review. The main changes made were aesthetic (i.e. unclear formatting of axes labels), but there were also some portions of the dashboards either added or removed. (For a full description of all of the changes made - as well as the early drafts of the project - see below).

### Feedback

| Version # | Reviewer | Feedback | Action |
|------|------|------|------|
| 1 | Peer Review | Rate-Income Sheet x-axis is unreadable in some of the groups. | Rotated the labels vertically. |
| 1 | Peer Review | Change Verifiable Income x-axis label so that it is more understandable (currently default). | Changed label to just be "Rate". |
| 1 | Peer Review | Unhide x-axis ticks/labels on the Credit Line Distribution Sheet. | Unhid the labels/ticks, and renamed the x/y-axes labels (I thought they could be clearer). |
| 1 | Peer Review | Explain Percentile Ranges in Median Borrower rates per Lines of Credit, add labels on plot. | Removed the 45/55 percentile lines from the plot, they added noise and irrelevant information to the plot. |
| 2 | Peer Review | Top 10 Borrowers States needs to be more clearly explained so that it is understood. | Removed from the dashboard altogether (it is irrelevant and confusing in this case). Instead added top 10 State Rates to the dashboard. |
| 2 | Peer Review | Make it so the Box-and-Whisker Plot doesn't need to be scrolled on. | Adjusted dashboard accordingly. |
| 3 | Peer Review | No defined time-frame. | Added rates over time to first dashboard in story. |

### Project Links <br>

Version 1: https://public.tableau.com/app/profile/benton.tripp/viz/ProsperLoansv1_16230942550010/Story <br>

Version 2: https://public.tableau.com/app/profile/benton.tripp/viz/ProsperLoansv2/Story <br>

Version 3 (Final): https://public.tableau.com/app/profile/benton.tripp/viz/ProsperLoansv3Final/Story

### Resources

https://www.prosper.com/about <br>
https://help.tableau.com/current/pro/desktop/en-us/reference_lines.htm<br>
https://community.tableau.com/s/question/0D54T00000HN5osSAD/how-to-rotate-axis-labels-to-45-degree-inclination<br>
https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html
