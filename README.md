# Encephale Cardiovascular Accident_lol
Brain Stroke Data Frame
https://drive.google.com/file/d/15G9Ksaq_29WPXOO0Z-ND7RsWG4N8SiD6/view?usp=sharing

This an analysis made on the aforementioned data base. It includes the use of the age, gender, hypertension, heart disease, BMI, smoking status, and if the respondent was ever married. Analysis mainly focuses their relation with strokes and other ailments.

Firstly, the data was transferred into Python as a CSV file for access and analysis. Functions were used to examine the dataframe for errors, missing values, discrepancies, and business logics. Any values deemed necessary for change were done so using in built Python functions. There were discrepencies in the way some of the words are formatted and is promptedly changed with the replace function. Otherwise, the data was clean with no other missing values, discrepencies, or buisness logics.

A couple of filters were put onto the data to gain further insights on how the data would correlate with strokes. We have observed positive correlation of stroke with age, marriage, and the female gender.

Various graphs were also constructed to better view the relationships some factors have with each other. 

Graph 1, a scatter plot, used grouping to show a positive correlation between age and the average glucose level. Along with a correlation analysis on the subject showing fairly strong positive correlations. 
<img width="848" height="547" alt="q" src="https://github.com/user-attachments/assets/cd4a9ff7-17dc-47ab-86dc-bb2652a96f7f" />

Interestingly, using filters we could conclude that graph 2, a count plot, showed a negative correlation of smoking to the occurrences of heart diseases. This pretty counter-intuitive and could be a result of the limited data size.
<img width="835" height="546" alt="w" src="https://github.com/user-attachments/assets/2851cc71-fed3-465c-a8d3-6dacb44bd39b" />

Graph 3, a line plot, is a simple line graph that showed the positive correlations between hypertensions and strokes. This quite natural to assume and the correlation analysis revealed moderate positive correlations between the two.
<img width="850" height="542" alt="e" src="https://github.com/user-attachments/assets/6bd8d318-6a29-4e4a-85ce-0748774dc0a3" />

Lastly, Graph 4, a histogram, showed a distribution of BMI according to the type of work the respondent did. With Stay at home having a more significant right skew and private work providing the most data and being much more bell shaped.
<img width="851" height="545" alt="image" src="https://github.com/user-attachments/assets/4eb60ce6-35f9-4b39-bdc8-354ba0ca8d98" />

Many correlation tests were tested and interestingly, marriage had the most positive correlation with BMI. It is significantly more correlated compared to the other correlation tests, being at a measured value of 0.37.

