
```data
name: John
age: 50
city: Milan
country: Italy
---
name: Jane
age: 53
city: Rome,Berlin
country: Italy
---
name: Francesco
age: 28
city: Berlin
country: Germany
```

Example:
<!-- #query data where Berlin in [{{city}}] -->
No results
<!-- /query -->

<!-- #use [[template/tagquery]] {each} -->
**ERROR:** Failed to parse template instantiation args: [[template/tagquery]] {each}
<!-- /use -->
