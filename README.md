Download Link: https://assignmentchef.com/product/solved-ve475-introduction-to-cryptography-homework-8
<br>
<strong>Ex. 1 –</strong><em> Lamport one-time signature scheme</em>

<ol>

 <li>Describe the Lamport signature scheme.</li>

 <li>Highlight the benefits and drawbacks of this method.</li>

 <li>Explain how this scheme can be attacked is a same key is used to sign more than one message.</li>

 <li>What is a<em> Merkie tree</em>, and how can it be used to improve the efficiency of the Lamport one-time signature scheme?</li>

</ol>

<strong>Ex. 2 –</strong><em> Chaum-van Antwerpen signatures</em>

In the lectures we presented the concept of undeniable signatures but we did not prove any of the results. We now do it, reusing the same notations.

<ol>

 <li>In this question we want to prove that ifs ≢ m<sup>x</sup> mod p, then swill be accepted as a valid signature with probability less than 1/q.</li>

 <li>For each value r Alice generates, how many ordered pairs ⟨e1, e2⟩ can be considered?</li>

 <li>Writing r = α<sup>i</sup>, t = αj, m = α<sup>k</sup>, and s = α<sup>l</sup>, i,j, k, l ∈ Z/qZ, consider the system of congruences</li>

</ol>

r ≡ se1βe2 mod p t ≡ me1αe2 mod p,

and prove it has a unique solution.

<ol>

 <li>Conclude on the probability that Alice accepts an invalid signature.</li>

 <li>We now prove that if s ≢ m<sup>x</sup> mod p, and the disavowal protocol is respected then we should have</li>

</ol>

(t1α−e2)f1 ≡ (t2α−f2)e1 mod p.

<ol>

 <li>Prove that</li>

</ol>

(t1α−e2)f1 ≡ se1f1x−1 mod p.

<ol>

 <li>Applying the same method to (t2α<sup>−f</sup>)<sup>e1</sup> mod p conclude that Bob can convince Alice that an invalid signature is a forgery.</li>

 <li>We finally prove that if s ≡ m<sup>x</sup> mod p, but t1 ≢ me1αe2 and t2 ≢ m<sup>f1</sup>α<sup>f2</sup>, then (t1α−e2)f1 ≢ (t2α−f2)e1 mod p with probability 1 − 1/q.</li>

 <li>Prove this result by contradiction using question 1.</li>

 <li>Does this result require Bob to follow the disavowal protocol?</li>

 <li>Can Bob convince Alice that a valid signature is a forgery?</li>

</ol>




<strong>Ex. 3 </strong>– <em>Simple questions</em>

<ol>

 <li>DSA with the parameters q = 101, p = 7879, a = 170, x = 75, and 3 = 4567 is used to signed a message whose hash is 52.</li>

 <li>Determine the signature of the message if k = 49.</li>

 <li>Verify the signature.</li>

 <li>Bob used the Elgamal signature scheme to sign his messages m1 = 8990 and m2 = 31415. He got ⟨m1, 23972, 31396), and (m2,23972.20481). Knowing his public parameters are p = 31847, a = 5, and 0 = 25703, recover both the random value k and his private key x.</li>

</ol>