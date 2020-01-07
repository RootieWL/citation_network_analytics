# citation_network_analytics [Still a Work-In-Progress]
Graph Network Analytics (Implementation in Scala, Python)

The dataset is obtained from https://www.aminer.cn/aminernetwork
It includes paper information, paper citation, author information and author collaboration. 

- Aminer-Paper.rar : 2,092,356 papers and 8,024,869 citations between them 
- Aminer-Author.zip : 1,712,433 authors
- Aminer-Coauthor.zip: 4,258,615 collaborations

A variery of methods (Topology Features, Community Features and Node Features) are being used to create a reliable predictive model that recommends potential research groups. 

Firstly, topology features will be used to perform a performance benchmark on the predictive capability of the machine learning model. 

Next, research groups detected using community detection (triangle count, label propagtion, louvain modularity), will be used as features to enhance the prediction model.
