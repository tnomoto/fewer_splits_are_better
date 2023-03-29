# Fewer Splits are Better

This respository contains responses collected from human participants to questions regarding the readability of split sentences, which were referred to in the paper: [**The Fewer Splits are Better: Deconstructing Readability in Sentence Splitting**](https://aclanthology.org/2022.tsar-1.1/).

The data consist of 15 columns. The following tells you what they mean. Note that each row represents a single task assigned to exactly seven people. 


| column  name | description                                            | 
| :----------: | :---------------------------------------------------- | 
| BART         | How A is generated (True if BART/False if Human)              |
| source       | source (original) sentence                             | 
| A            | source split into two                                  | 
| B            | source split into three                                | 
| AxB_A        | #votes for A in A vs. B                               | 
| AxB_B        | #votes for B in A vs. B                              | 
| AxB_NotSure  | #votes (avg) for 'not sure' in A vs. B                | 
| A_fluency    | combined ratings (1-5) people gave on the fluency of A | 
| B_fluency    | combined ratings (1-5) people gave on the fluency of B | 
| SxA_S        | #votes for S in S vs. A                               | 
| SxA_A        | #votes for A in S vs. A                               | 
| SxA_NotSure  | #votes for 'not sure' in S vs. A                      | 
| SxB_S        | #votes for S in S vs. B                               | 
| SxB_B        | #votes for B in S vs. B                               | 
| SxB_NotSure  | #votes for 'not sure' in S vs. B                      | 



## References

```bibtex
@inproceedings{nomoto-2022-fewer,
    title = "The Fewer Splits are Better: Deconstructing Readability in Sentence Splitting",
    author = "Nomoto, Tadashi",
    booktitle = "Proceedings of the Workshop on Text Simplification, Accessibility, and Readability (TSAR-2022)",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates (Virtual)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.tsar-1.1",
    pages = "1--11",
    abstract = "In this work, we focus on sentence splitting, a subfield of text simplification, primarily motivated by an unproven idea that if you divide a sentence into pieces, it should become easier to understand. Our primary goal in this paper is to determine whether this is true. In particular, we ask, does it matter whether we break a sentence into two or three? We report on our findings based on Amazon Mechanical Turk. More specifically, we introduce a Bayesian modeling framework to further investigate to what degree a particular way of splitting the complex sentence affects readability, along with a number of other parameters adopted from diverse perspectives, including clinical linguistics, and cognitive linguistics. The Bayesian modeling experiment provides clear evidence that bisecting the sentence leads to enhanced readability to a degree greater than when we create simplification by trisection.",
}


 ```
