# myKEYs

Vue, Vuetify and Firebase project.

# Firebase 資料結構

> 這邊用全大寫與大括號包覆表示其為集合、大駝峰表示文件、蛇式命名法表示欄位。

主要集合為 `KEYS`，當要對應 category_id 時需讀取 `CATEGORIES` 集合。

```js
{KEYS}:
  KeyA:
    category_id: 1
    name: 'Taiwan'
    account: 'aaa@gmail.com'
    password: 'ljklookl'
    remark: 'dldkdfdss'
  KeyB:
    category_id: 2
    name: 'America'
    account: 'bbb@gmail.com'
    password: 'ppol'
    remark: 'eeew'
```

```js
{CATEGORIES}:
  CategoryA:
    id: 1
    name: "Apple ID"
  CategoryB:
    id: 2
    name: "Facebook"
```