1)Input data download address：https://github.com/GALI17/experiment-data
2)Clustering: Run main.m with Matlab, and pay attention to modify the filepath, that is, the path of the phenotype data p.
3)Preprocessing (see the “readme” in Data_F):
a.Execute CreatFiles.java in the Data_F project to generate empty folders to use.
b.Execute Test_2.java and S_Test_2.java in the Data_F project to generate the input data of PSO_F.
4)Mining logical expressions: (see the “readme” in PSO_F) Execute the program in PSO_F.

Results processing and evaluation:
1)Get the final result: execute finalRes.java in Assessment_F.
2)Evaluate Type I Error and Type II error : (see “readme” in Assessment_F) execute countError_P.java and countError_S.java in Assessment_F.
(The above code and result download address: https://github.com/GALI17/Assessment_F)
3)Similarity evaluation: (see the “readme”in LogicSimilarity_F) execute the program in LogicSimilarity_F.
(Code and result download address: https://github.com/GALI17/LogicSimilarity_F)
