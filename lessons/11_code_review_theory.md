# 11. Code review. The bits and bytes of feedback: Theory

### Goals

1. Understand the specificities of code review in comparison to generic feedback
2. Prepare your pull requests (PR) to be reviewed
3. Know how to review code

## Differences from generic feedback

While feedback can be, at times, highly subjective and generic, code review has a more concrete target: the code being submitted. This leads to some intricacies.

 1. There are tools to automate certain verifications: code formatting, tests and their code coverage, linters. These tools are priceless in code review, since they allow coding practices to be standardized and applied consistently across the codebase and checked automaticcally. Crucially, this frees reviewers to focus on other, more important aspects of the contributions;
 2. They can seem impersonal. After all, we are discussing the code, not the individual, right? Well, not quite. Programmers attach themselves to the code they produce, and we must keep in mind that we are, at the end of the day, giving feedback *to a person*. Be respectful at all times. Don't be like the following reviewer [1]:

```
Ok, so I'm looking at the code generation and your compiler is pure
and utter *shit*.

Adding Jakub to the cc, because gcc-4.9.0 seems to be terminally broken.

Lookie here, your compiler does some absolutely insane things with the
spilling, including spilling a *constant*. For chrissake, that
compiler shouldn't have been allowed to graduate from kindergarten.
We're talking "sloth that was dropped on the head as a baby" level
retardation levels here:
```

 3. They can be more easily actionable, by pointing out specific problems with the code;
 4. It usually has a tight feedback loop. Coder submits a patch, a reviewer comments, then the coder resubmits, until it is good to be merged.

## Prepare your pull requests to be reviewed

To ease the way your pull requests are reviewed be sure to:

 1. Run the linters, formatters and tests before submitting;
 2. Explain, in the main comment, what is the problem the PR is solving and the general way you go about it. This helps guide the reviewer;
 3. Add a test plan, indicating what you did to appropriately test this code change;
 4. If you considered multiple alternatives in a particular part of the implementation, say so, detailing why you eventually chose one over the others. This helps the reviewer to get an understanding of both the problem and your assumptions.

## Know how to review code

When reviewing code make sure that:

 1. Your comments are actionable
 2. You have taken the time to understand the problem and the proposed solution
 3. Make sure that you have the expertise to review this piece of code
 4. Focus on high level aspects, do not bicker about things like style and personal preferences
 5. Be data- and technical-driven, do not base your comments on your opinions

### References

[1]: [Linus Torvalds (2014, July 24). _Re: Random panic in load_balance() with 3.16-rc_. Linux kernel mailing list](https://lkml.org/lkml/2014/7/24/584)

[2]: [Google (n.d.). _Code Review Developer Guide_. Google](https://google.github.io/eng-practices/review/)

[3]: [Google (n.d.). _The Standard of Code Review_. Google](https://google.github.io/eng-practices/review/reviewer/standard.html)
