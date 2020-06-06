# Graphs with non-overlapping communities
Collection of graphs with **non-overlapping** communities and ground truth partition.
All graphs are transformed into GML format, labels are kept in "gt" attribute. 

| | family | name | n_nodes | n_edges | n_classes |
| --- | --- | --- | --- | --- | --- |
0 |  | [as](https://github.com/altsoph/community_loglike): **AS Internet topology** <br> AS Internet topology of June 2009 extracted from data collected by the archipelago active measurement infrastructure developed by Cooperative Association for Internet Data Analysis <br> Marián Boguná at al. Sustaining the internet with hyperbolic mapping (2010) | 23752 | 58416 | 176
1 |  | [citeseer](http://konect.uni-koblenz.de/networks/citeseer): **CiteSeer** <br> Citation network extracted from the CiteSeer digital library. Nodes are publications and the directed edges denote citations. <br> Kurt Bollacker at al. CiteSeer: An autonomous Web agent for automatic retrieval and identification of interesting publications (1998) | 3327 | 4676 | 6
2 | cora | [cora](https://relational.fit.cvut.cz/dataset/CORA): **Cora Citation Network** <br> The original paper describes CoRA dataset with 2708 nodes. <br> Sen, Prithviraj, et al. Collective classification in network data (2008) | 2708 | 5278 | 7
3 | cora | [cora_full](https://github.com/altsoph/community_loglike): **Cora Citation Network** <br> Nodes represent scientific papers. An edge between two nodes indicates that the left node cites the right node. <br> Lovro Šubelj and Marko Bajec. Model of complex networks based on citation dynamics (2013) | 23166 | 89157 | 70
4 | cora_full subset | Artificial_Intelligence | 4900 | 13217 | 11
5 | cora_full subset | Artificial_Intelligence__Machine_Learning | 3445 | 10761 | 7
6 | cora_full subset | Data_Structures__Algorithms_and_Theory | 1937 | 4457 | 9
7 | cora_full subset | Databases | 1046 | 3186 | 7
8 | cora_full subset | Encryption_and_Compression | 864 | 1995 | 3
9 | cora_full subset | Hardware_and_Architecture | 763 | 1644 | 7
10 | cora_full subset | Human_Computer_Interaction | 1107 | 2385 | 5
11 | cora_full subset | Information_Retrieval | 457 | 1157 | 4
12 | cora_full subset | Networking | 1249 | 4022 | 4
13 | cora_full subset | Operating_Systems | 2176 | 8731 | 4
14 | cora_full subset | Programming | 3109 | 10564 | 9
15 |  | [dolphins](http://www-personal.umich.edu/~mejn/netdata/): **Dolphin social network** <br> An undirected social network of frequent associations between 62 dolphins in a community living off Doubtful Sound, New Zealand. <br> David Lusseau at al. The bottlenose dolphin community of Doubtful Sound features a large proportion of long-lasting associations (2003) | 62 | 159 | 2
16 |  | [eu-core](https://snap.stanford.edu/data/email-Eu-core.html): **email-Eu-core network** <br> The network was generated using email data from a large European research institution <br> Jure Leskovec at al. Graph evolution: Densification and shrinking diameters (2007) | 1005 | 16706 | 42
17 |  | [eurosis](https://gephi.org/gexf/format/datasets.html): EuroSiS web mapping study <br> Mapping interactions between Science in Society actors on the Web of 12 European countries. | 1285 | 7524 | 13
18 |  | [football](http://www-personal.umich.edu/~mejn/netdata/): **American College football** <br> Network of American football games between Division IA colleges during regular season Fall 2000. <br> Mark EJ Newman and Michelle Girvan. Finding and evaluating community structure in networks (2004) | 115 | 613 | 12
19 |  | [karate](http://www-personal.umich.edu/~mejn/netdata/): **Zachary's karate club** <br> Social network of friendships between 34 members of a karate club at a US university in the 1970s. <br> W. W. Zachary, An information flow model for conflict and fission in small groups (1977) | 34 | 78 | 2
20 | newsgroup | news_2cl1 <br> Confusion graphs generated from the Newsgroup 20 dataset <br> Yen, Luh, et al. Graph nodes clustering based on the commute-time kernel (2007) | 400 | 33854 | 2
21 | newsgroup | news_2cl2 | 398 | 21480 | 2
22 | newsgroup | news_2cl3 | 399 | 36527 | 2
23 | newsgroup | news_3cl1 | 600 | 70591 | 3
24 | newsgroup | news_3cl2 | 598 | 68201 | 3
25 | newsgroup | news_3cl3 | 595 | 64169 | 3
26 | newsgroup | news_5cl1 | 998 | 176962 | 5
27 | newsgroup | news_5cl2 | 999 | 164452 | 5
28 | newsgroup | news_5cl3 | 997 | 155618 | 5
29 | newsgroup_0.1 <br> Binarized weights with threshold 0.1 | news_2cl1_0.1 | 398 | 2634 | 2
30 | newsgroup_0.1 | news_2cl2_0.1 | 398 | 2455 | 2
31 | newsgroup_0.1 | news_2cl3_0.1 | 398 | 3347 | 2
32 | newsgroup_0.1 | news_3cl1_0.1 | 599 | 5129 | 3
33 | newsgroup_0.1 | news_3cl2_0.1 | 598 | 5041 | 3
34 | newsgroup_0.1 | news_3cl3_0.1 | 595 | 4557 | 3
35 | newsgroup_0.1 | news_5cl1_0.1 | 998 | 11525 | 5
36 | newsgroup_0.1 | news_5cl2_0.1 | 999 | 10194 | 5
37 | newsgroup_0.1 | news_5cl3_0.1 | 997 | 9791 | 5
38 | | [polblogs](http://www-personal.umich.edu/~mejn/netdata/): **Political blogs** <br> A directed network of hyperlinks between weblogs on US politics, recorded in 2005 by Adamic and Glance. <br> Lada A Adamic and Natalie Glance. The political blogosphere and the 2004 US election: divided they blog (2005) | 1490 | 19025 | 2
39 | | [polbooks](http://www-personal.umich.edu/~mejn/netdata/): **Books about US politics** <br> A network of books about US politics published around the time of the 2004 presidential election and sold by the online bookseller Amazon.com. Edges between books represent frequent copurchasing of books by the same buyers. <br> Mark EJ Newman. Modularity and community structure in networks (2006) <br> V. Krebs, unpublished, http://www.orgnet.com/ | 105 | 441 | 3
40 | sp_school | [sp_school_day_1](http://www.sociopatterns.org/datasets/primary-school-cumulative-networks/): **SocioPatterns: Primary school day 1** <br> Primary School: face-to-face proximity between students and teachers. <br> Juliette Stehlé at al. High-Resolution Measurements of Face-to-Face Contact Patterns in a Primary School (2011) | 236 | 5899 | 11
41 | sp_school | [sp_school_day_2](http://www.sociopatterns.org/datasets/primary-school-cumulative-networks/): **SocioPatterns: Primary school day 2** | 238 | 5539 | 11

## Citation

If you find this repository useful for you, please also consider to cite our paper:

```
@inproceedings{ivashkin2016logarithmic,
  title={Do logarithmic proximity measures outperform plain ones in graph clustering?},
  author={Ivashkin, Vladimir and Chebotarev, Pavel},
  booktitle={International Conference on Network Analysis},
  pages={87--105},
  year={2016},
  organization={Springer}
}
```