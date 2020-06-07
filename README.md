# oil-s-production-and-political-decisions-in-Russia
Statistical investigation of oil's production and political decisions in Russia
A study of the statistical dependence of oil exports from Russia on macroeconomic and political factors

1 Table of Contents
2. General statement of the problem 1
2.1. Statement of applied problem 1
2.2. Potential consumers of the solution; tasks that they can solve using the obtained results 2
2.3. The main hypotheses that are planned to be tested as part of the solution of problem 2
2.4. Key data sources 3
2.5. Publications on this topic 4
3. Preliminary analysis of the collected data 4
3.1. Analysis of data features: potential error and missing values, groups and outliers 4
3.1.1. Quantitative Variable Analysis 4
3.1.2. Analysis of Qualitative Variables 7
3.2. Statistical Linkage Analysis 8
3.2.1. Graphical analysis of the pair “numerical dependent variable - qualitative independent variable” 8
3.2.2. Graphical analysis of the pair “numerical dependent variable - numerical independent variable” 11
3.2.3. Analysis of the correlation between independent variables 15
4. Specification, evaluation and optimization of the model 22
4.1. The relationship of the structure of the basic model with the main hypotheses of the study: 22
4.2. Assessment of the base model and hypothesis test results 23
4.3. Emission Analysis 25
4.4. Heteroskedasticity Analysis 26
4.5. Model Optimization 27

Solved applied problem: determine Y - the volume of export of crude oil (Export), million tons,
at given levels of quantitative indicators of macroeconomics:
- oil production volume (Output variable, mln tons);
- the volume of primary oil refining in the Russian Federation (Primary_proc, mln tons);
- the set quotation for the sale of oil (Quotation, dollars / ton - from the 15th of the current month to the 15th of the next month)
- the specified macroeconomic indicators of the export duty (Export_duty, dollars / ton - for the current month);
as well as at given levels of quality variables, according to the author, affecting the volume of exports in terms of macroeconomics and politics:
 - an agreement with OPEC on not exceeding a certain level of oil production (OPEC_convention, 0 - no, 1 - yes);
 - The economic crisis in Venezuela (Venezuela_crisis, 0 - no, 1 - yes), which affected the volume of oil production in the country and export abroad;
- election year in Russia (Russia_elections, 0 - no, 1 - yes);
- a statement by the largest Russian vertically integrated oil companies on the achievement of the maximum level of oil production in Russia by the largest producing companies in the Russian Federation (Russia_max_output, 0 - no, 1 - yes).
