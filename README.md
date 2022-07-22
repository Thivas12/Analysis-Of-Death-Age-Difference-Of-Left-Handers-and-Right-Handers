# Analysis-Of-Death-Age-Difference-Of-Left-Handers-and-Right-Handers

Barak Obama is left-handed. So are Bill Gates and Oprah Winfrey; so were Babe Ruth and Marie Curie. A 1991 study reported that left-handed people die on average nine years than right-handed people. Nine years! Could this really be true?.

In this project, we will explore this phenomenon using age distribution data to see if we can reproduce a difference in average age at death purely from the changing rates of left-handedness over time, refuting the claim of early death for left-handers. This notebook uses pandas and Bayesian statistics to analyse the probability of being a certain age at death given that you are reported as left-handed or right-handed.

A National Geographic survey in 1986 resulted in over a million responses that included age, sex and hand preference for throwing and writing. Researchers Avery Gilbert and Charles Wysocki analysed this data and noticed that rates  of left-handedness were around 13% for people younger than 40 but decreased with age to about 5% by the age of 80. They concluded based on analysis of a subgroup of people who throw left-handed but write right-handed that this age-dependence was primarily due to changing social acceptability of left-handedness. This means that the rates aren’t a factor of age speciality but rather of the year you were born, and if the same study was done today, we should expect a shifted version of the same distribution as a function of age. Ultimately, we’ll see what effect this changing rate has on the apparent mean.

This project uses two datasets : death distribution data, rates of left-handedness.


