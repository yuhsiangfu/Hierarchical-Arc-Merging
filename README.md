# Hierarchical-Arc-Merging (HAM) Algorithm
Our paper, a community detection algorithm using network topologies and rule-based hierarchical arc-merging strategies,  is published on PloS One website.

The url is https://doi.org/10.1371/journal.pone.0187603.

# Abstract
The authors use four criteria to examine a novel community detection algorithm: (a) effectiveness in terms of producing high values of normalized mutual information (NMI) and modularity, using well-known social networks for testing; (b) examination, meaning the ability to examine mitigating resolution limit problems using NMI values and synthetic networks; (c) correctness, meaning the ability to identify useful community structure results in terms of NMI values and Lancichinetti-Fortunato-Radicchi (LFR) benchmark networks; and (d) scalability, or the ability to produce comparable modularity values with fast execution times when working with large-scale real-world networks.

In addition to describing a simple hierarchical arc-merging (HAM) algorithm that uses network topology information, we introduce rule-based arc-merging strategies for identifying community structures. Five well-studied social network datasets and eight sets of LFR benchmark networks were employed to validate the correctness of a ground-truth community, eight large-scale real-world complex networks were used to measure its efficiency, and two synthetic networks were used to determine its susceptibility to two resolution limit problems.

Our experimental results indicate that the proposed HAM algorithm exhibited satisfactory performance efficiency, and that HAM-identified and ground-truth communities were comparable in terms of social and LFR benchmark networks, while mitigating resolution limit problems.

# Execution environment of experiments
## Hardware Setting
We used a Lenovo X230 laptop (Intel Core i5 3230M @ 2.60GHz CPU, 16 GB DDR3 RAM) with a Windows 7 Professional 64-bit SP1 OS.

## Software Setting
We used Python 3.4, NetworkX 1.9.1, Numpy 1.9.2 and Scipy 0.15.1 programming languages and packages. **Notes that Python 3.5+ will cause HAM to output in incorrect results.** This issue should be fixed in the future.

# Google Drive
Due to the file size limitation of GitHub, the HAM program can be downloaded here:
https://drive.google.com/open?id=15UFtYLyADSLldsVsKMsRS3Abg-7FU_N1

# Notification
1. We uploaded the Python codes of HAM; you are free to use them for educational purposes.
2. We uploaded the missed algorithm 1 in our paper.
3. Our coding style may not as good as you expect, but it works.
4. We are glad to hear your improvements exceed HAM.
5. Any questions please contact **yuhisnag.fu@gmail.com**.

Best regards,
Yu-Hsiang Fu 20190107 updated.
