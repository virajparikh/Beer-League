Backlift url: https://dustinnssbeerleague-ud9pn.backliftapp.com/

#### Jack and Viraj fixes:

- Automatic refresh of week-by-week scores.

- Before, Enter Scores modal did not show blue Save Scores button if there were 8 teams since it pushed the button below the screen - this is now fixed.

- Validation now prevents incorrect form submit, and prevents ties.

- Form validation now exists on the Score Submit.

#### Phase 1:

-using Bootstrap - done.

-min/max team limits - in place. Season can't start without at least 4 teams, trying to add an 8th team will bring up an alert telling you league is full.

-add teams - working.

-save team info to server - working.

-show team info on hover - working.

#### Phase 2:

-uses pre-defined schedule; differentiates automatically depending on league size. Accounts for bye week. Working.

-capture scores by week: working. 

*	On saving scores, both schedule and save scores modal NOW UPDATES AUTOMATICALLY.

-Win/Loss calculated automatically on score entry, standings update dynamically without manual refresh.


## WHAT ISN'T WORKING (even after re-factoring):

*	Table sort header function does not work properly

*	Deleting any team except the last one results in score assignments to be off. 

