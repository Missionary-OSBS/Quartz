---
Text: Plain Text
List:
  - A
  - B
  - C
Number: 12341121212
Checkbox: true
Date: 
Date & Time: 2024-06-22T11:32:22
---

## BackLink example
Unlike section above, which is YAML, this is an example of back link

>[!note]+ How it's typed
> title:: backlink

**Backlink can also be used in table**. However, it should be enclosed in square bracket `[name:: value]`

| A                | B                |
| ---------------- | ---------------- |
| [type:: example] | [tag:: #example] |

>[!note]+ How do you know the backlink works ?
> Well , we test it by using community plugin [[Dataview]] 
> 
> ```dataview
> table title, type, tag
> from "Other notes/Properties example"
> ```

