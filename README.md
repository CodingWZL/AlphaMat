# AlphaMat
AlphaMat is committed to promoting the development of materials informatics together with the existing toolkits and contributing to the implementation of AI for Science.
![1](https://github.com/CodingWZL/AlphaMat/assets/104205506/1ce4aeed-d447-4b1e-9366-c2e17c88a4c7)

# Installation
Step 1: Create the enviornment

-- conda create -name my_alphamat python=3.9

Step 2: Activate the envionment

-- source (or conda) activate my_alphamat

Step 3: Go to the directory

-- cd installation

Step 4: Install the third-party libraries

-- pip install -re requirements.txt

Step 5: Run AlphaMat

-- cd ..

-- ./AlphaMat

Step 6: Set the .bashrc

-- vi ~/.bashrc 

on the last line, write:

-- export PATH="/XXX/XXX/.../AlphaMat/:$PATH"

-- source ~/.bashrc

Setp 7: Check

-- which AlphaMat

# Tutorials
More tutorials can be found in our group website: http://www.aimslab.cn/

# Notes
More simply, "environment.yaml" file provides all the installation dependencies.
Please note that Due to the iterative update of dependencies, many versions are incompatible with each other.
You can choose to install them separately.

If you want to implement more functions (which may not be in the current version), please contact us (sjtuaimslab@outlook.com) and we'll help you with the development.

# Citing
If you find AlphaMat useful to you, please cite:

Zhilong Wang, An Chen, Kehao Tao, Junfei Cai, Yanqiang Han, Jing Gao, Simin Ye, Shiwei Wang, Imran Ali, Jinjin Li. AlphaMat: a material informatics hub connecting data, features, models and applications. npj Computational Materials 9, 130 (2023).
https://doi.org/10.1038/s41524-023-01086-5

# References:
[1] Yanqiang Han, Imran Ali, Zhilong Wang, Junfei Cai, Sicheng Wu, Jiequn Tang, Lin Zhang, Jiahao Ren, Rui Xiao, Qianqian Lu, Lei Hang, Hongyuan Luo, Jinjin Li*. Machine learning accelerates quantum mechanics predictions of molecular crystals. Physics Reports 934, 3, 1-71 (2021).
https://doi.org/10.1016/j.physrep.2021.08.002

[2] Zhilong Wang, Yanqiang Han, Junfei Cai, An Chen, Jinjin Li*. Vision for energy material design: A roadmap for integrated data-driven modeling. Journal of Energy Chemistry 71, 56-62 (2022).
https://doi.org/10.1016/j.jechem.2022.03.052


