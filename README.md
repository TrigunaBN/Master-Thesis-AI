# Master Thesis AI - KU Leuven
<b>Title</b>: Machine Learning for profiling contributors to the University Fund <br>

<b>Promotor</b>: <i>Prof. Dr. Hendrik Blockeel</i> <br>

<b>Context</b>: <br>
Large datasets are becoming increasingly available in different domains. The technology to exploit data is getting more mature and opportunities created by data are manifold. The KU Leuven University Fund manages a database with detailed specifications of their donors and their gifts. The University Fund aims to apply datamining techniques to extract knowledge from this data. This knowledge can then be used for the decision-making process (e.g. if the profile of a loyal donor is derived from the analysis, then this group can be targeted accordingly in the communication process). <br>

In the context of this thesis, you will be working on predictive analytics, forecasting and profiling donors to the University Fund. This will involve the analysis of structured data with parameters of contributors and their gifts (location, age, education,…). <br>

You will work in close collaboration with the University Fund. The Fund is the central office within the university which brings donors and projects together in order to raise extra funds through philanthropy or sponsoring. A fund is an organization within the university governed by a steering board where the donor can be represented. There are more than 150 active funds at the university.

<b>Goal</b>: <br>
The goal of this thesis is to design and evaluate different algorithms to determine the donors profile and to deduct trends in the gift process (using datamining tools like, R., WEKA or Python). It will include algorithms for regression, classification, association rule mining and attribute selection. You will look for trends and anomalies in the data and identify which attributes in the data are the most predictive ones. <br>

You will upload data into a datamining software program and design and evaluate algorithms to: <br>
1. Define the profile of loyal donors: location, age, education, background, does the gift amount play a role? Does a loyal donor always give the same amount? If so, why (not)? <br>
2. Predict: If a donor donates for the first time, how likely is it that he will give a second time? <br>
3. Predict: if a donor donates for fund A and B, how likely is it that he will donate for fund C? <br>
4. Associations: if a donor donates for fund A and B, for which fund is he most likely to donate next? <br>
5. Patterns: why does a donor only donates once in his donor lifetime cycle in our database? Are there similarities in this type of donations (e.g. is the gift linked to a specific event)? <br>
6. Patterns: what are the differences in the profile between a loyal donor and a donor that donates once? <br>
7. Predict: The University Fund divided their gifts into 6 categories: 
    - CAT 1: € 0 – 1.249
    - CAT 2: € 1.250 – 4.999
    - CAT 3: € 5.000 – 14.999
    - CAT 4: € 15.000 – 24.999
    - CAT 5: € 25.000 – 49.999
    - CAT 6: > € 50.000

Based on the results of the algorithms, what is recommended: that contributors for cat. 1 are motivated to donate a sum that belongs to cat. 2 OR is it more likely that a donor for cat. 4 will raise his gift to cat. 5? <br>

<i>Note:I have used <b>Python</b>, <b>MySQL</b>, <b>Excel</b> and <b>Tableau</b> for this thesis</i> <br>
For: <br>
Question 1 -> Refer 'Profile of Loyal Donors.ipynb' <br>
Question 2 -> Refer 'Data Preparation & Feature Construction.ipynb' and 'Classification of Donors.ipynb' <br>
Question 3 & 4 -> Refer 'Associations, Sequence Mining, and Fund Recommendations.ipynb' <br>
Question 5 -> Refer 'Donation Patterns.ipynb' <br>
Question 6 -> Refer 'Donor Feature Analysis.ipynb' <br>
Question 7 -> Refer 'Donation Category Shifts.ipynb'


