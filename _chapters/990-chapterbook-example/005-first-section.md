---
slug: section1
title:  Name of this section
abstract: summary of this secton.
---

# Markdown basics 
The following provides a quick reference to the most commonly used Markdown syntax.


## Headers
### H3
#### H4
##### H5
###### H6

```r
norm <- function(x) {
  sqrt(x%*%x)
}
norm(1:4)
```

*Italic* and **Bold**
~~Scratched Text~~
superscript^2^
almost any <span style="color:red;">HTML</span> code that we &nbsp; <kbd>like</kbd> &nbsp; such as superscript<sup>2</sup>.

Nested Bullet points:
<\br>
- Item 1
- Item 2
    - Item 2a (2 tabs)
    - Item 2b

Nested Lists and bullets:
1. Item 1
2. Item 2
3. Item 3
    - Item 3a
    - Item 3b

Latex

$$
f(x)=
\begin{cases}
1/d_{ij} & \quad \text{when $d_{ij} \leq 160$}\\ 
0 & \quad \text{otherwise}
\end{cases}
$$

$$\int_a^b y \: \mathrm{d}x$$


code blocks:



Adding a quote or output of a program:
> x=5.0


~~~python
for x in range(5):
    print(x)
    if x>0:
        break
~~~

term
: definition
: another definition


This is a text with a
footnote[^1].

[^1]: And here is the definition.

---
```
This file is located at: {{ page.path }}
```
---
