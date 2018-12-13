# *Metastudies* Analysis

This is a writeup of a basic analysis of a slice of data from [*"Metastudies for robust tests of theory."* by Baribault et al.](https://doi.org/10.1073/pnas.1708285114)

The experimental task consisted of subjects, over multiple sessions, clicking an indicated target either *quickly* or *accurately*, depending on which cue they recieved. The cues were either *visible* or *masked*. Performance at this task nominally reveals whether the value of the *masked cue*, while not consciously perceptible, impacted participant behavior.

The analytic objective is to:
- assess the effect size of cue condition (visibility x instruction)
- for each *experimental session*, use linear regression to find the intercepts and coefficients for the Instruction variable in each visibility condition
- repeat these regressions with an additional penalty term to bias these estimates towards the grand mean of their values across all sessions.
