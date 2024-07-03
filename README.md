# Shamir-s-secret-Sharing
This is a simple implementation of secret sharing.
Shamir's secret sharing plan
A program that receives S, t, n, p and produces n shares Y1, Y2,..., Yn.
+ Let’s say S is the secret that we wish to encode.
+ It is divided into N parts: S1, S2, S3, …., Sn.
+ After dividing it, a number t is chosen by the user in order to decrypt the parts and find the original secret.
+ It is chosen in such a way that if we know less than t parts, then we will not be able to find the secret S (i.e.) the secret S can not be reconstructed with (t – 1) parts or fewer.
+ If we know t or more parts from S1, S2, S3, …., Sn, then we can compute/reconstructed our secret code S easily. This is conventionally called (t, N) threshold scheme.
Approach:The main idea behind the Shamir’s Secret Sharing Algorithm lies behind the concept that for the given t points we can find a random polynomial equation with the degree (t – 1).
And a program that receives t, n, p, y1, y2, ..., yt and returns the secret s.
In order to reconstruct the given polynomial back, the Lagrange basis Polynomial is used.
![image](https://github.com/Fatemeh-Arani/Shamir-s-secret-Sharing/assets/87821575/074040df-e74b-432a-bb2a-982b2fc16b37)
