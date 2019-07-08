# Multiple Languages

Anofie supports multiple languages, including Russian, Portugese, Chinese, Japanese and even RTL languages such as Arabic, Persian, Urdu, etc.

> {info} Please read the below guidelines to add a new language or update existing one.

---

- [Add New Language](#Add-New-Language)


<a name="Add-Language"></a>
## Add Language

You can find all the language files in `application/language` directory. If you want to add a new langauge then simply copy the `english` directory and paste it as `<your_language_name>`.

> {info} Recommended file to translate- `core_lang`

e.g Suppose you wanna add `mandarin` langauge. Then give copy the `english` folder and rename it as `mandarin` and translate all the files inside except variables names.

```bash

    application
        │
        ├── langauge
            ├── english
            └── mandarin

    ```
