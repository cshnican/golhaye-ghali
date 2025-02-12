# Golhaye Ghali: a dataset for profanity constructions in Farsi and Mazani

## What is this dataset for?
This repository explores profanity constructions in Farsi and Mazani, focusing on idiomatic expressions rather than isolated swear words. While existing resources primarily list individual profanities, this project seeks to document multi-word constructions that convey offensive, humorous, or metaphorical meanings in everyday speech.

## Why does it matter?
Language is believed to be largely compositional: the meaning of multi-word sequences can be mostly composed and deduced from the meaning of each word. For example, the meaning of "a white tower" is a tower that is white, which is a composition of its element, "white" and "tower". Compositionality allows speakers to generate complex meaning from a relatively smaller set of basic units, which is good, because speakers just need to memorize the meaning of each individual word, along with the rules to compose them together. On the other hand, if language is largely not-compositional, then speakers need to memorize 3 unrelated utterances for "book", "my book", and "Can I have my book?", which will be a nightmare for people using the language.

However, not everything about language is compositional. A counterexample is *idioms* in English: the sentence "put yourself in other people's shoes" doesn't mean you are actually wearing other people's shoes, as its individual words combined together will suggest. Instead, this sentence means to think in someone else's perspective. Another counterexample is some syntactic structures in English: "I am *into* laiko" does not mean I am physically into laiko music, as, again, its individual words combined together will suggest. Instead, it means I *like* laiko music.

Profanity constructions, which this dataset offers, is another example: words (usually vulgar) composed together mean something completely different from their individual parts. In English, the examples are "bullshit" vs. "batshit" vs. "horseshit" - they don't refer to the defecation of different animals. Rather, they refer to "nonsense", "something crazy", and "nonsense on a even deeper level".

Why is this the case? When is language not-compositional? How do these seemingly arbitraily meanings get assigned to these collection of words? To address these questions, in this dataset, we hope we can provide future researchers with data points to potentially draw inferences from. We choose Farsi and Mazani because they seem (to the judgement of curators) to be understudied languages with rich such constructions. 

Another theoretical value of this dataset is that it might offer a probe of how languages were spoken a long time ago, since these constructions were thought to have been formed a long time ago and have survived language changes due to their sociological values (cf. Progovac, 2024). 

A third, practical contribution of this dataset is to provide literal and implied translation of Farsi and Mazani expressions in order to train better machine translators.

## Table

This dataset consists of 5 columns. The first column is the original profanity construction in Farsi or Mazani, written in the Persian script. The second column is the transliterated construction in Latin script for those who are unfamiliar with the Persian sript. The third column is the literal meaning of the construction, usually a word-by-word translation (annotation may be added later, depending on the curators' bandwidth). The forth column is the inferred meaning, which is different from the literal meaning and is how the construction is actually used. The last column contains references.

| Construction | Construction (transliterated) | Literal Meaning | Inferred Meaning | References |
|----------|----------|----------|----------|----------|
| به کیرم  | [Be](https://en.wiktionary.org/wiki/%D8%A8%D9%87#Persian) [kiram](https://en.wiktionary.org/wiki/%DA%A9%DB%8C%D8%B1#Persian) | To my dick | I don't care  | - |
| به تخم چپم | Be [tokhm](https://en.wiktionary.org/wiki/%D8%AA%D8%AE%D9%85#Persian) [chapam](https://en.wiktionary.org/wiki/%DA%86%D9%BE#Persian) | To my left ball | I don't care  | - |
| تو کونم نمیره   | [Too](https://en.wiktionary.org/wiki/%D8%AA%D9%88#Etymology_4) [koonam](https://en.wiktionary.org/wiki/%DA%A9%D9%88%D9%86#Etymology_1) [ne](https://en.wiktionary.org/wiki/%D9%86%D9%87#Etymology_1_4) [mire](https://en.wiktionary.org/wiki/%D8%B1%D9%81%D8%AA%D9%86) | It does not go to my ass.  | I can't believe it | -  |
| تخم سگ | Tokhme [sag](https://en.wiktionary.org/wiki/%D8%B3%DA%AF#Persian) | Dog's balls | Naughty | - |
| سرت با کونت بازی میکنه | [Saret](https://en.wiktionary.org/wiki/%D8%B3%D8%B1#Persian) [ba](https://en.wiktionary.org/wiki/%D8%A8%D8%A7#Persian) koonet [bazi](https://en.wiktionary.org/wiki/%D8%A8%D8%A7%D8%B2%DB%8C#Persian) [mikone](https://en.wiktionary.org/wiki/%DA%A9%D8%B1%D8%AF%D9%86#Conjugation_2) | Your head does game with your ass | You don't have focus | - |
| دودول طلا | Doodool Tala | Golden dick | well-behaved kid | [Brian Parsa's instagram reel](https://www.instagram.com/reel/CyRgJEPPO0c/?igsh=cHNoMGYyejA2djg5) |
| مه موس | Me moos | (Mazani) My ass | The location of any lost item (use this to signal the speaker "why the hell should I know where your lost item is?) | - |
