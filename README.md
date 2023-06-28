# Modeling-Mining-Impact-by-Using-R
Detecting the Mine Site Impact on Rarerus Plantus ChlorophyII Level

The company has provided with a csv of data which contains information on the health of particular plants surrounding the mine site. Each row of data contains bimonthly measurement of chlorophyll and wheather that plant is located near (<50m) or far (>50m) from the mining activity. The greater the chlorophyll measurement, the healthier the plant is deemed to be. It is known that mining commenced in June 2017.

The non parametric test Friedman test were used, followed by post hoc test : Pairwise comparisons using Wilcoxon rank sum test.

From the result of the tests, we conclude:

If the mean yearly level of Chlorophyll deemed to be the same over the year without the existence of the mine site, we have 95% confidence that mining activity has had an impact on the plant Rarerus Plantus. More specifically, the health of Rarerus Plantus has been impacted in all the following 5 years, since the commencement of mine activity.
![Screenshot 2023-06-28 193043](https://github.com/coffeemartin/Modeling-Mining-Impact-by-Using-R/assets/73702415/59b6ab9a-36e7-489e-bf9d-a01ffecd2475)
![Screenshot 2023-06-28 193107](https://github.com/coffeemartin/Modeling-Mining-Impact-by-Using-R/assets/73702415/585e4249-6c13-4662-8d61-591a31ab9be6)
![Screenshot 2023-06-28 193121](https://github.com/coffeemartin/Modeling-Mining-Impact-by-Using-R/assets/73702415/4032546c-d63b-490b-9932-522ef684851c)
