---
title: Kleene star
created: '2020-08-29T04:47:27.149Z'
modified: '2020-08-29T04:47:28.991Z'
---

# Kleene star

Denoted by L\*. It is the set of all strings obtained by concatenating zero or more strins from L.The concatenation of zero strings is e, and the concatenation of one string is the string itself.

> $L^*$ = { w $\epsilon \Sigma^*$ : w = $w_1 \circ w_2 \circ ... w_k$ for some $k\geq 0$ and some $w_1...w_k \epsilon L$}

L = {01, 1, 100}, then 110001110011 E L\*,
since 110001110011 = $1\circ 0\circ 100001\circ 0\circ 1\circ 0\circ 1000\circ 1\circ 0\circ 1$, and each of these strings is in L.

Note that if $\phi^* = \{e\}$ then $L^* = \{e\}$

# Regular Expression

-   Describes a language by means of ingle symbols, $\phi, \cup$, parentheses and \*.

The regular expressions over an alphabet $\Sigma^*$ are all strings over the alphabet $\Sigma^* \cup$ {(,), 0, U,\*}

![](img/L4/Annotation%202020-08-29%20093555.png)

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

<script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>
