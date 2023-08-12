# Rubick

Rubick is an automata-based fuzz driver generation prototype. It is published in the [work published in Usenix Security 2023](https://www.usenix.org/conference/usenixsecurity23/presentation/zhangcen).

This repository contains both the source code and the setting used in evaluation of Rubick. For more usage, please see the README.md in each sub-directory.

# File Architectures

```
source     -> you can find all related source code of Rubick including crawling, usage automaton learning, and final fuzz driver generation
evaluation -> you can directly get the generated fuzz drivers and settings used in paper evaluation
```

# Citation

```
@article{zhangautomata,
  title={Automata-Guided Control-Flow-Sensitive Fuzz Driver Generation},
  author={Zhang, Cen and Li, Yuekang and Zhou, Hao and Zhang, Xiaohan and Zheng, Yaowen and Zhan, Xian and Xie, Xiaofei and Luo, Xiapu and Li, Xinghua and Liu, Yang and others}
}
```
