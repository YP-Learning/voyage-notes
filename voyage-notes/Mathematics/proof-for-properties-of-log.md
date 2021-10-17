
-  [[#The Product Rule]] 
-   [[#The Quotient Rule]]
-   [[#The Power Rule]]
-   [[#The Change of Base Rule]]

---
## The Product Rule
#### $$\log_a(b) + \log_a(c) = \log_a(b\cdot c)$$

Proof: 
$\text{let, } m = \log_a(b) \text{, and, } n = \log_a(c)$

 convert to exponential equations
$m = \log_a(b) \to b = a^m\text{,  }n = \log_a(c) \to c = a^n$ 

using the product rule of exponents  $[a^m + a^n = a^{m+n}]$

$b \cdot c = a^m + a^n = a^{m+n} \text{  [using the product rule of exponents]}$
$\log_a(b \cdot c) = m + n \text{ [converting it back to logarithm]}$

substituting out assumed values of m and n
$$\log_a(b \cdot c) = \log_a(b) + \log_a(c)$$

---
## The Quotient Rule
#### $$\log_a(b) - \log_a(c) = \log_a(\frac{b}{c})$$

Proof:
$\text{let, } m = \log_a(b) \text{, and, } n = \log_a(c)$

convert to exponential equation
$m = \log_a(b) \to b = a^m$
 $n =\log_a(c) \to c = a^n$

using $\frac{a^m}{a^n} = a^{m-n}$
$\frac{b}{c} = \frac{a^m}{a^n} = a^{m-n}$

convirting this back to log
$\log_a(\frac{b}{c}) = m-n$

Substituting the assumed values of m and n
#### $$\log_a(\frac{b}{c}) = \log_a(b) - \log_a(c)$$

---
## The Power Rule
#### $$a \cdot \log_b(c) = \log_b(c^a)$$

Proof:
let, $m = \log_b(c)$

convert to exponential form
$m = \log_b(c) \to c = b^m$

raise both the sides to $a$ power
$c^a = (b^m)^a = b^{ma}$

taking $\log_b$ of both the sides
$\log_b(c^a) = \log_b(b^{ma})$
$\log_b(c^a) = \log_b(b) \cdot (ma) = ma \cdot 1$
$\log_b(c^a) = ma$ 

substituting the value of m
#### $$\log_b(c^a) = \log_b(c) \cdot a$$

---
## The Change of Base Rule
#### $$\log_b(a) = \frac{\log_c(a)}{\log_c(b)}$$

Proof:
let, $\log_b(a) = m$

Convert to exponential form
$b^m = a$

take log with base b of both the sides
$\log_c(b^m) = \log_c(a)$
$m \cdot \log_c(b) = \log_c(a)$ [using The power rule]
$m = \frac{\log_c(a)}{\log_c(b)}$

substituting m
#### $$\log_b(a) = \frac{\log_c(a)}{\log_c(b)}$$