# Markdown Extension Examples

Что-то на русском.

## Syntax Highlighting

Что-то на русском [Shikiji](https://github.com/antfu/shikiji), Что-то на русском:

**Input**

````md
```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
````

**Output**

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

## Custom Containers

**Input**

```md
::: info
Что-то на русском. info box.
:::

::: tip
Что-то на русском. tip.
:::

::: warning
Что-то на русском. warning.
:::

::: danger
Что-то на русском. dangerous warning.
:::

::: details
Что-то на русском. details block.
:::
```

**Output**

::: info
Что-то на русском. info box.
:::

::: tip
Что-то на русском. tip.
:::

::: warning
Что-то на русском. warning.
:::

::: danger
Что-то на русском. dangerous warning.
:::

::: details
Что-то на русском. details block.
:::

## More

Что-то на русском. [full list of markdown extensions](https://vitepress.dev/guide/markdown).
