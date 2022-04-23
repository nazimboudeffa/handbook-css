# La forme des règles CSS

<img src="images/css-ruleset.png" width="300">

# Différents selecteurs

Voici les principales façons d'affecter des propriétés CSS à des éléments

Selecteur par balise/tag

```
div {
 ...
}
```

Selecteur par identificateur

```
#mon-id {
 ...
}
```

Selecteur par classe permet de répéter les propriétés pour plusieurs autres éléments

```
.ma-classe{
 ...
}
```

Selecteur universel qui s'applique à tous les éléments

```
* {
 ...
}
```

Il y a aussi d'autres manières d'affeter des propriétés CSS à un élément, les pseudo classes

# Combinateurs

Ciblage adjascent

```
div + p {
...
}
```

Ciblage général

```
div ~ p {
...
}
```

Enfant

```
div > p {
...
}
```

Descendant

```
div p {
...
}
```

# Pseudo classes

Pseudo classe | Description
--- | --- 
:active | an element being activated by the user (e.g. clicked). Mostly used on links or buttons
:checked | a checkbox, option or radio input types that are enabled
:default | the default in a set of choices (like, option in a select or radio buttons)
:disabled | an element disabled
:empty | an element with no children
:enabled | an element that's enabled (opposite to :disabled )
:firstchild | the first child of a group of siblings
:focus | the element with focus
:hover | an element hovered with the mouse
:last-child | the last child of a group of siblings
:link | a link that's not been visited
:not() | any element not matching the selector passed. E.g. :not(span)
:nthchild() | an element matching the specified position
:nth-lastchild() | an element matching the specific position, starting from the end
:only-child | an element without any siblings
:required | a form element with the required attribute set
:root | represents the html element. It's like targeting html , but it's more specific. Useful in CSS Variables.
:target | the element matching the current URL fragment (for inner navigation in the page)