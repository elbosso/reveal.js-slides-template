# Demo

--

## Lists

---

## Unordered Lists

* a
* b
  * 1
  * 2
    * I
* c

---

## Ordered Lists

automatic numbering

1. a
1. b
    1. 1
    1. 2
1. c

---

## Ordered Lists

custom numbering

1. a  
2. b  
    2.1. 1  
    2.2. 2  
3. c

---
## Definition Lists

(actually: line breaks in long lines in lists...)

* First Term  
This is the definition of the first term.
* Second Term  
This is one definition of the second term.  
This is another definition of the second term.

---

## Font Awesome

*  Itym One<!-- .element: class="mdfa fa-info-circle"--> (this is a feature test in a very long item)
*  Itym Two<!-- .element: class="mdfa fa-question-circle"-->
*  Itym Three<!-- .element: class="mdfa fa-exclamation-circle"-->
*  Itym 4<!-- .element: class="mdfa fa-exclamation-triangle"-->  
with forced line break!

--

## Fragments

---

## Dont reveal all at once!

- Item 1 <!-- .element: class="fragment" data-fragment-index="2" -->
- Item 2 <!-- .element: class="fragment" data-fragment-index="1" -->
- Item 3 <!-- .element: class="fragment" data-fragment-index="3" -->

---

## Fancy!

- Highlight Red <!-- .element: class="fragment highlight-red" data-fragment-index="2" -->
- Fade In Then Out <!-- .element: class="fragment fade-in-then-out" data-fragment-index="1" -->
- Slide up <!-- .element: class="fragment fade-up" data-fragment-index="3" -->
- Appear and step aside  <!-- .element: class="fragment fade-in-then-semi-out" data-fragment-index="4" -->

---

## Distinguished

- Item 1 <!-- .element: class="fragment semi-fade-out" data-fragment-index="1" -->
- Item 2 <!-- .element: class="fragment semi-fade-out" data-fragment-index="2" -->
- Item 3 <!-- .element: class="fragment semi-fade-out" data-fragment-index="3" -->
- Item 4 <!-- .element: class="fragment semi-fade-out" data-fragment-index="4" -->
- Item 5

---

## FAQ (Example)

*  Question One?<!-- .element: class="fragment mdfa fa-question-circle"-->
*  Answer One!<!-- .element: class="fragment mdfa fa-exclamation-circle"-->
*  Question One?<!-- .element: class="fragment mdfa fa-question-circle"-->
*  Answer One!<!-- .element: class="fragment mdfa fa-exclamation-circle"-->
*  Question One?<!-- .element: class="fragment mdfa fa-question-circle"-->
*  Answer One!<!-- .element: class="fragment mdfa fa-exclamation-circle"-->

--


## Syntax highlighting   

---

## Java 

```java [1-6|3-5]
public class TheFirst extends Object
{
	public static void main(String[] args)
	{
	}
}
```

---

## JavaScript

```js [1-2|3|4]
    let a = 1;
    let b = 2;
    let c = x => 1 + 2 + x;
    c(3);
```
    
---

## Callouts 

<!--https://fsymbols.com/signs/bullet-point/-->
```java
String switchExpressionPreview13(Direction way) {
    return switch (way) {                         ➊
        case N -> "Up";                           ➋
        case S -> { yield "Down"; }               ➌
        case E, W -> "Somewhere left or right";
        // default -> "Foo"                       ➍
    };
}
```

- ➊ `switch` can be used as expression
- ➋ `->` instead of `:` → no `break;` necessary!
- ➌ Lambdas can be used to. For _expressions_ they must `yield` a value [version]#13#
- ➍ `default` can be ommitted if a) no expression or b) `enum` with every value handled

---

## Callouts  (Alternative)

<!--https://fsymbols.com/signs/bullet-point/-->
```java
String switchExpressionPreview13(Direction way) {
    return switch (way) {                         ①
        case N -> "Up";                           ②
        case S -> { yield "Down"; }               ③
        case E, W -> "Somewhere left or right";
        // default -> "Foo"                       ④
    };
}
```
- ① <!-- .element: class="co"-->`switch` can be used as expression 
- ② <!-- .element: class="co"-->`->` instead of `:` → no `break;` necessary!
- ③ <!-- .element: class="co"-->Lambdas can be used to. For _expressions_ they must `yield` a value [version]#13#
- ④ <!-- .element: class="co"-->`default` can be ommitted if a) no expression or b) `enum` with every value handled

--

## Math

---

## Single Line


`$$ J(\theta_0,\theta_1) = \sum_{i=0} $$`

---

## Multiple lines

`$$\begin{aligned}
  \dot{x} & = \sigma(y-x) \\
  \dot{y} & = \rho x - y - xz \\
  \dot{z} & = -\beta z + xy
  \end{aligned} $$`

--

# Thanks & Credits

* [reveal.js](https://revealjs.com/)
* [highlight.js](https://highlightjs.org/)
* [fontawesome](https://fontawesome.com/)

