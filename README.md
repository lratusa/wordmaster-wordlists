# WordMaster Word Lists

This repository contains word list data for the WordMaster vocabulary learning app.

## Structure

```
english/           # English word lists
  cefr-a1.json     # CEFR A1 level
  cefr-a2.json     # CEFR A2 level
  cet4-full.json   # CET-4 full vocabulary
  toefl-core.json  # TOEFL core vocabulary (~5000 words)
  toefl-full.json  # TOEFL full vocabulary (~10000 words)
  ...

japanese/          # Japanese word lists (JLPT)
  jlpt-n5.json
  ...
```

## Word List Format

```json
{
  "name": "Word List Name",
  "language": "en",
  "description": "Description",
  "icon_name": "school",
  "words": [
    {
      "word": "example",
      "translation_cn": "例子",
      "part_of_speech": "n.",
      "phonetic": "/ɪɡˈzæmpəl/",
      "difficulty_level": 2,
      "examples": [
        {
          "sentence": "This is an example.",
          "translation_cn": "这是一个例子。"
        }
      ]
    }
  ]
}
```

## Available Word Lists

### English
| File | Name | Words |
|------|------|-------|
| cefr-a1.json | CEFR A1 | ~500 |
| cefr-a2.json | CEFR A2 | ~500 |
| cet4-full.json | CET-4 | ~4500 |
| toefl-core.json | TOEFL Core | ~5000 |
| toefl-full.json | TOEFL Full | ~10000 |

## License

MIT License
