# Modeling Developer Expertise with Zipf's law
- ZipfModeling is an expertise model to identify expert developers based on how they write code. <br />
![](https://github.com/ferdorart/ZipfModel/blob/main/EASE_digram.PNG)
- "Tokenizer", you can tokenize the content of python code into the AST nodes of source code and then collect the syntax patterns <br />
- "ZipfModeling_syndt", shows the probability distribution of alpha in Zipf after fitting on synthatic data.<br />
- "Model_train_realdt" and "Zipf_logLikelihood", collect syntax patterns from real projects fetched from GitHub and fit the distribution of the syntax patterns for each developer with Zipf's law.<br />
- "Zipf-Validity" explores the threat to the validity of fitting the data with the Zipf distribution.
- We generate a labeled synthetic dataset by resampling real data. This dataset contains 1200 developers in two categories of "Expert" and "Novice". With this data you can explore the validity of expertise models based on the content of programming code. <br />
-  "Dataset" contains raw real dataset which is extracted from GitHub repositories. The dataset includes following features:<br />
. 'commit_ID','Author', 'Authored_Date','email','msg','Commiter','committer_date', 'project_path','Commit_before', 'Commit_after','diff','Added_LOC','Removed_LOC', 'Num_LOC'<br />
-------------------------------------------------------------------------------------------------------------------------------------------------
## Citation
<a href="https://dl.acm.org/doi/abs/10.1145/3463274.3463343"><strong>Assessing developer expertise from the statistical distribution of programming syntax patterns</strong></a>
```
@article{,
  title={Assessing developer expertise from the statistical distribution of programming syntax patterns},
  author={Moradi Dakhel, Arghavan and C. Desmarais, Michel and Khomh, Foutse},
  Conferance={Evaluation and Assessment in Software Engineering},
  pages={90--99},
  year={2021}
}
```
