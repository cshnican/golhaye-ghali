# Golhaye Ghali: a dataset for profanity constructions in Farsi and Mazani

## What is this dataset for?
This repository explores profanity constructions in Farsi and Mazani (Mazanderani), focusing on idiomatic expressions rather than isolated swear words. While existing resources primarily list individual profanities, this project seeks to document multi-word constructions that convey offensive, humorous, or metaphorical meanings in everyday speech.

## Why does it matter?
Language is believed to be largely compositional: the meaning of multi-word sequences can be mostly composed and deduced from the meaning of each word. For example, the meaning of "a white tower" is a tower that is white, which is a composition of its element, "white" and "tower". Compositionality allows speakers to generate complex meaning from a relatively smaller set of basic units, which is good, because speakers just need to memorize the meaning of each individual word, along with the rules to compose them together. On the other hand, if language is largely not-compositional, then speakers need to memorize 3 unrelated utterances for "book", "my book", and "Can I have my book?", which will be a nightmare for people using the language.

However, not everything about language is compositional. A counterexample is *idioms* in English: the sentence "put yourself in other people's shoes" doesn't mean you are actually wearing other people's shoes, as its individual words combined together will suggest. Instead, this sentence means to think in someone else's perspective. Another counterexample is some syntactic structures in English: "I am *into* laiko" does not mean I am physically into laiko music, as, again, its individual words combined together will suggest. Instead, it means I *like* laiko music.

Profanity constructions, which this dataset offers, is another example: words (usually vulgar) composed together mean something completely different from their individual parts. In English, the examples are "bullshit" vs. "batshit" vs. "horseshit" - they don't refer to the defecation of different animals. Rather, they refer to "nonsense", "something crazy", and "nonsense on a even deeper level".

Why is this the case? When is language not-compositional? How do these seemingly arbitraily meanings get assigned to these collection of words? To address these questions, in this dataset, we hope we can provide future researchers with data points to potentially draw inferences from. We choose Farsi and Mazani because they seem (to the judgement of curators) to be understudied languages with rich such constructions. 

Another theoretical value of this dataset is that it might offer a probe of how languages were spoken a long time ago, since these constructions were thought to have been formed a long time ago and have survived language changes due to their sociological values (cf. Progovac, 2024). 

A third, practical contribution of this dataset is to provide literal and implied translation of Farsi and Mazani expressions in order to train better machine translators.

## What are Farsi and Mazani?

Both Farsi and Mazani are Indo-Iranian languages in the Indo-European (IE) language family. The IE langauge family is currently the language family with the most number of speakers in the world ([3.4 billion worldwide](https://en.wikipedia.org/wiki/Indo-European_languages)), consisting of a diverse set of languages such as English, German, Swedish (Germanic), Ukranian, Russian, Bulgarian (Balto-Slavic), Spanish, French, Italian (Italic), Irish (Celtic), Hindi, Urdu, Farsi (Indo-Iranian), Greek (Hellenic), Armenian (Armenian), and Albanian (Albanian). The original form of the language (called Proto-Indo-European) is believed to be spoken by people living in Anatolia and the Steppe (Heggarty et al., 2023) around 8000 years ago.

Indo-Iranian languages are estimated to branch out from the Indo-European family tree around 5500 years ago (Gray & Atkinson, 2003), after Hittite (Anatolian), Tocharian, Armenian, Greek, and Albanian. Indo-Iranian languages than separated from Indo-Aryan languages around 4600 years ago (Gray & Atkinson, 2003). There are three main stages for Indo-Iranian languages (Fortson, 2009): Old Iranian (e.g. Old Persian, Avestan), Middle Iranian (e.g. Pahlavi), and Modern Iranian (e.g. Farsi, Tajik).

Farsi is a language with multiple varieties: the most well known variety is spoken in modern day Iran. Another variety, called Dari, is one of the official languages in Afghanistan. A third variety, Tajik, is the official language in Tajikstan. All these languages belong to the Southwestern Iranian branch of the Iranian language family (Hammarström and Forkel, 2022). Mazani (Mazanderani), on the other hand, belongs to the Norwestern Iranian branch (Hammarström and Forkel, 2022) and is mainly spoken in the northern part of Iran near the Caspian Sea in the Mazandaran Province.

## Table

This dataset consists of 5 columns. The first column is the original profanity construction in Farsi or Mazani, written in the Persian script. The second column is the transliterated construction in Latin script for those who are unfamiliar with the Persian sript, with links to the corresponding Wiktionary entry. The third column is the literal meaning of the construction, usually a word-by-word translation (annotation may be added later, depending on the curators' bandwidth). The forth column is the inferred meaning, which is different from the literal meaning and is how the construction is actually used. The last column contains references.

| Construction | Construction (transliterated) | Literal Meaning | Inferred Meaning | References |
|----------|----------|----------|----------|----------|
| به کیرم  | [Be](https://en.wiktionary.org/wiki/%D8%A8%D9%87#Persian) [kiram](https://en.wiktionary.org/wiki/%DA%A9%DB%8C%D8%B1#Persian) | To my dick | I don't care  | - |
| به تخم چپم | Be [tokhm](https://en.wiktionary.org/wiki/%D8%AA%D8%AE%D9%85#Persian) [chapam](https://en.wiktionary.org/wiki/%DA%86%D9%BE#Persian) | To my left ball | I don't care  | - |
| تو کونم نمیره   | [Too](https://en.wiktionary.org/wiki/%D8%AA%D9%88#Etymology_4) [koonam](https://en.wiktionary.org/wiki/%DA%A9%D9%88%D9%86#Etymology_1) [ne](https://en.wiktionary.org/wiki/%D9%86%D9%87#Etymology_1_4) [mire](https://en.wiktionary.org/wiki/%D8%B1%D9%81%D8%AA%D9%86) | It does not go to my ass.  | I can't believe it | -  |
| تخم سگ | Tokhme [sag](https://en.wiktionary.org/wiki/%D8%B3%DA%AF#Persian) | Dog's balls | Naughty | - |
| سرت با کونت بازی میکنه | [Saret](https://en.wiktionary.org/wiki/%D8%B3%D8%B1#Persian) [ba](https://en.wiktionary.org/wiki/%D8%A8%D8%A7#Persian) koonet [bazi](https://en.wiktionary.org/wiki/%D8%A8%D8%A7%D8%B2%DB%8C#Persian) [mikone](https://en.wiktionary.org/wiki/%DA%A9%D8%B1%D8%AF%D9%86#Conjugation_2) | Your head does game with your ass | You don't have focus | - |
| دودول طلا | [Doodool](https://fa.wiktionary.org/wiki/%D8%AF%D9%88%D8%AF%D9%88%D9%84) [Tala](https://en.wiktionary.org/wiki/%D8%B7%D9%84%D8%A7#Persian) | Golden dick | well-behaved kid | [Brian Parsa's instagram reel](https://www.instagram.com/reel/CyRgJEPPO0c/?igsh=cHNoMGYyejA2djg5) |
| مه موس | [Me](https://en.wiktionary.org/wiki/%D9%85%D9%87#Mazanderani) [moos](https://en.wiktionary.org/wiki/%D9%85%D9%88%D8%B3#Mazanderani) | (Mazani) My ass | The location of any lost item (use this to signal the speaker "why the hell should I know where your lost item is?) | - |
| خایه مالو سگ بگاد | [Khayeh](https://en.wiktionary.org/wiki/%D8%AE%D8%A7%DB%8C%D9%87#Persian) [mal](https://en.wiktionary.org/wiki/%D9%85%D8%A7%D9%84#Verb_3)[o](https://en.wiktionary.org/wiki/%D8%B1%D8%A7#Persian) sag [begad](https://en.wiktionary.org/wiki/%DA%AF%D8%A7%D8%A6%DB%8C%D8%AF%D9%86#Persian) | Ball rubber will be fucked by a dog | Use this phrase to a person who's being a kiss-ass (instead of saying it directly, people usually just sing a tune) | [the tune](https://youtube.com/shorts/qLD0vyYWO0U?si=sHj6fWqgkUp4Lch3) [source of the tune](https://www.youtube.com/shorts/_5iK6sarTyw)|
|برو تو کونم رنگی در آ| [Boro](https://en.wiktionary.org/wiki/%D8%B1%D9%81%D8%AA%D9%86) too koonam [rangi](https://en.wiktionary.org/wiki/%D8%B1%D9%86%DA%AF%DB%8C) [dar a](https://en.wiktionary.org/wiki/%D8%AF%D8%B1%D8%A2%D9%85%D8%AF%D9%86) | Go in my ass and exit colorful | I believe very little (or care very little) about what you say | - |
|کیر خر|[Kir](https://en.wiktionary.org/wiki/%DA%A9%DB%8C%D8%B1#Persian) e [khar](https://en.wiktionary.org/wiki/%D8%AE%D9%8E%D8%B1)|Donkey dick|Quiet down. (Said in response to a loud noise or exclamation)|-|
|گاز و گوز نکن|Gaaz o gooz nakon|Don't accelarate and don't fart|one it down.|-|
|کس موش چال کردن|Kos moosh chaal kardan.|‌Burrying mouse pussy|Engaging in a futile activity.|-|
|خنجر به کس فیل زدن|Khanjar be kos e feel zadan.|Daggering an elephant's pussy.|Engaging in a futile and dangerous activity.|-|
|گنده گوزی کردن|‌Gonde goozi kardan|Farting big farts.|excessively exaggerating|-|
|مه موس ته دوربینه| Me moos te durbin e | (Mazani) My ass is your telescope | You're paying attention to me too much |-|