# Pinyinbase 

**Pinyinbase** is a truly free, libre and open source Chinese-English dictionary compiled using bilingual glossaries in backwards-compatible CEDICT files.

# Overview

  + **Pinyinbase is [free software][web_gnufree].**
  + Pinyinbase is a truly free, libre, and open source Chinese-English dictionary.
  + Pinyinbase is a distributed lexicographic knowledge base designed to compiled in unlimited ways.
  + Pinyinbase is designed to be a Chinese-English dictionary starter set, so you are not starting from scratch.
  + Pinyinbase is comprised of Chinese-English vocab lists (bilingual glossaries) that are backwards-compatibility CEDICT files.
  + Pinyinbase content is released to the [public domain][web_cczero].


# Details


### Workflow

![fmo][img_pb_steps]

Here is the workflow for Pinyinbase dictionary deployment:

  1. Create or edit vocab lists.
  2. Collect and [combine the vocab lists][gh_pbjkit] into an organized data source.
  3. Use the Pinyinbase dictionary outfile in apps.


### Pinyinbase Vs. CC-CEDICT

  + **Pinyinbase is NOT a CEDICT (or CC-CEDICT) fork.**
  + Pinyinbase uses CEDICT-formatted source files. That is where the similarities end.
    + The CEDICT files make it much easier for backwards-compatibility with legacy software.
  + Pinyinbase builds content based on vocab lists, not random submissions.
  + Pinyinbase provides definition-level or list-level control of Chinese-English dictionary content.


# Custom Chinese-English Dictionary Design

When it comes to Chinese-English dictionaries, one size does not fit all.

A Chinese-English dictionary in one context may be wholly inappropriate (or even illegal) in another.

**Pinyinbase solves this problem by providing you complete control over dictionary entries to avoid uncomfortable, unsuitable, unsafe and (in some cases) illegal content.**

Pinyinbase is designed to:

  + Provide complete control of what content is added to your custom Chinese-English dictionary.
  + Provide a Chinese-English dictionary set to be modified for your needs.  
  + Empower parents, teachers or clergy to specify acceptable content.
  + Help developers comply with local laws, regarding suitable content for audiences and jurisdictions.
  + Facilitate responsive development changes with a [simple build-from-source tool][gh_pbjkit].
  + Reconcile risk management priorities while limiting exposure for your project or organization.



# Case Studies

  + **Google AdSense is considered [family-safe][yt_adsense] and Google's Publisher Policy clearly defines [prohibited content][web_adsenserules].**  When you use content from a "community-maintained" dictionary, you may be putting your revenue stream, your brand or your organization at risk. Pinyinbase lets you control exactly which entries you add to your Chinese-English dictionary to keep your web site or mobile app family-safe.

  + **Good localization requires good understanding of local laws.** Local limitations on free speech determine which content should be excluded from your custom Chinese-English dictionary. Pinyinbase makes it easy to eliminate entire categories of entries, which may reduce your risk profile in these markets.

  + **Pinyinbase is powerful pinyin in your pocket dictionary.** Extending your brand to feature phones in emerging markets is not possible with a giant database dump. You need a dictionary with the right words for the right user. Pinyinbase helps you to build a small but useful Chinese-English dictionary, optimized for markets where a mobile phone is the primary platform.


# Bilingual Chinese-English Glossaries

  + Pinyinbase glossaries are CEDICT-formatted text files.
    + This format is backwards-compatible with legacy software.
    + CEDICT-formatted text files have wide library support across many languages.
    + Familiar format reduces cost of use or ownership for developers and end-users.
  + Each glossary contains a domain-specific vocabulary list of entries.
  + Each entry contains a Traditional Chinese field, a Simplified Chinese field, a Hanyu Pinyin field, and a definition field.
  + Learn more about [CEDICT Syntax][web_cedict].


# Search Pinyinbase with GitHub

  + **GitHub provides a powerful code search tool.**
  + Looking for specific words? Try [green tea][gh_search_greentea].


# License

  + Pinyinbase is released to the PUBLIC DOMAIN.
  + https://creativecommons.org/publicdomain/zero/1.0/

---
The Pffy Authors &middot; 2022

[gh_search_greentea]: https://github.com/pffy/pinyinbase/search?utf8=%E2%9C%93&q=green+tea
[gh_pbjkit]: https://github.com/pffy/pbjkit

[img_pb_steps]: https://raw.githubusercontent.com/pffy/b/main/png/pinyinbase-steps-300.png

[web_cczero]: http://creativecommons.org/publicdomain/zero/1.0/
[web_adsenserules]: https://support.google.com/adsense/answer/1348688?hl=en&vid=1-635770721350287708-1904227295&ref_topic=1271507&rd=1
[web_cedict]: http://cc-cedict.org/wiki/format:syntax
[web_gnufree]: http://www.gnu.org/philosophy/free-sw.en.html

[yt_adsense]: https://www.youtube.com/watch?v=dSucRZ3_AwA
