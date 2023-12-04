# securityandprivacy2024

This is the artifact of the research paper, Benchmarking Deep Learning Fuzzers, submitted to IEEE Security and Privacy 2024. Please note that we have taken careful steps to protect the anonymity of the replication package.

## About

In recent years, the practice of fuzzing Deep Learning (DL) libraries has gathered significant attention in the software engineering community. Many DL fuzzers have been proposed to test DL APIs via the generation of malformed inputs. Although most of these fuzzers have been demonstrated to be effective in detecting bugs and outperforming their respective prior work in different bugs, there remains a gap in benchmarking these DL fuzzers regarding their effectiveness against ground-truth real-world bugs in DL libraries. Since the existing comparisons among these DL fuzzers mainly focus on comparing bugs detected by them, they cannot provide a direct, in-depth evaluation of different DL fuzzers.In this work, we set out to conduct the first evaluation of state-of-the-art DL fuzzers against real-world bugs. Specifically, we first manually created an extensive DL bug benchmark dataset, which includes 412 real-world DL bugs gathered from PyTorch and TensorFlow libraries that are detectable by fuzzing, i.e., can be triggered by malformed inputs. Then we apply six state-of-the-art DL fuzzers, i.e., FreeFuzz, DeepRel, NablaFuzz, DocTer, TitanFuzz, and AtlasFuzz, on the curated benchmark dataset by following their instructions. We find that these fuzzers can only detect 3.1\% (13 out of 412) unique real-world bugs in our benchmark dataset. Our analysis further pinpoints three prevailing factors that impact the effectiveness of these fuzzers in identifying real-world bugs. These findings present opportunities to improve the performance of the fuzzers in future work. Overall, this work complements prior studies on DL fuzzers with an extensive performance evaluation and provides a benchmark for future DL library fuzzing studies.

## Data
All of our data is available [here](https://docs.google.com/spreadsheets/d/17g3ierEWEoJLqeeeLXZhJ1nBYjKxSY_aTG9B4D3xC98/edit?usp=sharing).

## Replication

To replication all figures and tables, please follow the instructions in [here](https://colab.research.google.com/drive/1TqiMSshyL3B86NHGMmjrwqEgTv3XbYym?usp=sharing).
