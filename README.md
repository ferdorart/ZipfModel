# zipfModeling
- ZipfModeling is an expertise model to identify expert developers based on how they write code. <br />
- With "Tokenizer", you can tokenize the content of python code into the AST nodes of source code. <br />
- With "ZipfModeling_syn", you can fit a probability distribution with Zipf's law.<br />
- With "Model_train_realdt", you can build a feature-based expertise model. Also, it shows how to build different baselines to compare the performance of your expertise model.<br />
- We generate a labeled synthetic dataset by resampling real data. This dataset contains 1200 developers in two categories of "Expert" and "Novice". With this data you can explore the validity of expertise models based on the content of programming code. <br />
-  "Dataset" contains raw dataset which is extracted from GitHub repositories. It contains these features:<br />
. 'commit_ID','Author', 'Authored_Date','email','msg','Commiter','committer_date', 'project_path','Commit_before', 'Commit_after','diff','Added_LOC','Removed_LOC', 'Num_LOC'<br />
   
