# Bible Natural Language Processing

**Update (Sept. 2018):** I'm working on a big, new project that will provide a much better system for interacting with this kind of data. Stay tuned and feel free to [contact me](https://hightower.space/contact/) if you would like to know when this is ready.

---

This repository contains a framework for performing natural language processing on the books of the Bible.

Currently, there is only a [Jupyter](https://jupyter.org/) notebook and a zip archive with one translation in it (NASB). More will be coming soon.

In the notebook, you can specify which book of the Bible you would like to analyze and it will give output like this:

```
# NLP Analysis for Genesis (using the NASB translation)

## Sentiment

Polarity†: 0.10086

Subjectivity‡: 0.45558

## Most Common Noun Phrases in Genesis:

 * 199  -  god
 * 182  -  jacob
 * 156  -  joseph
 * 141  -  lord
 * 133  -  abraham
 * 93   -  pharaoh
 * 81   -  isaac
 * 77   -  esau
 * 77   -  egypt
 * 58   -  abram


† Polarity is measured on a scale of [-1.0, 1.0] and measures whether that language used by the author is negative, neutral, or positive.

‡ Subjectivity is measured on a scale of [0.0, 1.0] and measures how subjective the text is (0.0 being very objective; 1.0 being very subjective).
```
