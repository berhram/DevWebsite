---
linkTitle: const
toc: false
---
# Question
What is the advantage of using const in Kotlin? 
# Answer
- Such properties can be used in annotations
- Value will be inlined, so there will be no getter call at runtime
# Extended Answer
Such property must fulfill requirements:
- Top-level propery, or member of (companion or regular) object
- String or primitive type
- Cannot have custom getter
# Links
https://kotlinlang.org/docs/properties.html#compile-time-constants