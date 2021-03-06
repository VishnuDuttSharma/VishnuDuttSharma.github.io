---
title: "Poetry to Prose Conversion in Sanskrit as a Linearisation Task: A Case for Low-Resource Languages"
collection: publications
permalink: https://www.aclweb.org/anthology/P19-1111/
excerpt: 'Amrith Krishna, <b>Vishnu Dutt Sharma</b>, Bishal Santra, Aishik Chakraborty, Pavankumar Satuluri, Pawan Goyal (2019). &quot;Poetry to Prose Conversion in Sanskrit as a Linearisation Task: A Case for Low-Resource Languages.&quot; <br /><i>Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019)</i>'
# date: 2009-10-01
# :venue: ''
paperurl: 'https://www.aclweb.org/anthology/D18-1276.pdf'
# citation: 'Vikas Reddy, Amrith Krishna, Vishnu Sharma, Prateek Gupta, Vineeth M R, Pawan Goyal. (2009). &quot;Building a Word Segmenter for Sanskrit Overnight.&quot; <i>Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018)</i>.'
---

[Download paper here](https://www.aclweb.org/anthology/D18-1276.pdf)

**Abstract:**
The word ordering in a Sanskrit verse is often not aligned with its corresponding prose order. Conversion of the verse to its corresponding prose helps in better comprehension of the construction. Owing to the resource constraints, we formulate this task as a word ordering (linearisation) task. In doing so, we completely ignore the word arrangement at the verse side. kāvya guru, the approach we propose, essentially consists of a pipeline of two pretraining steps followed by a seq2seq model. The first pretraining step learns task-specific token embeddings from pretrained embeddings. In the next step, we generate multiple possible hypotheses for possible word arrangements of the input %using another pretraining step. We then use them as inputs to a neural seq2seq model for the final prediction. We empirically show that the hypotheses generated by our pretraining step result in predictions that consistently outperform predictions based on the original order in the verse. Overall, kāvya guru outperforms current state of the art models in linearisation for the poetry to prose conversion task in Sanskrit.

Amrith Krishna, <b>Vishnu Dutt Sharma</b>, Bishal Santra, Aishik Chakraborty, Pavankumar Satuluri, Pawan Goyal (2019). &quot;Poetry to Prose Conversion in Sanskrit as a Linearisation Task: A Case for Low-Resource Languages.&quot; <br /><i>Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019)</i>'
