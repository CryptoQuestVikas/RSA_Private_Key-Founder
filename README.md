# RSA_Private_Key-Founder

# **Languages:**
> Python

```
git clone https://github.com/CryptoQuestVikas/RSA_Private_Key-Founder
cd RSA_Private_Key-Founder
chmod +x PrivateKey.py
python3 PrivateKey.py
```
# **Screenshot**
![](/img/pri.png)
![](/img/pri1.png)

# **About Fermat's Factorization Algorithm**
> Fermat's Factorization Algorithm is a classical method for integer factorization based on the principle of finding factors of a composite number \( N \) by expressing it as > a difference of two squares. Named after the French mathematician Pierre de Fermat, this algorithm is particularly effective for numbers that are products of two factors    > close > in magnitude.

> The algorithm begins by selecting an integer \( x \) such that \( x^2 - N \) is a perfect square. Specifically, we seek integers \( x \) and \( y \) such that:

> \[ x^2 - N = y^2 \]

> Rearranging gives:

> \[ x^2 - y^2 = N \]

> This can be factored as:

> \[ (x + y)(x - y) = N \]

> Thus, \( x + y \) and \( x - y \) are factors of \( N \). To find \( x \) and \( y \), start with \( x \) as the smallest integer greater than \( \sqrt{N} \), and check if  > \( x^2 - N \) is a perfect square. If it is, then \( y \) can be computed as \( \sqrt{x^2 - N} \), and the factors of \( N \) are \( (x + y) \) and \( (x - y) \).

> Though efficient for numbers with factors close together, Fermat's algorithm can be slow for numbers with widely spaced factors and is less effective compared to modern     > factorization methods for large integers.
