# Great ML conf papers
ML summaries revolutionized
<!--
| student name | qualities |
| ------------ | ---------- |
| John         | ![honest](https://img.shields.io/badge/honest-red) ![hard working](https://img.shields.io/badge/hard%20working-green) ![loyal](https://img.shields.io/badge/loyal-blue) |
| Rebecca      | ![loyal](https://img.shields.io/badge/loyal-blue) ![coy](https://img.shields.io/badge/coy-purple) |
-->


| Conf | Title | Released | Topics | Why you should read the paper? |   Key takeaways from the paper |
| -----|-------|----------| ----| ---- | ------- |
| ACL | [Feature-Adaptive and Data-Scalable In-Context Learning](https://arxiv.org/pdf/2405.10738) | May 2024 | In-context learning | <ul><li>A different way of making In-context learning data-scalable, i.e., how can we incorporate more and more training data for in-context learning when the context window is fixed? <li> How can we "fine-tune" In-context learning to different downstream tasks?</ul> | <ul><li>A simple solution is to use the rest of the training data (which can not be fit into the context) for training a feature adaptor that takes in input the final hidden representation from the transformer and outputs the required output <li> This only works on classification tasks yet. </ul> |
| iCML 2024 | [Bottleneck-Minimal Indexing for Generative Document Retrieval](https://arxiv.org/pdf/2405.10974) | May 2024 | IR, Generative IR, ML Theory | <ul><li>To learn more on an emerging segment in IR, GDR or generative document retrieval where the goal is to generate indices (of the documents) given a query (and not the documents themselves! Sounds crazy but research has been on-going for last couple of years) <li>To learn why we need to consider the distribution of query space to obtain optimal indexing for GDR problem</ul> |  <ul><li>Need to read more!</ul> |
