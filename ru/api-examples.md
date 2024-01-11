---
outline: deep
---

# Runtime API Examples

Что-то на русском..

Что-то на русском. `useData()` Что-то на русском. `.md` and `.vue` files:

```md
<script setup>
import { useData } from 'vitepress'

const { theme, page, frontmatter } = useData()
</script>

## Результат

### Данные темы
<pre>{{ theme }}</pre>

### Данные страницы
<pre>{{ page }}</pre>

### страница форматирования
<pre>{{ frontmatter }}</pre>
```

<script setup>
import { useData } from 'vitepress'

const { site, theme, page, frontmatter } = useData()
</script>
