# Learning Journal

## 2025-07-09 - Project Setup & Learning about AB testing

- created the repository and added notes folder
- reading a few articles:[The surprising power of online experiments](https://hbr.org/2017/09/the-surprising-power-of-online-experiments), [The AB testing Cookbook](https://medium.com/@ibtesamahmex/the-ab-testing-cookbook-d98edb997db7) and [Beginner's guide to Bayesian AB testing](https://medium.com/@ibtesamahmex/beginners-guide-to-bayesian-ab-testing-22f40988d5e6)
- what I noticed: AB testing is probably what users are experimenting when someone complains about a new feature that only a handful of other users can relate to. Or the other way around, telling everybody how this new feature is awesome and other people being sad about not having it yet. 
- learned that to fully get the benefits of this kind of testing, you have to do it a LOT, which requires infrastructure. So there's definitely a trade-off involved.
- vocab: 
        *overall evaluation criterion* (OEC) is the evaluation metric, it's not a one size fits all but rather developed very individually and needs regular updating (annually e.g.). Bing has created more than 6,000 metrics that experimenters can use, it's maybe worth looking those up.
        *carry-over effect*: when people are reused for experiments, it could alter their future behavior, leading to biased results, so always shuffling users helps
- **important**: running an AA test and getting the result of no significant difference is a way to make sure the formulas and numbers are correct!! 
- steps of AB testing:
    1. formulating a hypothesis
    2. deciding the randomisation unit and splitting into groups (control and treatment group)
    3. deciding the metric and the time duration for the test (driver metrics, guardrail metrics)
    4. power analysis (2 types of errors)
- tests: parametric (assumes pop of data has normal distr, only continuous data) and non-parametric (no distr assumption, continuous and categorical data possible)
    - parametric: T-Test, Welch's T-Test, Dependent T-Test / Z-Test / F-Test
    - non parametric: chi-squared test / mann whitney U test / kruskal wallis H-test
- next articles I might want to check out: [Even Split Increases Power of A/B Tests](https://towardsdatascience.com/even-split-increases-power-of-a-b-tests-7cc2b8cb182a/) and the next article in the cookbook series: [Part 4](https://medium.com/@ibtesamahmex/the-ab-testing-cookbook-part-4-a0243c6ad5e6)

**Conclusion of day 1: I feel like I now understand what an AB Test is and how it can be useful, especially in a business setting. I'd rather start building something than keep learning and look up things as I go, so that's the plan for tomorrow.**

