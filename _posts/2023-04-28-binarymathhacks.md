---
toc: true
layout: post
description: Binary Math HACKS with Extra Credit
categories: [markdown]
title: Binary Math HACKS (DID ALL THREE BUTTONS FOR EXTRA CREDIT)
---

```
How do you think we should find the difference of two binary numbers? The product? The quotient? What rules need to be followed for those operations? Look into all of this on the Internet and note down important information you find
```

**To find the difference of two binary numbers, we need to subtract each bit of the second number from the corresponding bit of the first number, starting from the least significant bit. If the result of the subtraction is negative, then we need to borrow 1 from the next bit. This process is continued until all the bits are subtracted.**

**Multiplication of binary numbers involves multiplying each bit of one number with all the bits of the other number, similar to decimal multiplication. The results of these multiplications are then added up to give the final product. It is important to keep track of the carry bits while performing multiplication, similar to decimal multiplication.**

**Division of binary numbers involves a similar process to decimal division. We need to repeatedly subtract the divisor from the dividend until we get a remainder that is less than the divisor. The quotient is the number of times we subtracted the divisor from the dividend. It is important to align the divisor and dividend properly and to keep track of the remainder and quotient while performing division.**

**In all these operations, it is important to remember that binary numbers only have 2 digits (0 and 1), and any operation involving these numbers follows the rules of binary arithmetic, which can be different from the rules of decimal arithmetic.**

```
Based on what you find online, fill out the tables below for subtracting, multiplying, and dividing binary numbers (0.45):
```

![]({{site.baseurl}}/images/hack.png "Hack Pic")


```
Create buttons similar to the ones above that allow you to subtract binary numbers and returns the desired result in both binary and decimal
Create buttons similar to the ones above that allow you to multiply binary numbers and returns the desired result in both binary and decimal
Create buttons similar to the ones above that allow you to divide binary numbers and returns the desired result in both binary and decimal

If you create buttons for all three of these (or somehow find a way to combine them!), you can get an extra 0.1, and if you decide to customize the buttons to make them look more visually appealing (i.e. by using SASS), you could get extra credit.

BONUS: Create a binary to decimal/decimal to binary converter in any language (not given in the lesson) a different way (0.9). Try not to use binary functions (like bin(x))!
```

{% include binarymath1.html %}

{% include binarymath2.html %}

{% include binarymath3.html %}
