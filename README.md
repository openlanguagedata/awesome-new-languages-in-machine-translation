# Awesome New Languages in Machine Translation
This is a list of initiatives for adding new languages to opensource machine translation models (such as [NLLB](https://github.com/facebookresearch/fairseq/tree/nllb)).

Also, some notable projects for increasing the translation quality for an already supported low-resourced language would be highlighted.

The first part of the document lists individual languages in the alphabetic order of their English names.

The second part of the document lists multilingual initiatives.

Any new additions are welcome (in the form of pull requests or issues)!

# Single-language projects

## Ainu 
- Model: https://huggingface.co/TwentyNine/nllb-jpn-ain-v1

## Amis
- Model: https://huggingface.co/dylan-leddy/nllb-eng-ami-reverse

## Aromanian
- Code and description: https://github.com/lolismek/AroTranslate
- Paper: https://arxiv.org/abs/2410.17728
- Interface: https://arotranslate.com/

## Awajun
- Model: https://huggingface.co/hectordiazgomez/nllb-spa-awa-v2

## Bambara
- Paper: https://aclanthology.org/2023.loresmt-1.9/ 

## Buryat
- Press: https://burunen.ru/news/society/107048 (in Russian)
- Interface: https://translate-bur.ru/
- Model: https://huggingface.co/SaranaAbidueva/nllb-200-bxr-ru 

##  Circassian (Kabardian)
- Interface: https://www.zedzek.com/en

##  Chechen 
- Paper: https://arxiv.org/abs/2507.12672
- Dataset, sentence encoder, translation model: [https://huggingface.co/collections/NM-development](https://huggingface.co/collections/NM-development/open-machine-translation-for-the-chechen-language-6877a4abad8a4ea9ef15bbef)

## Emakhuwa:
- Paper: https://www2.statmt.org/wmt24/pdf/2024.wmt-1.45.pdf

## Erzya
- Interface: https://lango.to/ 
- Paper (for an old version): https://aclanthology.org/2022.fieldmatters-1.6/
- Newer paper: https://www2.statmt.org/wmt24/pdf/2024.wmt-1.49.pdf 

Additionally, see [TartuNLP](#finno-ugric-languages-tartunlp).

## Fula
- Model: https://huggingface.co/flutter-painter/nllb-fra-fuf-v2

## Ge’ez
- Paper: https://aclanthology.org/2024.loresmt-1.14/ 

## Hill Mari
See [TartuNLP](#finno-ugric-languages-tartunlp)

## Interslavic
- Model: https://huggingface.co/Salavat/nllb-200-distilled-600M-finetuned-isv_v2
- Demo: https://huggingface.co/spaces/Salavat/Interslavic-Translator-NLLB200
- Presentation: https://www.youtube.com/watch?v=BiNrza83Gvw

## Karakalpak
- Interface: https://tahrirchi.uz/uz/translator
- Paper: https://www2.statmt.org/wmt24/pdf/2024.wmt-1.48.pdf 

## Komi
See [TartuNLP](#finno-ugric-languages-tartunlp)

## Kpelle
- Paper: https://arxiv.org/abs/2505.18905
- Data: https://huggingface.co/datasets/IARG-UF/English-Kpelle-Corpus

## Ladin:
- Paper: https://clic2024.ilc.cnr.it/wp-content/uploads/2024/12/104_main_long.pdf

## Lezgian
`lez`, [lezg1247](https://glottolog.org/resource/languoid/id/lezg1247)

- Model: https://huggingface.co/leks-forever/nllb-200-distilled-600M
- Code: https://github.com/leks-forever/nllb-tuning
- Demo: https://huggingface.co/spaces/leks-forever/lezghian-nllb-200-distilled-600M
- Description (in Russian): [in a Telegram channel](https://t.me/saidgood/248)

## Livonian
See [TartuNLP](#finno-ugric-languages-tartunlp)

## Livvi Karelian
See [TartuNLP](#finno-ugric-languages-tartunlp)

## Mansi
- Github:  https://github.com/anyasarybaeva/Mansi-Legends

## Mari (Meadow)
See [TartuNLP](#finno-ugric-languages-tartunlp)

## Moksha
See [TartuNLP](#finno-ugric-languages-tartunlp)

## Ngambay
- Paper: https://aclanthology.org/2023.nlp4tia-1.6.pdf

## Qarachay Malqar
- Github: https://github.com/TBSj/Qarachay_Malqar_translator 
- Model: https://huggingface.co/TSjB/NLLB-201-600M-QM-V1 
- Blog post (rus): https://habr.com/ru/articles/829248/ 

## Tamazight
- Model: https://huggingface.co/Tamazight-NLP/NLLB-200-600M-Tamazight-All-Data-3-epoch
- Demo: https://huggingface.co/spaces/Tamazight-NLP/Finetuned-NLLB
- Paper: https://www2.statmt.org/wmt25/pdf/2025.wmt-1.82.pdf

## Tyvan
- Blog: https://cointegrated.medium.com/a37fc706b865 
- Interface: https://tyvan.ru/
- Paper: https://www2.statmt.org/wmt24/pdf/2024.wmt-1.46.pdf

## Udmurt
See [TartuNLP](#finno-ugric-languages-tartunlp)

## Wu Chinese
- Paper: https://www2.statmt.org/wmt24/pdf/2024.wmt-1.47.pdf

## Zarma
- Paper: https://arxiv.org/abs/2406.05888

# Multilingual projects

## Finno-Ugric languages (TartuNLP)
Multiple Finno-Ugric languages (including Komi, Udmurt, Hill and Meadow Mari, Erzya, Livonian, Mansi, Moksha and Livvi Karelian)

- Paper (an early one): https://aclanthology.org/2022.wmt-1.33/ 
- Paper: https://aclanthology.org/2023.nodalida-1.77.pdf 
- Interface: https://translate.ut.ee/ 
- Model: https://huggingface.co/tartuNLP/smugri3_14-finno-ugric-nmt 

## Indigenous languages of the Americas (AmericasNLP Shared Tasks)
Indigenous languages of the Americas (including Ashaninka, Aymara, Bribri, Chatino, Guarani, Hñähñu, Nahuatl, Quechua, Raramuri, Shipibo-Konibo, and Wixarika from the AmericasNLP Mt shared task, and Wayuunaiki, Arhuaco, Inga, and Nasa – additionally)
- Paper: https://aclanthology.org/2023.americasnlp-1.19.pdf 
- Paper: https://aclanthology.org/2024.americasnlp-1.22.pdf
- Paper: https://aclanthology.org/2024.americasnlp-1.2.pdf

## Multiple Iberian languages
Aragonese, Aranese, Asturian, Valencian
- Paper: https://www2.statmt.org/wmt24/pdf/2024.wmt-1.94.pdf
- Paper: https://www2.statmt.org/wmt24/pdf/2024.wmt-1.41.pdf

##  Multiple Ethiopian languages 
Namely: Afar, Afaan Oromo, Awngi, Amharic, Basketo, Dawuro, Dashenech, Geez, Gamo, Gofa, Gurage, Hadiya, Kafa, Korate, Majang, Male, Murule, Nuer, Shakicho, Sidama, Somali, Tigrinya, Wolaytta.
- Paper: https://aclanthology.org/2024.rail-1.12/


## Hundreds of diverse languages (Apertium)
Apertium is a system of rule-based machine translation. 

Currently, it has linguistic tools (such as dictionaries and morphological parsers) for an insane number of languages, but only few of them (51 language pairs) have been developed to a state considered stable enough for publicly releasing a translation service.

- Code: https://github.com/apertium
- Interface (with only a subset of the most stable language pairs): https://www.apertium.org/
  
