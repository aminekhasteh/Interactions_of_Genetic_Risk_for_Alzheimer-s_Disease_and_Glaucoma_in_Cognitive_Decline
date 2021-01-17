# Understanding The Interactions of Genetic Risk for Alzheimer’s Disease and Glaucoma in Cognitive Decline With Machine Learning

Alzheimer’s disease (AD) is the most common cause of dementia in aging and has etiological links to primary open-angle glaucoma. Gene variants have been identified as risk factors
for both diseases, though the degree of overlap in genetic risk is not well understood. Further,
it is not known how risk for these diseases interact to influence pathological aging. Using published genome-wide summary statistics, we calculated multiple polygenic risk scores (PRSs)
for AD and glaucoma at multiple P-value thresholds for variant inclusion in two large longitudinal cohort studies of aging including longitudinal cognitive decline. By using machine
learning methods which are hierarchical group-lasso regularization and best subset selection,
interaction terms evaluated interdependent effects of these scores on cognitive decline. In
2,067 elderly subjects, the group-lasso regularization method was able to select a model with
two interactions between AD and Glaucoma (PRS of AD at p ≤ 10−4 with PRS of Glaucoma
at p ≤ 0.001, and PRS of AD at p ≤ 10−5 with PRS of Glaucoma at p ≤ 0.001). From the
selected model by group-lasso regularization method, we used best subset selection to select
a more parsimonious model; It included an interaction between of PRSs between AD and
Glaucoma (PRS of AD at p ≤ 10−4 with PRS of Glaucoma at p ≤ 0.001). The two selected
PRSs were correlated (Pearson r=0.0235, CI 95%=[-0.0196,0.0667]) when including a large
number of genetic variants in PRS of AD (p ≤ 10−4
) and only the top variants for PRS of
Glaucoma (p ≤ 0.001). A weak interaction was observed between AD and glaucoma PRS
(uncorrected p = 0.082) for levels of cognitive decline, whereby individuals at high risk for
AD were protected from cognitive decline, if they had lower risk for Glaucoma. Our final
model was able to explain 24.39% of the variations in cognitive decline. The biological link
between AD and Glaucoma has been shown in previous studies. However, the genetic links
between the two traits has not been explored yet.

