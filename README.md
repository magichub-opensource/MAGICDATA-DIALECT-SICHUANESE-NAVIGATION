# MAGICDATA-DIALECT-SICHUANESE-NAVIGATION: Sichuan–Chongqing Dialect Navigation Speech Dataset

Magic Data has released the MAGICDATA-DIALECT-SICHUANESE-NAVIGATION Sichuan–Chongqing dialect navigation speech recognition dataset on the MagicHub.com, for developers, researchers, and speech technology practitioners.

## Dataset Introduction

The dataset contains 32.5 hours of audio and targets Chinese dialect automatic speech recognition (ASR) in navigation, ride-hailing, and travel-inquiry scenarios. Centered on Sichuan–Chongqing accent/dialect speech, it comprises speech content designed around real travel intents, covering common interactions such as route origin and destination descriptions, vehicle-type selection, ride booking, platform promotions, and order confirmation.

The dataset is suitable for evaluating the transcription accuracy, domain-keyword recognition, and accent robustness of speech recognition systems on Sichuan-dialect navigation speech. Compared with general read-speech corpora, navigation-domain text contains a large number of place names, travel-service terms, and natural spoken expressions, and therefore reflects more directly the practical recognition challenges faced by in-car voice assistants, map navigation, ride-hailing platforms, and local-life services.

## Dataset Overview

- **Data type:** Automatic speech recognition (ASR) 
- **Language:** Chinese dialect/accent
- **Total duration:** 32.5 hours
- **Total size:** 2.84 GB
- **Coverage:** 15 cities in the Sichuan–Chongqing region
- **Recording device:** Mobile phone
- **Recording environment:** Quiet indoor

![[Codex 图像 2026年8月31日 15_36_55.svg|156]]![[city-distribution.png|234]]

Figure 1: Gender distribution of dataset speakers ; Figure 2: City distribution of dataset speakers

## Data Composition

| Dataset name                                          | Primary use                                                                                                                                | Audio duration | File size | Coverage                                                                                                                                             |
| ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | -------------: | --------: | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TRAININGSET   | Model development, parameter tuning, validation/evaluation, and error analysis for speech recognition on Sichuan-dialect navigation speech |       13 hours |   1.14 GB | 12 cities in the Sichuan–Chongqing region: Chengdu, Chongqing, Leshan, Yibin, Luzhou, Zigong, Neijiang, Ziyang, Mianyang, Nanchong, Dazhou, Guang'an |
| MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TESTSET-PART1 | Model development, parameter tuning, validation/evaluation, and error analysis for speech recognition on Sichuan-dialect navigation speech |       13 hours |   1.12 GB | 12 cities in the Sichuan–Chongqing region: Chengdu, Chongqing, Leshan, Yibin, Luzhou, Zigong, Neijiang, Ziyang, Mianyang, Nanchong, Dazhou, Guang'an |
| MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TESTSET-PART2 | Model development, parameter tuning, validation/evaluation, and error analysis for speech recognition on Sichuan-dialect navigation speech |      6.5 hours |    579 MB | 6 cities in Sichuan: Chengdu, Zigong, Neijiang, Bazhong, Guangyuan, Suining                                                                          |

## Applications

- Testing and benchmark evaluation of Chinese ASR models for Sichuan dialect/accent.
- Scenario-based recognition evaluation of navigation, in-car voice assistant, and ride-hailing voice interaction systems.
- Analysis of recognition performance on navigation-domain keywords such as place names, vehicle types, times, and promotions.
- Validation of the voice interaction experience for Sichuan-localized intelligent mobility services.

## Audio and Annotation Format

| Item              | Specification         |
| ----------------- | --------------------- |
| Audio Parameters  | 16 kHz,16 bits,Mono   |
| File Forma        | WAV (PCM),TXT (UTF-8) |
| Speech type       | Read speech           |

## Download

The dataset is available from the MagicHub open-source community:

MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TESTSET-PART1: [https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-testset-part1/](https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-testset-part1/)

MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TESTSET-PART2: [https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-testset-part2/](https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-testset-part2/)

MAGICDATA-DIALECT-SICHUANESE-NAVIGATION-TRAININGSET: [https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-trainingset/](https://magichub.com/datasets/magicdata-dialect-sichuanese-navigation-trainingset/)

## Usage

The dataset is suitable for evaluating the transcription accuracy, domain-keyword recognition, and accent robustness of speech recognition systems on Sichuan-dialect navigation speech. Compared with general read-speech corpora, navigation-domain text contains a large number of place names, travel-service terms, and natural spoken expressions, and therefore reflects more directly the practical recognition challenges faced by in-car voice assistants, map navigation, ride-hailing platforms, and local-life services.

Before using the dataset, please read the license and data usage notes in the repository, and comply with applicable laws, regulations, and privacy protection requirements.

License: [MAGIC DATA OPEN-SOURCE LICENSE](https://magichub.com/magic-data-open-source-license/)

## Contact Us

If you have any questions or suggestions, please feel free to submit an Issue in the GitHub repository or contact us by email open@magicdatatech.com.
> [中文文档](./README_CN.md)
