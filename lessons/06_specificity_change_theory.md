# 6. Specificity of feedback II. The trip from general to specific feedback: Theory


## Why do we need to give specific feedback?

Even if sometimes people have good intentions about sharing their thoughts with other people, the feedback can be so general that the receptor is confused about the next step.

For example, in the code reviews, we can find some generic feedback as the following:

1. The code is not very efficient, can you please optimize some of it?
2. I find your code very difficult to understand
3. There are some lines that do not following our coding best practices

Even if the previous sentences are well intentioned they can confuse a junior developer For the item number one of our previous list, the junior engineer can start asking themselves these questions,

*Is all my code not efficient or only a specific function? Is there a specific part of my code that is not well designed?*

After all, the feedback is important in every part of the teams, but sometimes junior developers need a very clear and specific way of feedback since they are starting their careers and learning the good coding practices of their new teams.

How can engineers provide a better feedback and be more specific? There are some methodologies already established for this, in this case the S.T.A.R. and S.B.I methodology will be approached.

## S.T.A.R. Methodology

This methodology was firstly introduced by Development Dimensions International, INC (DDI), it was developed by their CEO William C. Byham in 1974 (DDI, 2021). The initial purpose of this methodology was to have a structured interviewing system, although it can be adapted to learn how to go from build specific feedback.

The S.T.A.R model can help in giving specific feedback since it allow the people to think in the the situations, tasks, actions and results of the person who is going to receive feedback, before actually giving it.


| S.T.A.R. Concept | Defintion | Examples | 
| ---------------- | --------- | ------ |
| Situation        | The following questions need to be answered: What? When? Who? (DDI, 2021) | Senior developer to Junior developer: "I felt that in the last iteration of the project your code did not comply with our styling guides" | 
| Task | Which should be the expected behavior? (DDI, 2021) | Senior developer to Junior developer: "In order to keep the same formatting style in our team, we like to follow the styling guidelines that are specified" |
| Action | Which was the tasks that have been done or not? (DDI, 2021) |Senior developer to Junior developer: "Because the lack of the formatting style in your last code, you spent twice the time that that you would have if you had followed them since the beginning" |
| Result | Which was the impact of the action? (DDI, 2021)| Senior developer to Junior developer: "The work of the code reviewer is going to complicate more if engineers do not follow coding guidelines, since they are already used to one way of working" |

Once the person that is going to give the feedback already thought in the previous items, they need to know that the vague words are something to be avoided in terms of giving feedback.

- Avoid vague sentences. Even if the intention is good, a vague sentence will not be very helpful.
  - General feedback: "Your code needs improvement".
  - Specific feedback:  "Your did not followed our styling guidelines, in specific the ones about the formatting of variables, because of that the code reviewer invest more time"

- Provide examples of what is mentioned in the feedback:
  - General feedback "I didn't like your last submission"
  - Specific feedback "I didn't like your last submission because you used your own code instead of using the already built-in functions previously developed by the team".


## S.B.I methodology

| S.B.I Concept | Definition | Examples |
| ------------- | ---------- | -------- |
| Situation | Describe the situation. Be specific about when and where it occurred, use concepts of time and place, that can help (CCL, 2021). | "During the last iteration of the project ... ". |
| Behavior  | Describe what you observer in the other person behavior, don't assume that people can guess what you are thinking (CCL, 2021). |  "I noticed that you lacked of time to submit the last iteration of the project and instead of giving a heads up, you just submitted an incomplete commit". |
| Impact | Describe what you thought or felt in reaction to the behavior (CCL, 2021). | "The team felt that you did not thought in the team, since your incomplete commit gave more work to the reviewers". |


### References:

[1]: [About DDI | Leadership Assessment & Development. (n.d.). DDI. Retrieved October 31, 2021](https://www.ddiworld.com/about/history)

[1]: [CCL. (2021, September 15). Use SBI (situation-behavior-impact) to understand intent. Center for Creative Leadership (CCL). Retrieved November 14, 2021](https://www.ccl.org/articles/leading-effectively-articles/closing-the-gap-between-intent-vs-impact-sbii/.)

---

[Previous Lesson: 5. Practice](05_specificity_diff_practice.md)

[Next Lesson: 6. Practice](06_specificity_change_practice.md)
