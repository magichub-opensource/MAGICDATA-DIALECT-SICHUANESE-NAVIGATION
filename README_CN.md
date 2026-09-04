> [English](./README.md)
>
> # MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-川渝方言导航语音数据集

Magic Data 现通过 [MagicHub 开源社区](https://github.com/MagicHub-io)开源MAGICDATA-DIALECT-SICHUANESE-NAVIGATION川渝方言导航语音识别数据集，面向开发者、研究人员和语音技术从业者开放使用。

# 数据集介绍##
数据集总时长32.5小时，面向导航、打车与出行问询场景的中文方言语音识别（ASR）场景。数据集以川渝地区口音/方言表达为主要对象，围绕真实出行意图设计语音内容，覆盖路线出发地与目的地描述、车型选择、预约用车、平台优惠、订单确认等常见交互需求。

数据集适合用于评估语音识别系统在四川方言导航语音中的转写准确率、场景词识别能力和口音鲁棒性。相较于通用朗读语料，导航领域文本包含大量地名、出行服务词和自然口语表达，可更直接反映车载语音助手、地图导航、网约车平台与本地生活服务中的实际识别难点。

## 数据集概览

- **数据类型：** 语音识别（ASR）音频数据
- **语种：** 中文方言/口音
- **总时长：** 32.5 小时
- **总大小：** 2.84 GB
- **覆盖范围：** 川渝地区 15个城市
- **录音设备：** 手机
- **录音环境：** 安静室内

## 数据组成

| 数据集名称                                                 | 主要用途                                   |   音频时长 |    文件大小 | 覆盖区域                                            |
| ----------------------------------------------------- | -------------------------------------- | -----: | ------: | ----------------------------------------------- |
| MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TRAININGSE    | 语音识别系统在四川方言导航语音场景中的模型开发、参数调优、验证评估与错误分析 |  13 小时 | 1.14 GB | 川渝地区 12 个城市：成都、重庆、乐山、宜宾、泸州、自贡、内江、资阳、绵阳、南充、达州、广安 |
| MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TESTSET-PART1 | 语音识别系统在四川方言导航语音场景中的模型开发、参数调优、验证评估与错误分析 |  13 小时 | 1.12 GB | 川渝地区 12 个城市：成都、重庆、乐山、宜宾、泸州、自贡、内江、资阳、绵阳、南充、达州、广安 |
| MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TESTSET-PART2 | 语音识别系统在四川方言导航语音场景中的模型开发、参数调优、验证评估与错误分析 | 6.5 小时 |  579 MB | 四川地区 6 个城市：成都、自贡、内江、巴中、广元、遂宁                    |

## 应用方向

- 四川方言/口音中文ASR模型的测试与基准评估。
- 导航、车载语音助手和网约车语音交互系统的场景化识别评测。
- 地名、车型、时间、优惠活动等导航领域关键词识别效果分析。
- 面向四川本地化智能出行服务的语音交互体验验证。

## 音频与标注格式

| 项目   | 规格         |
| ---- | ---------- |
| 采样率  | 16 kHz     |
| 位深   | 16 bits    |
| 声道   | 单声道（mono）  |
| 音频格式 | WAV（PCM）   |
| 标注格式 | TXT（UTF-8） |
| 语音类型 | 朗读式语音      |

## 数据下载

该数据集可在 MagicHub 开源社区获取：

MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TESTSET-PART1：[https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-testset-part1/](https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-testset-part1/)  
MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TESTSET-PART2：[https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-testset-part2/](https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-testset-part2/)  
MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TRAININGSET：https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-trainingset/

## 使用说明

该数据集适合用于评估语音识别系统在四川方言导航语音中的转写准确率、场景词识别能力和口音鲁棒性。相较于通用朗读语料，导航领域文本包含大量地名、出行服务词和自然口语表达，可更直接反映车载语音助手、地图导航、网约车平台与本地生活服务中的实际识别难点。

使用数据集前，请阅读仓库中的许可证及数据使用说明，并遵守相关法律法规和隐私保护要求。

许可证信息：## [MAGIC DATA OPEN-SOURCE LICENSE](https://magichub.com/magic-data-open-source-license/)

## 联系我们

如有问题或建议，欢迎在 GitHub 仓库提交 Issue，或通过电子邮件 open@magicdatatech.com 联系我们。


