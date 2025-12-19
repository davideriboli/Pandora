---
title: Indice Prompt
description: "Indice di sezione"
tags: [prompt, indici]
date: "2025-05-11"
---

# Altri Prompt per Immagini

```dataview
TABLE WITHOUT ID
    file.link AS "Titolo File",
    description AS "Descrizione"
FROM "01-Biblio/Prompt/AltriPromptPerImmagini/Varia"
WHERE file.name != this.file.name AND file.ext = "md"
SORT file.name ASC
```

---