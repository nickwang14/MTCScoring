# MTCScoring
Quick application to calculate scorecards and decision results

2 modes: Judge or Jury
+*Judge Mode*+
Allows judge to select limited options for scoring. It will take results and return tally one of 3 final decisions.


*Basic Scoring Options:*
10-9
10-8
10-7
Point Deduction
10 Counts (Auto 10-8 round)

*Instant Win Criteria:*
D     Decision
KO    Knockout
RSC   Referee Stops Contest
RSCH  Referee Stops Contest Head
RET   Retire
DQ    Disqualification
WO    Walk Over
NC    No Contest

*Final Result Options Per Judge*
Red Win   (Numbers or Result)
Blue Win  (Numbers or Result)
Draw      (Numbers or Result)


+*Jury Mode*+
Takes 3 Judge results to tally Final Win Possibilities.

*Final Results*
Win Type:   

+Red Win+       J1 J2 J3
Unanimous Red:  R  R  R
Majority Red:   R  R  D
Split Red:      R  R  B

+Blue Win+      J1 J2 J3
Unanimous Blue: R  R  R
Majority Blue:  R  R  D
Split Blue:     R  R  B

+Draw+          J1 J2 J3
Unanimous Draw: D  D  D
Majority Draw:  D  D  R/B
Split Draw:     R  B  D

  
