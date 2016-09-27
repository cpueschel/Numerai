# Numerai
Hedge Fund Machine Learning


It has been shown that Benford's law can apply to day-to-day probability distributions for markets [1]. It is possible the Numerai's dataset would also demonstrate the law.

>Encryption is a way to secure data. Ordinarily, if you encrypt data, it becomes useless to a data scientist. But new developments in cryptography are letting us share datasets securely without destroying their utility to data scientists.

>Structure-preserving encryption schemes allow machine learning algorithms to learn things even though blind to the raw data.
There are now practical homomorphic encryption schemes, such as the Fan and Vercauteren scheme, which allows one to perform addition and multiplication operations on high degree polynomial ciphertexts in an algebraic ring. Turns out, if multiplication and addition are preserved, then structure is too. Since machine learning algorithms only care about structure, this breakthrough means you can run machine learning algorithms on encrypted data.

>Simpler schemes like order-preserving symmetric encryption also allow strong security in certain settings, and are easy to use with out of the box machine learning tools.[2]

1. Marco Corazza (3), Andrea Ellero (3), and Alberto Zorzi (3). "Checking Financial Markets via Benford's Law: The S&P 500 Case." - Springer. N.p., n.d. Web. 27 Sept. 2016.
2. https://medium.com/numerai/encrypted-data-for-efficient-markets-fffbe9743ba8#.4iiwc6ima
