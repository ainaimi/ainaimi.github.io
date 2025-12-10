# PDF Naming Convention Guide for Publications

## Directory Structure

Create these directories:
```
files/publications/
├── [Main publication PDFs go here]
└── classroom/
    └── [AJE Classroom article PDFs go here]
```

## Main Publications (26 PDFs needed)

Place these PDFs in `files/publications/`:

1. `Naimi2025_MonteCarloIntegration.pdf`
2. `Zheng2024_Generalization.pdf`
3. `Naimi2024_PRNG.pdf`
4. `Rudolph2023_AspirinPregnancy.pdf`
5. `Bodnar2022_DietaryGuidelines.pdf`
6. `Rudolph2023_IPW_GComputation.pdf`
7. `Rudolph2022_LongitudinalData.pdf`
8. `Kim2021_IncrementalInterventions.pdf`
9. `Bodnar2022_DoublyRobust.pdf`
10. `Rudolph2022_NaturalCourse.pdf`
11. `ConzueloRodriguez2022_EffectModification.pdf`
12. `Naimi2021_AspirinPerProtocol.pdf`
13. `Naimi2023_MLChallenges.pdf`
14. `Naimi2021_IncrementalPropensity.pdf`
15. `Rudolph2021_SimulationTeaching.pdf`
16. `Rudolph2020_CompetingEvents.pdf`
17. `Bodnar2020_DietarySynergy.pdf`
18. `Cartus2020_Undersampling.pdf`
19. `Naimi2019_ActionableInferences.pdf`
20. `Naimi2018_SuperLearning.pdf`
21. `Larkin_BirthweightCurves.pdf` (no year in filename - add year if you have it)
22. `Naimi2016_ComplexSystems.pdf`
23. `Naimi2017_GMethods.pdf`
24. `Naimi2016_FundamentalCause.pdf`
25. `Naimi2016_Stillbirth.pdf`
26. `Naimi2016_MediationDisparities.pdf`
27. `Naimi2015_BoundlessScience.pdf`
28. `Naimi2015_PopulationImpact.pdf`
29. `Naimi2015_CounterfactualTheory.pdf`
30. `Naimi2014_ExposureResponse.pdf`
31. `Naimi2014_StochasticMediation.pdf`
32. `Keil2014_GFormula.pdf`
33. `Naimi2014_MediationMisgivings.pdf`
34. `Naimi2014_IPW.pdf`
35. `Naimi2013_HealthyWorker.pdf`
36. `Cole2013_AsbestosGFormula.pdf`
37. `Naimi2012_Reply.pdf`
38. `Herring2012_EcologicalDesign.pdf`
39. `Naimi2011_Potassium.pdf`

## AJE Classroom Articles (13 PDFs needed)

Place these PDFs in `files/publications/classroom/`:

1. `Naimi2025_InferentialStatistics.pdf`
2. `Zivich2024_NeuralNetworks.pdf`
3. `Naimi2024_IPW_Categorical.pdf`
4. `Banack2024_ColliderBias2.pdf`
5. `Whitcomb2023_Interaction.pdf`
6. `Banack2023_ColliderBias1.pdf`
7. `Naimi2023_LATE.pdf`
8. `Naimi2023_ATE.pdf`
9. `Naimi2023_CorrelatedData.pdf`
10. `Whitcomb2021_Noncollapsibility.pdf`
11. `Naimi2020_RiskRatios.pdf`
12. `Whitcomb2020_Misclassification.pdf`
13. `Naimi2020_ConfidenceIntervals.pdf`

## Naming Convention Pattern

**Main Publications:**
```
FirstAuthorLastNameYYYY_ShortDescriptiveTitle.pdf
```

**Examples:**
- `Naimi2024_PRNG.pdf` (short acronym)
- `Naimi2018_SuperLearning.pdf` (descriptive title)
- `Rudolph2023_AspirinPregnancy.pdf` (topic-based)

**AJE Classroom Articles:**
Same pattern, but stored in `classroom/` subdirectory

**Tips:**
- Use camelCase for multi-word titles (e.g., `SuperLearning`, `MediationDisparities`)
- Keep titles concise but descriptive
- Avoid special characters (except underscore `_`)
- Always include year

## Next Steps

1. Create the directories:
   ```bash
   mkdir -p files/publications/classroom
   ```

2. Rename your PDFs according to this guide

3. Place them in the appropriate directories

4. Let me know when done, and I'll rebuild the site!
