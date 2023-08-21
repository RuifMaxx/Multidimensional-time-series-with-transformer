# Multidimensional-time-series-with-transformer
Transformer/self-attention for Multidimensional time series forecasting 使用transformer架构实现多维时间预测

Rerfer to  https://github.com/oliverguhr/transformer-time-series-prediction

## Requirement

torch 1.7.0

python 3.7

matplotlib 3.4.1

numpy 1.20.2

## Dataset

After downloading data from https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014, I convert it into .xlsx file 

This is the .xlsx file (source: 'https://pan.baidu.com/s/1gyN37cM_ZI2i7OOaiaQ-_g'  password: 4iu4)

You can also download by this link:[https://docs.google.com/spreadsheets/d/1P8nIB2Ugd9AMcGlAPu3lD2yh2eAyJVh3/edit?usp=drive_link&ouid=102877252444231070619&rtpof=true&sd=true](https://docs.google.com/spreadsheets/d/1P8nIB2Ugd9AMcGlAPu3lD2yh2eAyJVh3/edit?usp=drive_link&ouid=102877252444231070619&rtpof=true&sd=true) or https://drive.google.com/file/d/13FyJqP_MVVHzqQ3G0egpglelO0G-dsEa/view?usp=drive_link

![image](https://user-images.githubusercontent.com/75245181/126475468-46964a3a-4413-49df-becb-76adff683f8d.png)

And in my code, I select 10 dims time series for modeling

## Some result

![image](https://user-images.githubusercontent.com/75245181/126475904-1b020a78-d2f9-453f-93e4-5413d44019f8.png)

![image](https://user-images.githubusercontent.com/75245181/126475965-1c5ce38f-2129-42e8-9cac-c11a7a80fcf3.png)

![image](https://user-images.githubusercontent.com/75245181/126477805-05c5d40e-4069-44c2-9d38-48d4c420c86f.png)



## 知乎

https://zhuanlan.zhihu.com/p/390193679

## Star 历史

[![Star History Chart](https://api.star-history.com/svg?repos=RuifMaxx/Multidimensional-time-series-with-transformer&type=Date)](https://star-history.com/#RuifMaxx/Multidimensional-time-series-with-transformer&Date)
