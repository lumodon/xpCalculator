# xpCalculator
This is a showcase simple app to calculate the XP value of a project based on input project points.

Math.md
Get Hired has 4 specs:
- [ ] __10:__ Artifact is a gist with your plan for the week.
- [ ] __10:__ Artifact includes at least 3 specific objectives as a checklist.
- [ ] __50:__ All objectives are completed.
- [ ] __10:__ PR is submitted for [this goal](https://github.com/GuildCrafts/web-development-js/blob/master/_goals/368-Get_Hired.md) with additional resources added to the Resources section.

The total value of these specs is *10 + 10 + 50 + 10 = * __80 points__
The XP of a solo level 4 project is valued around __200 XP Points__

If a user completes for instance:
- [x] __10:__ Artifact is a gist with your plan for the week.
- [x] __10:__ Artifact includes at least 3 specific objectives as a checklist.
- [ ] __50:__ All objectives are completed.
- [x] __10:__ PR is submitted for [this goal](https://github.com/GuildCrafts/web-development-js/blob/master/_goals/368-Get_Hired.md) with additional resources added to the Resources section.

Then they have completed 30 points out of 80 points. The percentage is *(30/80) __ 100 = 37.5%* which commonly rounds to nearest whole number, thus 38%
The XP value if you complete 100% of the project is 200XP, but you completed 38% so you should get 38% of that 200 XP, or *0.38 __ 200 = * __76 XP__

A standard formula can now be derived:

![Points Completed / Points Total = Percentage](math/mathone.gif)
AND
![Percentage * XP Value = XP Received](math/mathtwo.gif)

THEREFORE
![Points Completed / Points Total * XP Value = XP Received](math/maththree.gif)
