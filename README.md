# community-graphs
Collection of graphs with **non-overlapped** communities and ground truth partition.
All graphs are transformed into GML format, labels are kept in "gt" attribute. 

| | family | name | n_nodes | n_edges | n_classes | description | citation
| --- | --- | --- | --- | --- | --- | --- | --- |
0 |  | [as](https://github.com/altsoph/community_loglike) <br> AS Internet topology | 23752 | 58416 | 176 | AS Internet topology of June 2009 extracted from data collected by the archipelago active measurement infrastructure developed by Cooperative Association for Internet Data Analysis | Marián Boguná, Fragkiskos Papadopoulos, and Dmitri Krioukov. 2010. Sustaining the internet with hyperbolic mapping. Nature communications 1 (2010), 62
1 |  | [citeseer](http://konect.uni-koblenz.de/networks/citeseer) <br> CiteSeer | 3327 | 4676 | 6 | Citation network extracted from the CiteSeer digital library. Nodes are publications and the directed edges denote citations. | Kurt Bollacker, Steve Lawrence, and C. Lee Giles. CiteSeer: An autonomous Web agent for automatic retrieval and identification of interesting publications. In Proc. Int. Conf. on Autonomous Agents, pages 116--123, 1998.
2 | cora | [cora](https://relational.fit.cvut.cz/dataset/CORA) <br> Cora Citation Network | 2708 | 5278 | 7 | The original paper describing CoRA dataset with 2708 nodes: Collective Classification in Network Data | Sen, Prithviraj, et al. "Collective classification in network data." AI magazine 29.3 (2008): 93-93.
3 | cora | [cora_full](https://github.com/altsoph/community_loglike) <br> Cora Citation Network | 23166 | 89157 | 70 | Nodes represent scientific papers. An edge between two nodes indicates that the left node cites the right node. | Lovro Šubelj and Marko Bajec. 2013. Model of complex networks based on citation dynamics. In Proceedings of the 22nd international conference on World Wide Web. ACM, 527–530
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
15 |  | [dolphins](http://www-personal.umich.edu/~mejn/netdata/) <br> Dolphin social network | 62 | 159 | 2 | An undirected social network of frequent associations between 62 dolphins in a community living off Doubtful Sound, New Zealand. | David Lusseau, Karsten Schneider, Oliver J Boisseau, Patti Haase, Elisabeth Slooten, and Steve M Dawson. 2003. The bottlenose dolphin community of Doubtful Sound features a large proportion of long-lasting associations. Behavioral Ecology and Sociobiology 54, 4 (2003), 396–405.
16 |  | [eu-core](https://snap.stanford.edu/data/email-Eu-core.html) <br> email-Eu-core network | 1005 | 16706 | 42 | The network was generated using email data from a large European research institution| Jure Leskovec, Jon Kleinberg, and Christos Faloutsos. 2007. Graph evolution: Densification and shrinking diameters. ACM Transactions on Knowledge Discovery from Data (TKDD) 1, 1 (2007), 2
17 |  | [eurosis](https://gephi.org/gexf/format/datasets.html) <br> EuroSiS web mapping study | 1285 | 7524 | 13
18 |  | [football](http://www-personal.umich.edu/~mejn/netdata/) <br> American College football | 115 | 613 | 12 | Network of American football games between Division IA colleges during regular season Fall 2000. | Mark EJ Newman and Michelle Girvan. 2004. Finding and evaluating community structure in networks. Physical review E 69, 2 (2004), 026113
19 |  | [karate](http://www-personal.umich.edu/~mejn/netdata/) <br> Zachary's karate club | 34 | 78 | 2 | Social network of friendships between 34 members of a karate club at a US university in the 1970s. | W. W. Zachary, An information flow model for conflict and fission in small groups, Journal of Anthropological Research 33, 452-473 (1977).
20 | newsgroup | news_2cl_1 | 400 | 33854 | 2 | Confusion graphs generated from the Newsgroup 20 dataset | Yen, Luh, et al. "Graph nodes clustering based on the commute-time kernel." Pacific-Asia Conference on Knowledge Discovery and Data Mining. Springer, Berlin, Heidelberg, 2007.
21 | newsgroup | news_2cl_2 | 398 | 21480 | 2
22 | newsgroup | news_2cl_3 | 399 | 36527 | 2
23 | newsgroup | news_3cl_1 | 600 | 70591 | 3
24 | newsgroup | news_3cl_2 | 598 | 68201 | 3
25 | newsgroup | news_3cl_3 | 595 | 64169 | 3
26 | newsgroup | news_5cl_1 | 998 | 176962 | 5
27 | newsgroup | news_5cl_2 | 999 | 164452 | 5
28 | newsgroup | news_5cl_3 | 997 | 155618 | 5
29 | newsgroup_0.1 | news_2cl1_0.1 | 398 | 2634 | 2 | Binarized weights on threshold 0.1
30 | newsgroup_0.1 | news_2cl2_0.1 | 398 | 2455 | 2
31 | newsgroup_0.1 | news_2cl3_0.1 | 398 | 3347 | 2
32 | newsgroup_0.1 | news_3cl1_0.1 | 599 | 5129 | 3
33 | newsgroup_0.1 | news_3cl2_0.1 | 598 | 5041 | 3
34 | newsgroup_0.1 | news_3cl3_0.1 | 595 | 4557 | 3
35 | newsgroup_0.1 | news_5cl1_0.1 | 998 | 11525 | 5
36 | newsgroup_0.1 | news_5cl2_0.1 | 999 | 10194 | 5
37 | newsgroup_0.1 | news_5cl3_0.1 | 997 | 9791 | 5
38 | | [polblogs](http://www-personal.umich.edu/~mejn/netdata/) <br> Political blogs | 1490 | 19025 | 2 | A directed network of hyperlinks between weblogs on US politics, recorded in 2005 by Adamic and Glance. | Lada A Adamic and Natalie Glance. 2005. The political blogosphere and the 2004 US election: divided they blog. In Proceedings of the 3rd international workshop on Link discovery. ACM, 36–43
39 | | [polbooks](http://www-personal.umich.edu/~mejn/netdata/) <br> Books about US politics | 105 | 441 | 3 | A network of books about US politics published around the time of the 2004 presidential election and sold by the online bookseller Amazon.com. Edges between books represent frequent copurchasing of books by the same buyers. | Mark EJ Newman. 2006. Modularity and community structure in networks. Proceedings of the national academy of sciences 103, 23 (2006), 8577–8582; V. Krebs, unpublished, http://www.orgnet.com/
40 | sp_school | [sp_school_day_1](http://www.sociopatterns.org/datasets/primary-school-cumulative-networks/) <br> SocioPatterns: Primary school day 1 | 236 | 5899 | 11 | Primary School: face-to-face proximity between students and teachers. | Juliette Stehlé at al. High-Resolution Measurements of Face-to-Face Contact Patterns in a Primary School. PLOS ONE 6(8): e23176 (2011). doi:10.1371/journal.pone.0023176
41 | sp_school | [sp_school_day_2](http://www.sociopatterns.org/datasets/primary-school-cumulative-networks/) <br> SocioPatterns: Primary school day 2 | 238 | 5539 | 11

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