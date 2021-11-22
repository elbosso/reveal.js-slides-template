# Demo

--

# Lists

---

# Unordered Lists

* a
* b
  * 1
  * 2
    * I
* c

---

# Ordered Lists

automatic numbering

1. a
1. b
    1. 1
    1. 2
1. c

---

# Ordered Lists

custom numbering

1. a  
2. b  
    2.1. 1  
    2.2. 2  
3. c

---
# Definition Lists

(actually: line breaks in long lines in lists...)

* First Term  
This is the definition of the first term.
* Second Term  
This is one definition of the second term.  
This is another definition of the second term.

--

# Syntax highlighting   

---

# Java 

```java [1-6|3-5]
public class TheFirst extends Object
{
	public static void main(String[] args)
	{
	}
}
```

---

# JavaScript

```js [1-2|3|4]
    let a = 1;
    let b = 2;
    let c = x => 1 + 2 + x;
    c(3);
```
    
--

# Dont reveal all at once!

- Item 1 <!-- .element: class="fragment" data-fragment-index="2" -->
- Item 2 <!-- .element: class="fragment" data-fragment-index="1" -->
- Item 3 <!-- .element: class="fragment" data-fragment-index="3" -->

---

# Fancy!

- Highlight Red <!-- .element: class="fragment highlight-red" data-fragment-index="2" -->
- Fade In Then Out <!-- .element: class="fragment fade-in-then-out" data-fragment-index="1" -->
- Slide up <!-- .element: class="fragment fade-up" data-fragment-index="3" -->
- Appear and step aside  <!-- .element: class="fragment fade-in-then-semi-out" data-fragment-index="4" -->

---

# Distinguished

- Item 1 <!-- .element: class="fragment semi-fade-out" data-fragment-index="1" -->
- Item 2 <!-- .element: class="fragment semi-fade-out" data-fragment-index="2" -->
- Item 3 <!-- .element: class="fragment semi-fade-out" data-fragment-index="3" -->
- Item 4 <!-- .element: class="fragment semi-fade-out" data-fragment-index="4" -->
- Item 5



--

# Math

---

# Single Line


`$$ J(\theta_0,\theta_1) = \sum_{i=0} $$`

---

# Multiple lines

`$$\begin{aligned}
  \dot{x} & = \sigma(y-x) \\
  \dot{y} & = \rho x - y - xz \\
  \dot{z} & = -\beta z + xy
  \end{aligned} $$`



