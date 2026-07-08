# SarcOji Test Sets

These datasets were processed using the same filtering approach as discussed for the SarcOji dataset.

## SarcOjiTest1

Compiled using three benchmark datasets viz:

1. SPIRS dataset (Shmueli, et al., 2020), X posts with the phrase being sarcastic (October, November 2019). Random English posts were scraped from X in the same time period to collect non-sarcastic records. (Initial raw compilation: 15,000 Sarcastic, 15,000 Non-Sarcastic, 30,000 Total)
2. Ptáček, et al., 2014. Posts from X randomly scraped for non-sarcastic and using #sarcasm hashtag for sarcastic posts. (Initial raw compilation: 50,000 Sarcastic, 50,000 Non-Sarcastic, 100,000 Total)
3. Riloff, et al., 2013. Posts scraped from X using #sarcastic or #sarcasm for sarcastic instances and randomly scraped posts for non-sarcastic instances. (Initial raw compilation: 35,000 Sarcastic, 140,000 Non-Sarcastic, 175,000 Total)

### Dataset Statistics
* SarcOjiTest1 has a total of **7,228** text records.
* The distribution is **52.6%** Sarcastic texts and **47.4%** Non-Sarcastic texts.

---

## SarcOjiTest2

Compiled by scraping random tweets from X (formerly Twitter) between the years 2021 and 2022. Sarcastic texts were collected using hashtags: #whatever, #not, #sarcasm, #sarcastic, #wtf, #sarcasmic, #lmao, #sarcasticmemes. Non-sarcastic texts were collected randomly. (Initial raw compilation: 7,710 Sarcastic, 20,000 Non-Sarcastic, 27,710 Total)

### Dataset Statistics
* SarcOjiTest2 has a total of **5,056** text records.
* The distribution is **25%** Sarcastic texts and **75%** Non-Sarcastic texts.

---

## Citations

Please cite the following research work:

**Thesis:**
`[Insert your thesis citation details here]`

**Journal Articles:**
```bibtex
@article{grover2024attention,
  title={An attention approach to emoji focused sarcasm detection},
  author={Grover, Vandita and Banati, Hema},
  journal={Heliyon},
  volume={10},
  number={17},
  year={2024},
  publisher={Elsevier}
}

@article{grover2026emoji,
  title={An emoji centric approach to sarcasm detection in online discourse},
  author={Grover, V and Banati, H},
  journal={Scientific Reports},
  volume={16},
  number={1},
  pages={3891},
  year={2026},
  publisher={Nature Publishing Group UK London}
}
