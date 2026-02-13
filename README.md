# WordMaster Word Lists

This repository contains word list data for the [WordMaster](https://github.com/lratusa/wordmaster) vocabulary learning app.

## Overview

- **40,000+ vocabulary words** across English and Japanese
- **4,200+ kanji characters** with readings and example words
- **Chinese translations** for all entries
- **IPA phonetics** for English words
- **Example sentences** with translations
- **Multiple proficiency levels** (CEFR A1-C2, JLPT N5-N1)
- **Japanese school curriculum** kanji (Grades 1-6, Middle School, High School)

## Structure

```
english/              # English word lists
  cefr_a1.json        # CEFR A1 - Beginner (1,063 words)
  cefr_a2.json        # CEFR A2 - Elementary (1,352 words)
  cefr_b1.json        # CEFR B1 - Intermediate (2,354 words)
  cefr_b2.json        # CEFR B2 - Upper-Intermediate (2,691 words)
  cefr_c1.json        # CEFR C1 - Advanced (1,009 words)
  cefr_c2.json        # CEFR C2 - Proficiency (972 words)
  cet4-full.json      # CET-4 Full vocabulary
  cet6_full.json      # CET-6 Full vocabulary
  toefl-full.json     # TOEFL Full vocabulary
  kaoyan_full.json    # 考研 Full vocabulary
  ...

japanese/             # Japanese word lists
  jlpt_n5.json        # JLPT N5 - Beginner vocabulary
  jlpt_n4.json        # JLPT N4 - Elementary vocabulary
  jlpt_n3.json        # JLPT N3 - Intermediate vocabulary
  jlpt_n2.json        # JLPT N2 - Upper-Intermediate vocabulary
  jlpt_n1.json        # JLPT N1 - Advanced vocabulary
  jlpt_kanji_n5.json  # JLPT N5 - Kanji (80 characters)
  jlpt_kanji_n4.json  # JLPT N4 - Kanji (170 characters)
  jlpt_kanji_n3.json  # JLPT N3 - Kanji (370 characters)
  jlpt_kanji_n2.json  # JLPT N2 - Kanji (380 characters)
  jlpt_kanji_n1.json  # JLPT N1 - Kanji (1,135 characters)
  school_kanji_grade1.json  # 小学1年生 (80 kanji)
  school_kanji_grade2.json  # 小学2年生 (160 kanji)
  school_kanji_grade3.json  # 小学3年生 (200 kanji)
  school_kanji_grade4.json  # 小学4年生 (202 kanji)
  school_kanji_grade5.json  # 小学5年生 (193 kanji)
  school_kanji_grade6.json  # 小学6年生 (191 kanji)
  school_kanji_middle.json  # 中学校 (610 kanji)
  school_kanji_high.json    # 高等学校 (500 kanji)
```

## Word List Format

```json
{
  "name": "CEFR B1 中级",
  "language": "en",
  "description": "欧洲语言共同参考框架 B1 级别词汇 (2354词)",
  "icon_name": "school",
  "words": [
    {
      "word": "abandon",
      "translation_cn": "放弃；抛弃",
      "part_of_speech": "v.",
      "phonetic": "/əˈbændən/",
      "cefr_level": "B1",
      "difficulty_level": 2,
      "examples": [
        {
          "sentence": "They had to abandon the car.",
          "translation_cn": "他们不得不弃车。"
        },
        {
          "sentence": "Don't abandon your dreams.",
          "translation_cn": "不要放弃你的梦想。"
        }
      ]
    }
  ]
}
```

## Available Word Lists

### CEFR English (欧洲语言共同参考框架)

| File | Level | Name | Words | Description |
|------|-------|------|-------|-------------|
| cefr_a1.json | A1 | 入门 | 1,063 | Beginner - Basic phrases and expressions |
| cefr_a2.json | A2 | 初级 | 1,352 | Elementary - Everyday situations |
| cefr_b1.json | B1 | 中级 | 2,354 | Intermediate - Independent user |
| cefr_b2.json | B2 | 中高级 | 2,691 | Upper-Intermediate - Complex texts |
| cefr_c1.json | C1 | 高级 | 1,009 | Advanced - Proficient user |
| cefr_c2.json | C2 | 精通 | 972 | Proficiency - Near-native level |
| **Total** | | | **9,441** | |

### Chinese Exam Vocabulary (中国考试词汇)

| File | Name | Words | Description |
|------|------|-------|-------------|
| zhongkao_full.json | 中考完整词汇 | ~1,600 | Middle school entrance exam |
| gaokao_full.json | 高考完整词汇 | ~3,500 | College entrance exam |
| cet4-full.json | CET-4 四级 | ~4,500 | College English Test Band 4 |
| cet6_full.json | CET-6 六级 | ~5,500 | College English Test Band 6 |
| kaoyan_full.json | 考研词汇 | ~5,500 | Graduate entrance exam |

### Standardized Test Vocabulary (标准化考试)

| File | Name | Words | Description |
|------|------|-------|-------------|
| toefl-full.json | TOEFL 托福 | ~10,000 | Test of English as a Foreign Language |
| sat_full.json | SAT | ~4,000 | SAT vocabulary |

### Japanese Vocabulary (JLPT 日本語能力試験)

| File | Level | Words | Description |
|------|-------|-------|-------------|
| jlpt_n5.json | N5 | ~800 | Beginner - Basic Japanese |
| jlpt_n4.json | N4 | ~1,500 | Elementary - Basic grammar |
| jlpt_n3.json | N3 | ~3,700 | Intermediate - Everyday Japanese |
| jlpt_n2.json | N2 | ~6,000 | Upper-Intermediate - Complex texts |
| jlpt_n1.json | N1 | ~10,000 | Advanced - Near-native level |

### Japanese Kanji - JLPT (日本語能力試験 漢字)

| File | Level | Kanji | Description |
|------|-------|-------|-------------|
| jlpt_kanji_n5.json | N5 | 80 | Basic kanji for beginners |
| jlpt_kanji_n4.json | N4 | 170 | Elementary kanji |
| jlpt_kanji_n3.json | N3 | 370 | Intermediate kanji |
| jlpt_kanji_n2.json | N2 | 380 | Upper-intermediate kanji |
| jlpt_kanji_n1.json | N1 | 1,135 | Advanced kanji |
| **Total** | | **2,135** | |

### Japanese Kanji - School Curriculum (学年別漢字配当表)

| File | Level | Kanji | Description |
|------|-------|-------|-------------|
| school_kanji_grade1.json | 小学1年 | 80 | Elementary Grade 1 |
| school_kanji_grade2.json | 小学2年 | 160 | Elementary Grade 2 |
| school_kanji_grade3.json | 小学3年 | 200 | Elementary Grade 3 |
| school_kanji_grade4.json | 小学4年 | 202 | Elementary Grade 4 |
| school_kanji_grade5.json | 小学5年 | 193 | Elementary Grade 5 |
| school_kanji_grade6.json | 小学6年 | 191 | Elementary Grade 6 |
| school_kanji_middle.json | 中学校 | 610 | Middle School |
| school_kanji_high.json | 高等学校 | 500 | High School |
| **Total** | | **2,136** | Complete Joyo Kanji |

## Data Sources

- **CEFR (A1-B2)**: [CEFR-J Vocabulary Profile](https://github.com/openlanguageprofiles/olp-en-cefrj) - CC BY-SA 4.0
- **CEFR (C1-C2)**: [Octanove Vocabulary Profile](https://github.com/openlanguageprofiles/olp-en-cefrj) - CC BY-SA 4.0
- **Chinese Exams**: [KyleBing/english-vocabulary](https://github.com/KyleBing/english-vocabulary)
- **JLPT Vocabulary**: Community-sourced JLPT vocabulary lists
- **JLPT Kanji**: [davidluzgouveia/kanji-data](https://github.com/davidluzgouveia/kanji-data)
- **School Kanji (Elementary)**: [fnshr/kyo-kan](https://github.com/fnshr/kyo-kan) - CC0 1.0
- **School Kanji (Joyo)**: [vaiorabbit/everyday_use_kanji](https://github.com/vaiorabbit/everyday_use_kanji)

## Usage

These word lists are designed for use with the [WordMaster app](https://github.com/lratusa/wordmaster), but can be used in any vocabulary learning application that supports JSON format.

## License

MIT License

## Contributing

Contributions welcome! Please submit issues or pull requests for:
- Corrections to translations or phonetics
- Additional example sentences
- New word lists
