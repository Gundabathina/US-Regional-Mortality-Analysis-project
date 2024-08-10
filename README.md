# US Regional Mortality Analysis

## Project Overview


The "US Regional Mortality Analysis" project is an in-depth exploration of mortality trends across various regions of the United States. This analysis seeks to uncover regional disparities, identify potential socio-economic and demographic factors contributing to these differences, and provide actionable insights for public health policy and intervention strategies. The project leverages advanced data analysis techniques and visualization tools to present a comprehensive view of mortality patterns, enabling stakeholders to make informed decisions based on empirical evidence.

This project is particularly relevant in the context of ongoing public health challenges, offering valuable insights that can aid in understanding the underlying causes of mortality rate variations across different regions. By examining factors such as age, gender, cause of death, and geographic location, this analysis provides a nuanced understanding of how mortality rates differ and what might be driving these differences.
## Dataset Description
The dataset employed in this analysis is sourced from authoritative public health databases, including but not limited to the CDC WONDER database and the National Vital Statistics System (NVSS). It encompasses a wide array of variables, including:

- Geographic Region: Data is categorized by state and region (e.g., Northeast, Midwest, South, West).
- Demographics: Includes age, gender, race, and ethnicity of individuals.
- Cause of Death: Classified according to the International Classification of Diseases (ICD) codes.
- Time Period: Spanning multiple years to analyze trends over time.

## Tools and Technologies
The following tools and technologies were integral to the project's success:

- Python: Core programming language used for data analysis.
- Pandas: Essential for data manipulation and analysis.
- NumPy: Used for numerical computations and handling large datasets.
- Matplotlib & Seaborn: Employed for creating detailed and informative visualizations.
- Scipy & Statsmodels: Applied for statistical testing and regression analysis.
- Geopandas: Used for geospatial analysis and mapping.
- Jupyter Notebook: The interactive environment used to conduct and document the analysis process.

## Key Findings
The key findings from the analysis include:

- Regional Disparities: Significant differences in mortality rates were observed between regions, with certain areas showing consistently higher rates of specific causes of death.
- Demographic Influences: Age and gender were found to be major factors influencing mortality rates, with notable variations across different regions.
- Socio-economic Correlations: A strong correlation was identified between socio-economic status and mortality rates, suggesting that income, education, and healthcare access play crucial roles in determining health outcomes.



## Authors

- [@Prem_teja] 
https://github.com/Gundabathina/US-Regional-Mortality-Analysis-project
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prem-teja-21856a28b)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/)

 401 changes: 401 additions & 0 deletions401  
USRegionalMortality.csv
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,401 @@
rownames,Region,Status,Sex,Cause,Rate,SE
5,HHS Region 01,Urban,Male,Heart disease,188.2,1
6,HHS Region 01,Rural,Male,Heart disease,199.1,2.6
7,HHS Region 01,Urban,Female,Heart disease,115.1,0.6
8,HHS Region 01,Rural,Female,Heart disease,124.5,1.7
9,HHS Region 02,Urban,Male,Heart disease,226.8,0.8
10,HHS Region 02,Rural,Male,Heart disease,248.8,3.3
11,HHS Region 02,Urban,Female,Heart disease,148.6,0.5
12,HHS Region 02,Rural,Female,Heart disease,165.6,2.3
13,HHS Region 03,Urban,Male,Heart disease,218.2,0.8
14,HHS Region 03,Rural,Male,Heart disease,246,2
15,HHS Region 03,Urban,Female,Heart disease,138.1,0.5
16,HHS Region 03,Rural,Female,Heart disease,162.5,1.4
17,HHS Region 04,Urban,Male,Heart disease,212.8,0.5
18,HHS Region 04,Rural,Male,Heart disease,276.4,1.3
19,HHS Region 04,Urban,Female,Heart disease,132.2,0.4
20,HHS Region 04,Rural,Female,Heart disease,176.8,0.9
21,HHS Region 05,Urban,Male,Heart disease,222.5,0.6
22,HHS Region 05,Rural,Male,Heart disease,229,1.2
23,HHS Region 05,Urban,Female,Heart disease,139.6,0.4
24,HHS Region 05,Rural,Female,Heart disease,140.8,0.8
25,HHS Region 06,Urban,Male,Heart disease,219.9,0.8
26,HHS Region 06,Rural,Male,Heart disease,266.4,1.6
27,HHS Region 06,Urban,Female,Heart disease,140.7,0.5
28,HHS Region 06,Rural,Female,Heart disease,175.7,1.1
29,HHS Region 07,Urban,Male,Heart disease,210,1.3
30,HHS Region 07,Rural,Male,Heart disease,237.7,1.7
31,HHS Region 07,Urban,Female,Heart disease,131.1,0.9
32,HHS Region 07,Rural,Female,Heart disease,152.3,1.2
33,HHS Region 08,Urban,Male,Heart disease,166.5,1.4
34,HHS Region 08,Rural,Male,Heart disease,191.2,2.1
35,HHS Region 08,Urban,Female,Heart disease,106.7,0.9
36,HHS Region 08,Rural,Female,Heart disease,119.8,1.4
37,HHS Region 09,Urban,Male,Heart disease,195.8,0.6
38,HHS Region 09,Rural,Male,Heart disease,205.8,2.7
39,HHS Region 09,Urban,Female,Heart disease,121,0.4
40,HHS Region 09,Rural,Female,Heart disease,125.2,1.9
41,HHS Region 10,Urban,Male,Heart disease,176,1.1
42,HHS Region 10,Rural,Male,Heart disease,194.9,2.3
43,HHS Region 10,Urban,Female,Heart disease,106,0.7
44,HHS Region 10,Rural,Female,Heart disease,114.3,1.6
57,HHS Region 01,Urban,Male,Cancer,194.5,1
58,HHS Region 01,Rural,Male,Cancer,202.7,2.5
59,HHS Region 01,Urban,Female,Cancer,140.3,0.8
60,HHS Region 01,Rural,Female,Cancer,144.7,2
61,HHS Region 02,Urban,Male,Cancer,187.5,0.7
62,HHS Region 02,Rural,Male,Cancer,204.9,2.9
63,HHS Region 02,Urban,Female,Cancer,139.2,0.5
64,HHS Region 02,Rural,Female,Cancer,151.7,2.3
65,HHS Region 03,Urban,Male,Cancer,204.3,0.7
66,HHS Region 03,Rural,Male,Cancer,224.7,1.9
67,HHS Region 03,Urban,Female,Cancer,146.7,0.5
68,HHS Region 03,Rural,Female,Cancer,156.7,1.4
69,HHS Region 04,Urban,Male,Cancer,204.7,0.5
70,HHS Region 04,Rural,Male,Cancer,245.2,1.2
71,HHS Region 04,Urban,Female,Cancer,139.9,0.4
72,HHS Region 04,Rural,Female,Cancer,156.2,0.8
73,HHS Region 05,Urban,Male,Cancer,207.3,0.6
74,HHS Region 05,Rural,Male,Cancer,217.2,1.1
75,HHS Region 05,Urban,Female,Cancer,149.9,0.4
76,HHS Region 05,Rural,Female,Cancer,152,0.9
77,HHS Region 06,Urban,Male,Cancer,201.6,0.7
78,HHS Region 06,Rural,Male,Cancer,223.8,1.4
79,HHS Region 06,Urban,Female,Cancer,137.8,0.5
80,HHS Region 06,Rural,Female,Cancer,151.8,1.1
81,HHS Region 07,Urban,Male,Cancer,204.3,1.3
82,HHS Region 07,Rural,Male,Cancer,214.1,1.6
83,HHS Region 07,Urban,Female,Cancer,148,1
84,HHS Region 07,Rural,Female,Cancer,149.7,1.3
85,HHS Region 08,Urban,Male,Cancer,167,1.3
86,HHS Region 08,Rural,Male,Cancer,173.7,1.9
87,HHS Region 08,Urban,Female,Cancer,122.5,1
88,HHS Region 08,Rural,Female,Cancer,132.6,1.6
89,HHS Region 09,Urban,Male,Cancer,176.1,0.5
90,HHS Region 09,Rural,Male,Cancer,186.7,2.5
91,HHS Region 09,Urban,Female,Cancer,130.1,0.4
92,HHS Region 09,Rural,Female,Cancer,135.7,2
93,HHS Region 10,Urban,Male,Cancer,190.6,1.1
94,HHS Region 10,Rural,Male,Cancer,197.1,2.3
95,HHS Region 10,Urban,Female,Cancer,140.9,0.9
96,HHS Region 10,Rural,Female,Cancer,143.8,1.9
109,HHS Region 01,Urban,Male,Lower respiratory,36.7,0.5
110,HHS Region 01,Rural,Male,Lower respiratory,51.7,1.3
111,HHS Region 01,Urban,Female,Lower respiratory,32.2,0.4
112,HHS Region 01,Rural,Female,Lower respiratory,41.3,1
113,HHS Region 02,Urban,Male,Lower respiratory,33,0.3
114,HHS Region 02,Rural,Male,Lower respiratory,59.3,1.6
115,HHS Region 02,Urban,Female,Lower respiratory,28,0.2
116,HHS Region 02,Rural,Female,Lower respiratory,46.3,1.2
117,HHS Region 03,Urban,Male,Lower respiratory,41.7,0.3
118,HHS Region 03,Rural,Male,Lower respiratory,62.1,1
119,HHS Region 03,Urban,Female,Lower respiratory,34.4,0.3
120,HHS Region 03,Rural,Female,Lower respiratory,46.4,0.8
121,HHS Region 04,Urban,Male,Lower respiratory,48.5,0.3
122,HHS Region 04,Rural,Male,Lower respiratory,70.7,0.6
123,HHS Region 04,Urban,Female,Lower respiratory,39.9,0.2
124,HHS Region 04,Rural,Female,Lower respiratory,51.1,0.5
125,HHS Region 05,Urban,Male,Lower respiratory,48.7,0.3
126,HHS Region 05,Rural,Male,Lower respiratory,59.9,0.6
127,HHS Region 05,Urban,Female,Lower respiratory,40.1,0.2
128,HHS Region 05,Rural,Female,Lower respiratory,44.7,0.4
129,HHS Region 06,Urban,Male,Lower respiratory,49.5,0.4
130,HHS Region 06,Rural,Male,Lower respiratory,65.8,0.8
131,HHS Region 06,Urban,Female,Lower respiratory,39.4,0.3
132,HHS Region 06,Rural,Female,Lower respiratory,50.5,0.6
133,HHS Region 07,Urban,Male,Lower respiratory,54.8,0.7
134,HHS Region 07,Rural,Male,Lower respiratory,65.9,0.9
135,HHS Region 07,Urban,Female,Lower respiratory,44,0.5
136,HHS Region 07,Rural,Female,Lower respiratory,45.6,0.7
137,HHS Region 08,Urban,Male,Lower respiratory,48.9,0.7
138,HHS Region 08,Rural,Male,Lower respiratory,56.1,1.1
139,HHS Region 08,Urban,Female,Lower respiratory,37.1,0.6
140,HHS Region 08,Rural,Female,Lower respiratory,40.2,0.9
141,HHS Region 09,Urban,Male,Lower respiratory,40.6,0.3
142,HHS Region 09,Rural,Male,Lower respiratory,50.7,1.3
143,HHS Region 09,Urban,Female,Lower respiratory,33.7,0.2
144,HHS Region 09,Rural,Female,Lower respiratory,43.6,1.1
145,HHS Region 10,Urban,Male,Lower respiratory,46.3,0.6
146,HHS Region 10,Rural,Male,Lower respiratory,52.3,1.2
147,HHS Region 10,Urban,Female,Lower respiratory,38.4,0.5
148,HHS Region 10,Rural,Female,Lower respiratory,45.3,1
161,HHS Region 01,Urban,Male,Unintentional injuries,47.4,0.5
162,HHS Region 01,Rural,Male,Unintentional injuries,60.5,1.5
163,HHS Region 01,Urban,Female,Unintentional injuries,22.5,0.3
164,HHS Region 01,Rural,Female,Unintentional injuries,28.8,1
165,HHS Region 02,Urban,Male,Unintentional injuries,39.7,0.3
166,HHS Region 02,Rural,Male,Unintentional injuries,49.6,1.5
167,HHS Region 02,Urban,Female,Unintentional injuries,17,0.2
168,HHS Region 02,Rural,Female,Unintentional injuries,23.4,1
169,HHS Region 03,Urban,Male,Unintentional injuries,51.8,0.4
170,HHS Region 03,Rural,Male,Unintentional injuries,77.6,1.2
171,HHS Region 03,Urban,Female,Unintentional injuries,24.3,0.2
172,HHS Region 03,Rural,Female,Unintentional injuries,39.8,0.9
173,HHS Region 04,Urban,Male,Unintentional injuries,56.2,0.3
174,HHS Region 04,Rural,Male,Unintentional injuries,79.1,0.7
175,HHS Region 04,Urban,Female,Unintentional injuries,28.6,0.2
176,HHS Region 04,Rural,Female,Unintentional injuries,41.3,0.5
177,HHS Region 05,Urban,Male,Unintentional injuries,50.9,0.3
178,HHS Region 05,Rural,Male,Unintentional injuries,62.3,0.7
179,HHS Region 05,Urban,Female,Unintentional injuries,25.9,0.2
180,HHS Region 05,Rural,Female,Unintentional injuries,32.3,0.4
181,HHS Region 06,Urban,Male,Unintentional injuries,54.6,0.4
182,HHS Region 06,Rural,Male,Unintentional injuries,77.2,0.9
183,HHS Region 06,Urban,Female,Unintentional injuries,27,0.2
184,HHS Region 06,Rural,Female,Unintentional injuries,39.9,0.6
185,HHS Region 07,Urban,Male,Unintentional injuries,53.4,0.6
186,HHS Region 07,Rural,Male,Unintentional injuries,68.1,1
187,HHS Region 07,Urban,Female,Unintentional injuries,28.7,0.4
188,HHS Region 07,Rural,Female,Unintentional injuries,35.4,0.7
189,HHS Region 08,Urban,Male,Unintentional injuries,55.3,0.7
190,HHS Region 08,Rural,Male,Unintentional injuries,71,1.3
191,HHS Region 08,Urban,Female,Unintentional injuries,32.7,0.5
192,HHS Region 08,Rural,Female,Unintentional injuries,39.2,0.9
193,HHS Region 09,Urban,Male,Unintentional injuries,41.8,0.2
194,HHS Region 09,Rural,Male,Unintentional injuries,79.1,1.8
195,HHS Region 09,Urban,Female,Unintentional injuries,20.5,0.2
196,HHS Region 09,Rural,Female,Unintentional injuries,40.9,1.3
197,HHS Region 10,Urban,Male,Unintentional injuries,49.8,0.6
198,HHS Region 10,Rural,Male,Unintentional injuries,66.2,1.5
199,HHS Region 10,Urban,Female,Unintentional injuries,28.4,0.4
200,HHS Region 10,Rural,Female,Unintentional injuries,37.2,1.1
213,HHS Region 01,Urban,Male,Cerebrovascular diseases,28.4,0.4
214,HHS Region 01,Rural,Male,Cerebrovascular diseases,31.2,1
215,HHS Region 01,Urban,Female,Cerebrovascular diseases,28.5,0.3
216,HHS Region 01,Rural,Female,Cerebrovascular diseases,33.6,0.9
217,HHS Region 02,Urban,Male,Cerebrovascular diseases,29.2,0.3
218,HHS Region 02,Rural,Male,Cerebrovascular diseases,32.9,1.2
219,HHS Region 02,Urban,Female,Cerebrovascular diseases,27.2,0.2
220,HHS Region 02,Rural,Female,Cerebrovascular diseases,32.2,1
221,HHS Region 03,Urban,Male,Cerebrovascular diseases,38.2,0.3
222,HHS Region 03,Rural,Male,Cerebrovascular diseases,42.5,0.8
223,HHS Region 03,Urban,Female,Cerebrovascular diseases,37.4,0.3
224,HHS Region 03,Rural,Female,Cerebrovascular diseases,42.1,0.7
225,HHS Region 04,Urban,Male,Cerebrovascular diseases,37.5,0.2
226,HHS Region 04,Rural,Male,Cerebrovascular diseases,49.1,0.5
227,HHS Region 04,Urban,Female,Cerebrovascular diseases,36.4,0.2
228,HHS Region 04,Rural,Female,Cerebrovascular diseases,46.6,0.4
229,HHS Region 05,Urban,Male,Cerebrovascular diseases,38.3,0.3
230,HHS Region 05,Rural,Male,Cerebrovascular diseases,40.6,0.5
231,HHS Region 05,Urban,Female,Cerebrovascular diseases,36.5,0.2
232,HHS Region 05,Rural,Female,Cerebrovascular diseases,40.1,0.4
233,HHS Region 06,Urban,Male,Cerebrovascular diseases,41.4,0.4
234,HHS Region 06,Rural,Male,Cerebrovascular diseases,45.9,0.7
235,HHS Region 06,Urban,Female,Cerebrovascular diseases,39.6,0.3
236,HHS Region 06,Rural,Female,Cerebrovascular diseases,47.2,0.6
237,HHS Region 07,Urban,Male,Cerebrovascular diseases,38,0.6
238,HHS Region 07,Rural,Male,Cerebrovascular diseases,39.2,0.7
239,HHS Region 07,Urban,Female,Cerebrovascular diseases,37.3,0.5
240,HHS Region 07,Rural,Female,Cerebrovascular diseases,40.1,0.6
241,HHS Region 08,Urban,Male,Cerebrovascular diseases,33.7,0.6
242,HHS Region 08,Rural,Male,Cerebrovascular diseases,36.2,0.9
243,HHS Region 08,Urban,Female,Cerebrovascular diseases,34.3,0.5
244,HHS Region 08,Rural,Female,Cerebrovascular diseases,38,0.8
245,HHS Region 09,Urban,Male,Cerebrovascular diseases,34.5,0.2
246,HHS Region 09,Rural,Male,Cerebrovascular diseases,36.6,1.1
247,HHS Region 09,Urban,Female,Cerebrovascular diseases,34,0.2
248,HHS Region 09,Rural,Female,Cerebrovascular diseases,37.5,1
249,HHS Region 10,Urban,Male,Cerebrovascular diseases,36.8,0.5
250,HHS Region 10,Rural,Male,Cerebrovascular diseases,37.1,1
251,HHS Region 10,Urban,Female,Cerebrovascular diseases,35.2,0.4
252,HHS Region 10,Rural,Female,Cerebrovascular diseases,40.3,1
265,HHS Region 01,Urban,Male,Alzheimers,16.4,0.3
266,HHS Region 01,Rural,Male,Alzheimers,18.1,0.8
267,HHS Region 01,Urban,Female,Alzheimers,21.8,0.3
268,HHS Region 01,Rural,Female,Alzheimers,27.9,0.8
269,HHS Region 02,Urban,Male,Alzheimers,10.5,0.2
270,HHS Region 02,Rural,Male,Alzheimers,12.3,0.7
271,HHS Region 02,Urban,Female,Alzheimers,13.6,0.1
272,HHS Region 02,Rural,Female,Alzheimers,17.9,0.7
273,HHS Region 03,Urban,Male,Alzheimers,15.2,0.2
274,HHS Region 03,Rural,Male,Alzheimers,17.9,0.6
275,HHS Region 03,Urban,Female,Alzheimers,19.9,0.2
276,HHS Region 03,Rural,Female,Alzheimers,26.2,0.5
277,HHS Region 04,Urban,Male,Alzheimers,18.3,0.2
278,HHS Region 04,Rural,Male,Alzheimers,25.3,0.4
279,HHS Region 04,Urban,Female,Alzheimers,25.8,0.2
280,HHS Region 04,Rural,Female,Alzheimers,35.2,0.4
281,HHS Region 05,Urban,Male,Alzheimers,20,0.2
282,HHS Region 05,Rural,Male,Alzheimers,20.9,0.4
283,HHS Region 05,Urban,Female,Alzheimers,26,0.2
284,HHS Region 05,Rural,Female,Alzheimers,29.2,0.3
285,HHS Region 06,Urban,Male,Alzheimers,20.7,0.3
286,HHS Region 06,Rural,Male,Alzheimers,22.5,0.5
287,HHS Region 06,Urban,Female,Alzheimers,27.7,0.2
288,HHS Region 06,Rural,Female,Alzheimers,33,0.5
289,HHS Region 07,Urban,Male,Alzheimers,21,0.4
290,HHS Region 07,Rural,Male,Alzheimers,23.8,0.5
291,HHS Region 07,Urban,Female,Alzheimers,27.8,0.4
292,HHS Region 07,Rural,Female,Alzheimers,30.3,0.5
293,HHS Region 08,Urban,Male,Alzheimers,23.7,0.5
294,HHS Region 08,Rural,Male,Alzheimers,21.2,0.7
295,HHS Region 08,Urban,Female,Alzheimers,30.9,0.5
296,HHS Region 08,Rural,Female,Alzheimers,28.3,0.7
297,HHS Region 09,Urban,Male,Alzheimers,24.9,0.2
298,HHS Region 09,Rural,Male,Alzheimers,18.9,0.8
299,HHS Region 09,Urban,Female,Alzheimers,32.1,0.2
300,HHS Region 09,Rural,Female,Alzheimers,24,0.8
301,HHS Region 10,Urban,Male,Alzheimers,29.9,0.5
302,HHS Region 10,Rural,Male,Alzheimers,22.9,0.8
303,HHS Region 10,Urban,Female,Alzheimers,40.8,0.4
304,HHS Region 10,Rural,Female,Alzheimers,33.9,0.9
317,HHS Region 01,Urban,Male,Diabetes,19.2,0.3
318,HHS Region 01,Rural,Male,Diabetes,23.8,0.9
319,HHS Region 01,Urban,Female,Diabetes,12.1,0.2
320,HHS Region 01,Rural,Female,Diabetes,15,0.6
321,HHS Region 02,Urban,Male,Diabetes,22.7,0.2
322,HHS Region 02,Rural,Male,Diabetes,24.5,1
323,HHS Region 02,Urban,Female,Diabetes,15.2,0.2
324,HHS Region 02,Rural,Female,Diabetes,17.6,0.8
325,HHS Region 03,Urban,Male,Diabetes,25,0.3
326,HHS Region 03,Rural,Male,Diabetes,32.5,0.7
327,HHS Region 03,Urban,Female,Diabetes,17.2,0.2
328,HHS Region 03,Rural,Female,Diabetes,24.1,0.6
329,HHS Region 04,Urban,Male,Diabetes,25.2,0.2
330,HHS Region 04,Rural,Male,Diabetes,32,0.4
331,HHS Region 04,Urban,Female,Diabetes,17.4,0.1
332,HHS Region 04,Rural,Female,Diabetes,25,0.3
333,HHS Region 05,Urban,Male,Diabetes,26.6,0.2
334,HHS Region 05,Rural,Male,Diabetes,28.5,0.4
335,HHS Region 05,Urban,Female,Diabetes,18.6,0.2
336,HHS Region 05,Rural,Female,Diabetes,20.3,0.3
337,HHS Region 06,Urban,Male,Diabetes,26.2,0.3
338,HHS Region 06,Rural,Male,Diabetes,32.8,0.5
339,HHS Region 06,Urban,Female,Diabetes,19.9,0.2
340,HHS Region 06,Rural,Female,Diabetes,25.1,0.4
341,HHS Region 07,Urban,Male,Diabetes,22.6,0.4
342,HHS Region 07,Rural,Male,Diabetes,25.9,0.6
343,HHS Region 07,Urban,Female,Diabetes,16,0.3
344,HHS Region 07,Rural,Female,Diabetes,19.1,0.4
345,HHS Region 08,Urban,Male,Diabetes,23.2,0.5
346,HHS Region 08,Rural,Male,Diabetes,24.7,0.7
347,HHS Region 08,Urban,Female,Diabetes,15,0.4
348,HHS Region 08,Rural,Female,Diabetes,18,0.6
349,HHS Region 09,Urban,Male,Diabetes,25.3,0.2
350,HHS Region 09,Rural,Male,Diabetes,24.9,0.9
351,HHS Region 09,Urban,Female,Diabetes,16.7,0.1
352,HHS Region 09,Rural,Female,Diabetes,17.8,0.7
353,HHS Region 10,Urban,Male,Diabetes,28.2,0.4
354,HHS Region 10,Rural,Male,Diabetes,29.8,0.9
355,HHS Region 10,Urban,Female,Diabetes,17.7,0.3
356,HHS Region 10,Rural,Female,Diabetes,20.1,0.7
369,HHS Region 01,Urban,Male,Flu and pneumonia,18.5,0.3
370,HHS Region 01,Rural,Male,Flu and pneumonia,15.6,0.7
371,HHS Region 01,Urban,Female,Flu and pneumonia,12.8,0.2
372,HHS Region 01,Rural,Female,Flu and pneumonia,11.9,0.5
373,HHS Region 02,Urban,Male,Flu and pneumonia,22.4,0.2
374,HHS Region 02,Rural,Male,Flu and pneumonia,19.6,0.9
375,HHS Region 02,Urban,Female,Flu and pneumonia,14.5,0.2
376,HHS Region 02,Rural,Female,Flu and pneumonia,14.9,0.7
377,HHS Region 03,Urban,Male,Flu and pneumonia,18.9,0.2
378,HHS Region 03,Rural,Male,Flu and pneumonia,22.8,0.6
379,HHS Region 03,Urban,Female,Flu and pneumonia,13.3,0.2
380,HHS Region 03,Rural,Female,Flu and pneumonia,17.1,0.5
381,HHS Region 04,Urban,Male,Flu and pneumonia,15.5,0.1
382,HHS Region 04,Rural,Male,Flu and pneumonia,24.1,0.4
383,HHS Region 04,Urban,Female,Flu and pneumonia,11.6,0.1
384,HHS Region 04,Rural,Female,Flu and pneumonia,19,0.3
385,HHS Region 05,Urban,Male,Flu and pneumonia,17.8,0.2
386,HHS Region 05,Rural,Male,Flu and pneumonia,18.8,0.3
387,HHS Region 05,Urban,Female,Flu and pneumonia,12.9,0.1
388,HHS Region 05,Rural,Female,Flu and pneumonia,14.1,0.2
389,HHS Region 06,Urban,Male,Flu and pneumonia,16.6,0.2
390,HHS Region 06,Rural,Male,Flu and pneumonia,23.1,0.5
391,HHS Region 06,Urban,Female,Flu and pneumonia,12.8,0.2
392,HHS Region 06,Rural,Female,Flu and pneumonia,18.1,0.4
393,HHS Region 07,Urban,Male,Flu and pneumonia,18.6,0.4
394,HHS Region 07,Rural,Male,Flu and pneumonia,21.1,0.5
395,HHS Region 07,Urban,Female,Flu and pneumonia,14.4,0.3
396,HHS Region 07,Rural,Female,Flu and pneumonia,17.3,0.4
397,HHS Region 08,Urban,Male,Flu and pneumonia,15.3,0.4
398,HHS Region 08,Rural,Male,Flu and pneumonia,18.1,0.7
399,HHS Region 08,Urban,Female,Flu and pneumonia,11.6,0.3
400,HHS Region 08,Rural,Female,Flu and pneumonia,14.6,0.5
401,HHS Region 09,Urban,Male,Flu and pneumonia,18.5,0.2
402,HHS Region 09,Rural,Male,Flu and pneumonia,19.1,0.8
403,HHS Region 09,Urban,Female,Flu and pneumonia,13.4,0.1
404,HHS Region 09,Rural,Female,Flu and pneumonia,14.9,0.7
405,HHS Region 10,Urban,Male,Flu and pneumonia,11.6,0.3
406,HHS Region 10,Rural,Male,Flu and pneumonia,12.7,0.6
407,HHS Region 10,Urban,Female,Flu and pneumonia,8.8,0.2
408,HHS Region 10,Rural,Female,Flu and pneumonia,10.5,0.5
421,HHS Region 01,Urban,Male,Suicide,15.2,0.3
422,HHS Region 01,Rural,Male,Suicide,25.6,1
423,HHS Region 01,Urban,Female,Suicide,4.5,0.2
424,HHS Region 01,Rural,Female,Suicide,5.8,0.5
425,HHS Region 02,Urban,Male,Suicide,12.6,0.2
426,HHS Region 02,Rural,Male,Suicide,20.3,1
427,HHS Region 02,Urban,Female,Suicide,3.4,0.1
428,HHS Region 02,Rural,Female,Suicide,3.9,0.4
429,HHS Region 03,Urban,Male,Suicide,19.1,0.2
430,HHS Region 03,Rural,Male,Suicide,26.9,0.7
431,HHS Region 03,Urban,Female,Suicide,4.8,0.1
432,HHS Region 03,Rural,Female,Suicide,6.6,0.4
433,HHS Region 04,Urban,Male,Suicide,21.5,0.2
434,HHS Region 04,Rural,Male,Suicide,24.6,0.4
435,HHS Region 04,Urban,Female,Suicide,5.9,0.1
436,HHS Region 04,Rural,Female,Suicide,6,0.2
437,HHS Region 05,Urban,Male,Suicide,18.8,0.2
438,HHS Region 05,Rural,Male,Suicide,23.4,0.4
439,HHS Region 05,Urban,Female,Suicide,4.9,0.1
440,HHS Region 05,Rural,Female,Suicide,5.1,0.2
441,HHS Region 06,Urban,Male,Suicide,20.2,0.2
442,HHS Region 06,Rural,Male,Suicide,27.2,0.5
443,HHS Region 06,Urban,Female,Suicide,5.3,0.1
444,HHS Region 06,Rural,Female,Suicide,6.4,0.3
445,HHS Region 07,Urban,Male,Suicide,22.5,0.4
446,HHS Region 07,Rural,Male,Suicide,26,0.6
447,HHS Region 07,Urban,Female,Suicide,5.8,0.2
448,HHS Region 07,Rural,Female,Suicide,5.8,0.3
449,HHS Region 08,Urban,Male,Suicide,29.1,0.5
450,HHS Region 08,Rural,Male,Suicide,34.3,0.9
451,HHS Region 08,Urban,Female,Suicide,8.7,0.3
452,HHS Region 08,Rural,Female,Suicide,8.4,0.5
453,HHS Region 09,Urban,Male,Suicide,17.9,0.2
454,HHS Region 09,Rural,Male,Suicide,35.4,1.2
455,HHS Region 09,Urban,Female,Suicide,5.2,0.1
456,HHS Region 09,Rural,Female,Suicide,9.7,0.7
457,HHS Region 10,Urban,Male,Suicide,24,0.4
458,HHS Region 10,Rural,Male,Suicide,32.2,1
459,HHS Region 10,Urban,Female,Suicide,7,0.2
460,HHS Region 10,Rural,Female,Suicide,8.6,0.5
473,HHS Region 01,Urban,Male,Nephritis,18.1,0.3
474,HHS Region 01,Rural,Male,Nephritis,13,0.7
475,HHS Region 01,Urban,Female,Nephritis,10.9,0.2
476,HHS Region 01,Rural,Female,Nephritis,8.8,0.5
477,HHS Region 02,Urban,Male,Nephritis,14.5,0.2
478,HHS Region 02,Rural,Male,Nephritis,14.4,0.8
479,HHS Region 02,Urban,Female,Nephritis,8.6,0.1
480,HHS Region 02,Rural,Female,Nephritis,11.6,0.6
481,HHS Region 03,Urban,Male,Nephritis,18.8,0.2
482,HHS Region 03,Rural,Male,Nephritis,22.4,0.6
483,HHS Region 03,Urban,Female,Nephritis,13,0.2
484,HHS Region 03,Rural,Female,Nephritis,17,0.5
485,HHS Region 04,Urban,Male,Nephritis,17.2,0.2
486,HHS Region 04,Rural,Male,Nephritis,22.6,0.4
487,HHS Region 04,Urban,Female,Nephritis,11.7,0.1
488,HHS Region 04,Rural,Female,Nephritis,17.3,0.3
489,HHS Region 05,Urban,Male,Nephritis,18.5,0.2
490,HHS Region 05,Rural,Male,Nephritis,17.9,0.3
491,HHS Region 05,Urban,Female,Nephritis,12.9,0.1
492,HHS Region 05,Rural,Female,Nephritis,12.8,0.2
493,HHS Region 06,Urban,Male,Nephritis,19.4,0.2
494,HHS Region 06,Rural,Male,Nephritis,21.5,0.4
495,HHS Region 06,Urban,Female,Nephritis,14.3,0.2
496,HHS Region 06,Rural,Female,Nephritis,16.7,0.3
497,HHS Region 07,Urban,Male,Nephritis,18.1,0.4
498,HHS Region 07,Rural,Male,Nephritis,16.5,0.5
499,HHS Region 07,Urban,Female,Nephritis,12.3,0.3
500,HHS Region 07,Rural,Female,Nephritis,12.5,0.3
501,HHS Region 08,Urban,Male,Nephritis,12.9,0.4
502,HHS Region 08,Rural,Male,Nephritis,10.8,0.5
503,HHS Region 08,Urban,Female,Nephritis,8.3,0.3
504,HHS Region 08,Rural,Female,Nephritis,8.5,0.4
505,HHS Region 09,Urban,Male,Nephritis,9,0.1
506,HHS Region 09,Rural,Male,Nephritis,12.6,0.7
507,HHS Region 09,Urban,Female,Nephritis,6.1,0.1
508,HHS Region 09,Rural,Female,Nephritis,8.4,0.5
509,HHS Region 10,Urban,Male,Nephritis,8.6,0.3
510,HHS Region 10,Rural,Male,Nephritis,8.6,0.5
511,HHS Region 10,Urban,Female,Nephritis,5.9,0.2
512,HHS Region 10,Rural,Female,Nephritis,6.7,0.4
