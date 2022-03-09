#Quantum 
## Άσκηση 1
![[Pasted image 20220219111414.png]]

---

## Άσκηση 2
![[Pasted image 20220219111443.png]]

---

## Άσκηση 3
![[Pasted image 20220219111519.png]]

---

## Άσκηση 4
![[Pasted image 20220219111544.png]]

---

## Άσκηση 5
![[Pasted image 20220219111646.png]]

---

## Άσκηση 6
![[Pasted image 20220219111718.png]]

---

Οι πράξεις για τον υπολογισμό των παρακάτω ολοκληρωμάτων παραλείπονται, είτε γιατι υπολογίστηκαν στην mathematica είτε γιατι οι πράξεις είναι πολύ εκτενής για να πληκτρολογηθούν και δεν προσφέρουν αξία στην εξέταση της κβαντομηχανικής.

---

## Άσκηση 7
$V(x)=\frac{1}{2}kx^2$
$\psi(x)=Nxe^{-λx^2}$
a) Για να είναι η ολική πιθανότητα 1 πρέπει:
$$<ψ|ψ>=\int_{-\infty}^{\infty}N^2*x^2e^{-2λx^2}dx=1$$
$$N^2* \frac{\sqrt{\frac{\pi}{2}}}{4λ^{3/2}}=1$$
$$N=2\sqrt[^4]{\frac{2λ^3}{\pi}}$$

b) Για να είναι ιδιοσυνάρτηση του H θα πρέπει να ισχύει:
$$Hψ=Eψ$$
$$-\frac{\hbar^2}{2m}\frac{d^2}{dx^2}ψ(x)+\frac{1}{2}kx^2ψ(x)=Eψ(x)$$
$$-\frac{\hbar^2}{2m}N(4λ^2x^2-6λ)xe^{-λx^2}+\frac{1}{2}kx^2*Nxe^{-λx^2}=E*Nxe^{-λx^2}$$
$$(-\frac{\hbar^2}{m}2λ^2+\frac{k}{2})x^2=E-\frac{\hbar^2}{m}3λ$$
Για κάθε χ:
$$\frac{\hbar^2}{m}2λ^2=\frac{k}{2}$$
$$λ=\frac{1}{2\hbar}\sqrt{km}$$
c)Μέση τιμή H:
$$<H>=\bra ψΗ\ketψ = \int (-\frac{\hbar^2}{m}2λ^2+\frac{k}{2})x^2*|ψ|^2 dx+\int \frac{\hbar^2}{m}{3}λ|ψ|^2dx$$
$$=(-\frac{\hbar^2}{m}2λ^2+\frac{k}{2})\frac{3\sqrt{\frac{\pi}{2}}}{16λ^{5/2}}+\frac{\hbar^2}{m}{3}λ$$

---

## Άσκηση 8

$Ψ(x)=Ne^{-\frac{a}{2}(x-x_0)^2+ip_0\frac{x}{\hbar}}$
$a>0$
Για να βρούμε το Ν κανονικοποιούμε:
$$\bra ψ\ketψ=1 => N^2\int e^{-a(x-x_0)^2}dx=1$$
$$N^2*\sqrt{\frac{\pi}{a}}=1$$
$$N=\sqrt[^4]{\frac{a}{\pi}}$$
a) $<x>$
$$<x>=\bra ψ x\ket ψ=\sqrt{\frac{a}{\pi}}\int_{-\infty}^{\infty}xe^{-a(x-x_0)^2}dx=x_0$$
$<x^2>$
$$<x^2>=\bra ψ x^2 \ket ψ= \sqrt{\frac{a}{\pi}}\int x^2e^{-a(x-x_0)^2}dx=x_0^2+\frac{1}{2a}$$
$<p>$
$$pψ=-i\hbar\frac{dψ}{dx}=-i\hbar\sqrt[^4]{\frac{a}{\pi}}(-a(x-x_0)+\frac{ip_0}{\hbar})e^{\frac{-a}{2}(x-x_0)^2+ip_0\frac{x}{\hbar}}$$
$$<p>=\bra ψ -i\hbar[\frac{d}{dx}\ket ψ=-i\hbar[\sqrt\frac{a}{\pi}\int -a(x-x_0)e^{-a(x-x_0)^2}dx+i\frac{p_0}{\hbar}\int |ψ|^2dx]$$
$$=-i\hbar\sqrt\frac{a}{\pi}\frac{e^{-a(x-x_0)^2}}{2} _{-\infty}^{+\infty}+(-i\hbar)\frac{i*p_0}{\hbar}=p_0$$
$<p^2>$
$$<p^2>=-\int ψ^* \hbar^2\frac{d^2}{dx^2}ψdx=-\hbar^2\int -a|ψ|^2-\hbar^2\int(-a(x-x_0)+i\frac{p_0}{\hbar})^2|ψ|^2$$
$$=a\hbar^2-\hbar^2 \sqrt\frac{a}{\pi}\int(-a(x-x_0)+\frac{ip_0}{\hbar})^2e^{-a(x-x_0)^2}dx=a\hbar^2+\hbar^2\frac{2p_0^2-a\hbar^2}{2\hbar^2}$$$$=a\hbar^2+p_0^2-\frac{a}{2}\hbar^2=\frac{a}{2}\hbar^2+p_0^2$$
b) 
$$(Δx)^2=<x^2>-<x>^2=x_0^2+\frac{1}{2a}-x_0^2=\frac{1}{2a}$$
$$(Δp)^2=<p^2>-<p>^2=\frac{a}{2}\hbar^2+p_0^2-p_0^2=\frac{a}{2}\hbar^2$$
$$(Δx)(Δp)=\sqrt\frac{1}{2a}\sqrt{\frac{a}{2}\hbar^2}=\frac{\hbar}{2}$$

---

## Άσκηση 9

![[273978160_1304411220043143_2022858343641039056_n (2).jpg]]

---
## Άσκηση 10

![[273943150_334626388430002_3043140753727052251_n.jpg]]

---

## Άσκηση 11

![[274061919_489203859269879_4024875804793035606_n.jpg]]
