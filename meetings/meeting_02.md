# PHYS3116 Computational Assessment
# Meeting 2

**Date:** 7 October 2026 (Wednesday)  
**Time:** 2:00 pm    
**Location:** Teams  

## Attendance

- Sarah Lawler
- Christian McCarthy
- Hanna Bridges

## Agenda

- Review progress on data cleaning
- Confirm the main analyses for the project
- Divide analysis tasks between team members
- Discuss how results will be combined to identify candidate accreted globular clusters

## Discussion

### Data Cleaning

Sarah completed the initial data cleaning and catalogue merging. Cluster identifiers were standardised across the VandenBerg, Harris and Krause catalogues, and the datasets were merged into a common cleaned dataset containing 55 globular clusters.

The cleaned dataset contains age, metallicity, positional, kinematic and structural information that can now be used for the main scientific analysis.

### Overall Analysis Strategy

The group agreed that the project should focus on two main indicators of possible globular cluster accretion:

1. **Stellar population behaviour**, particularly outliers in the age-metallicity relation.
2. **Dynamical behaviour**, particularly clusters that do not follow the bulk Galactic rotation pattern.

These results will later be combined to identify stronger candidate accreted clusters.

### Age-Metallicity Analysis

Christian will investigate the relationship between cluster age and metallicity, `[Fe/H]`.

Planned analysis:

- Plot age against `[Fe/H]`
- Include age uncertainties where appropriate
- Determine the main age-metallicity trend
- Calculate residuals from the fitted trend
- Identify clusters with unusually large age-metallicity residuals

Clusters that are unusually young or old for their metallicity may represent possible accreted populations.

### Kinematic Analysis

Hanna will investigate whether any clusters display unusual dynamical behaviour.

Planned analysis:

- Plot `v_LSR` against Galactic longitude `L`
- Investigate the bulk rotational behaviour of the cluster sample
- Fit or otherwise characterise the main kinematic trend
- Calculate velocity residuals
- Identify clusters with unusually large deviations from the bulk behaviour

Clusters that do not follow the main rotational pattern may provide independent evidence for accretion.

### Catalogue Comparison and Robustness Testing

Sarah will investigate the consistency between the VandenBerg and Krause catalogues.

Planned analysis:

- Compare VandenBerg and Krause age estimates
- Compare VandenBerg and Krause metallicity estimates
- Plot both comparisons against a 1:1 agreement line
- Quantify the typical differences between catalogue measurements
- Identify clusters with the largest catalogue disagreements
- Test whether candidate accreted clusters remain unusual when Krause measurements are used instead of VandenBerg measurements

This will help assess whether the identification of unusual clusters depends strongly on the choice of catalogue.

### Combined Candidate Selection

Once the individual analyses are complete, the group will compare the results and identify clusters supported by multiple lines of evidence.

A final candidate table may include:

| Cluster | Age-Metallicity Outlier | Kinematic Outlier | Robust to Catalogue Choice | Accretion Candidate |
|---|---|---|---|---|
| Cluster ID | Yes/No | Yes/No | Yes/No | Strong/Possible/Unlikely |

Clusters that are unusual in both their stellar population properties and their kinematics will be treated as stronger accretion candidates.

### Possible Extension

If time permits, the group may investigate the spatial distribution of candidate clusters using quantities such as Galactocentric distance or Galactic Cartesian coordinates to determine whether candidate accreted clusters show different spatial behaviour from the rest of the sample.

## Action Items

| Team Member | Task |
|---|---|
| Sarah | Complete VandenBerg-Krause catalogue comparison and robustness analysis |
| Christian | Complete age-metallicity relation and residual analysis |
| Hanna | Complete kinematic analysis and identify dynamical outliers |
| All | Compare candidate clusters and combine results into a final accretion-candidate classification |

## Next Meeting
**Date:** Monday 12th of October  
**Time:** 2:30pm   
**Planned focus:** 
- Review completed plots and results
- Compare identified outliers
- Begin selecting candidate accreted clusters
- Discuss interpretation in the context of Milky Way formation