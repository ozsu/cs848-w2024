## Weekly Schedule

| Week              | Date | Topic | Speaker | Readings | 
| :----------------: | :------: | :---- | :---- | :---- |
| 1 | 1/9 | Introduction to Disaggregated & Heterogeneous Platforms | M. Tamer Özsu | 1, 2, 3 |
| 2 | 1/16 | Introduction to Graph Processing | M. Tamer Özsu| 4, 5 |
| 3 | 1/23 | Networking infrastructure |  | 6, 7, 8, 9 |
| 4 | 1/30 | Storage disaggregation | Student 1 <br/> Student 2 | 10 <br/> 11 |
| 5 | 2/6 | Storage disaggregation |  Student 3 <br/> Student 4| 12 <br/> 13 |
| 6 | 2/13 | Storage/Memory disaggregation | Student 5 <br/> Student 6 | 14 <br/> 15 |
| 7 | 2/20 |  No class -- Reading week|  |  |
| 8 | 2/27 | Memory disaggregation | Student 7 <br/> Student 8 | 16 <br/> 17 |
| 9 | 3/5 | Memory disaggregation | Student 9 <br/> Student 10 | 18 <br/> 19 |
| 10 | 3/12 | Hardware accelerators | Student 11 <br/> Student 12 | 20 <br/> 21 |
| 11 | 3/19 | Hardware accelerators  | Student 13 <br/> Student 14  | 22 <br/> 23 |
| 12 | 3/26 |  Project presentations |  |  |
| 13 | 4/2 |  Project presentations |  |  |

## Readings

Note that all of the following are accessible from the original repositories I have linked to if you access them from the University (or use VPN into SCS if you are accessing from home).

1. R. Wang et al., [The Case for Shared-Memory Databases with RDMA-Enabled Memory Disaggregation](https://www.vldb.org/pvldb/vol16/p15-wang.pdf), _Proc. VLDB Endowment_, 2022
2. I. Blagodurov et al., [The time is ripe for disaggregated systems](https://www.sigarch.org/the-time-is-ripe-for-disaggregated-systems/). Computer Architecture Today – ACM SIGARCH Blog, 2021.
3. S. Ghandeharizadeh et al., [Disaggregated database management systems](https://doi.org/10.1007/978-3-031-29576-8_3). In _Performance Evaluation and Benchmarking_, 2023. 
4. M.T. Özsu and P. Valduriez, [Big Data Processing](https://doi.org/10.1007/978-3-030-26253-2_10). In _Principles of Distributed Database Systems_. Springer, 2022. (Focus on Section 10.4)
5. M.T. Özsu and P. Valduriez, [Big Data Processing](https://doi.org/10.1007/978-3-030-26253-2_10). In _Principles of Distributed Database Systems_. Springer, 2022. (Focus on Section 12.6)
6. R. Recio, [A Tutorial of the RDMA Model](https://www.hpcwire.com/2006/09/15/a_tutorial_of_the_rdma_model-1/), HPC Wire, 2006.
7. InfiniBand Trade Organization, [Enabling the Modern Data Center – RDMA for the Enterprise](https://www.infinibandta.org/wp-content/uploads/2019/05/IBTA_WhitePaper_May-20-2019.pdf), 2019.
8. A. Lerner et al., [Databases on modern networks: A decade of research that now comes into practice](https://doi.org/10.14778/3611540.3611579). _Proc. VLDB Endowment_, 16(12):3894–3897, 2023.
9. D. Gouk et al., [Direct access, High-Performance memory disaggregation with DirectCXL](https://www.usenix.org/conference/atc22/presentation/gouk). In _Proc. USENIX 2022 Annual Technical Conf._, pages 287–294, 2022. 
10. A. Verbitski et al., [Amazon Aurora: Design Considerations for High Throughput Cloud-Native Relational Databases](https://doi.org/10.1145/3035918.3056101), In _Proc. ACM SIGMOD Int. Conf. Management of Data_, pages 1041–1052, 2017.
11. P. Antonopoulos, et al., [Socrates: The New SQL Server in the Cloud](https://dl.acm.org/doi/10.1145/3299869.3314047), In _Proc. ACM SIGMOD Int. Conf. Management of Data_, pages 1743–1756, 2019.
12. W. Cao et al., [PolarFS: An Ultra-low Latency and Failure Resilient Distributed File System for Shared Storage Cloud Database](https://doi.org/10.14778/3229863.3229872), _Proc. VLDB Endowment_, 11(12): 1849-1962, 2018.
13. M. Vuppalapati et al., [Building An Elastic Query Engine on Disaggregated Storage](https://www.usenix.org/conference/nsdi20/presentation/vuppalapati), In _Proc. 17th USENIX Symp. on Networked Systems Design & Implementation,_ pages 449-462, 2020.
14. A. Agiwal et al., [Napa: Powering Scalable Data Warehousing with Robust Query Performance at Google](https://doi.org/10.14778/3476311.3476377), 14(12): 2986-2998, 2021
15. Y, Shan et al., [LegoOS: A Disseminated, Distributed OS for Hardware Resource Disaggregation](https://www.usenix.org/conference/osdi18/presentation/shan), In _Proc. 14th USENIX Symp. on Operating System Design and Implementation_, pages 69-87, 2018.
16. Y. Zhang et al., [Towards Cost-Effective and Elastic Cloud Database Deployment via Memory Disaggregation](https://doi.org/10.14778/3467861.3467877), _Proc. VLDB Endowment_, 14(10): 1900 - 1912, 2021.
17. Wei Cao et al., [PolarDB Serverless: A Cloud Native Database for Disaggregated Data Centers](https://doi.org/10.1145/3448016.3457560), In _Proc. ACM SIGMOD Int. Conf. Management of Data_, pages 2477–2489, 2021.
18. Q. Zhang et al., [Understanding the Effect of Data Center Resource Disaggregation on Production DBMSs](https://doi.org/10.14778/3397230.3397249), _Proc. VLDB Endowment_, 13(9): 1568-1581, 2020.
19. Q. Zhang et al., [Redy: Remote Dynamic Memory Cache](https://doi.org/10.14778/3503585.3503587), _Proc. VLDB Endowment_, 15(4): 766 - 779, 2022.
20. C. Lutz et al., [Pump Up the Volume: Processing Large Data on GPUs with Fast Interconnects](https://doi.org/10.1145/3318464.3389705), In _Proc. ACM SIGMOD Int. Conf. Management of Data_, pages 1633–1649, 2020.
21. L. Hu et al., [GAMMA: A Graph Pattern Mining Framework for Large Graphs on GPU](https://ieeexplore.ieee.org/document/10184586), In _IEEE 39th International Conference on Data Engineering_, 2023.
22. xxx
23. xxx
 
