### Dataset: python-method

- Paper: https://arxiv.org/abs/1707.02275
- Data source: https://github.com/EdinburghNLP/code-docstring-corpus

Run the `get_data.sh` script inside the `python` directory. Once finished, we will see a pretty table summarizing the data statistics.

```
+------------------------+---------+--------+--------+---------+
| Attribute              |   Train |  Valid |   Test | Fullset |
+------------------------+---------+--------+--------+---------+
| Records                |   55538 |  18505 |  18502 |   92545 |
| Function Tokens        | 2670849 | 887331 | 882013 | 4440193 |
| Javadoc Tokens         |  525524 | 175429 | 176673 |  877626 |
| Unique Function Tokens |  159968 |  73862 |  73766 |  307596 |
| Unique Javadoc Tokens  |   27197 |  14462 |  14530 |   56189 |
| Avg. Function Length   |   48.09 |  47.95 |  47.67 |   47.98 |
| Avg. Javadoc Length    |    9.46 |   9.48 |   9.55 |    9.48 |
+------------------------+---------+--------+--------+---------+
```

**Acknowledgement**: We thank the authors of [Bolin et al., 2019](https://arxiv.org/abs/1910.05923) for sharing the preprocessed python dataset that we used in our experiments.

### Dataset: tlcodesum

- Paper: https://xin-xia.github.io/publication/ijcai18.pdf
- Data source: https://github.com/xing-hu/TL-CodeSum

Run the `get_data.sh` script inside the `java` directory. Once finished, we will see a pretty table summarizing the data statistics.

```
+------------------------+---------+---------+---------+----------+
| Attribute              |   Train |   Valid |    Test |  Fullset |
+------------------------+---------+---------+---------+----------+
| Records                |   69708 |    8714 |    8714 |    87136 |
| Function Tokens        | 8371911 | 1042466 | 1055733 | 10470110 |
| Javadoc Tokens         | 1235295 |  155876 |  153407 |  1544578 |
| Unique Function Tokens |   36202 |   15317 |   15131 |    66650 |
| Unique Javadoc Tokens  |   28047 |    9555 |    9293 |    46895 |
| Avg. Function Length   |  120.10 |  119.63 |  121.15 |   120.16 |
| Avg. Javadoc Length    |   17.72 |   17.89 |   17.60 |    17.73 |
+------------------------+---------+---------+---------+----------+
```

### Dataset: tlcodesum to SBT representation

Added by Robert.

Run the `get_data.sh` script inside the `java-sbt` directory. Once finished, we will see a pretty table summarizing the data statistics.

```
+------------------------+----------+---------+---------+----------+
| Attribute              |    Train |   Valid |    Test |  Fullset |
+------------------------+----------+---------+---------+----------+
| Records                |    69593 |    8694 |    8689 |    86976 |
| Function Tokens        | 12112822 | 1503864 | 1529499 | 15146185 |
| Javadoc Tokens         |  1214372 |  153148 |  150972 |  1518492 |
| Unique Function Tokens |    39818 |   16061 |   15965 |    71844 |
| Unique Javadoc Tokens  |    29113 |    9889 |    9591 |    48593 |
| Avg. Function Length   |   174.05 |  172.98 |  176.03 |   174.14 |
| Avg. Javadoc Length    |    17.45 |   17.62 |   17.38 |    17.46 |
+------------------------+----------+---------+---------+----------+

```


### Direct Data Download

You can directly download our experiment dataset from [here](https://drive.google.com/drive/folders/1Mx0xEPZfQzb5h0z753XV-JgoWUuxiuKZ?usp=sharing).
