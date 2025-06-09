---
title: Rumus MTK
---

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

# MTK

## Barisan Aritmatika  
**Rumus:**  
$$u_n = a + (n - 1)b$$

## Deret Aritmatika  
**Rumus:**  
$$S_n = \frac{n}{2}(a + u_n)$$  
$$S_n = \frac{n}{2}(2a + (n - 1)b)$$

## Rumus Rasio  
$$r = \frac{u_n}{u_{n-1}}$$

## Rumus Suku ke-n (Geometri)  
$$u_n = a \times r^{n - 1}$$

## Deret Geometri  

**Jika rasio < 1:**  
$$S_n = a \times \frac{1 - r^n}{1 - r}$$

**Jika rasio > 1:**  
$$S_n = a \times \frac{r^n - 1}{r - 1}$$

## Luas dan Keliling Lingkaran  

**Jika diketahui diameter ($d$):**  
- Keliling: $$\pi \times d$$  
- Luas: $$L = \pi \times \frac{d^2}{4}$$

**Jika diketahui jari-jari ($r$):**  
- Keliling: $$2 \times \pi \times r$$  
- Luas: $$L = \pi \times r^2$$

---

## Garis Singgung Lingkaran  

### A. Garis Persekutuan Dalam  

Diketahui:  
- $$R$$ = jari-jari lingkaran besar  
- $$r$$ = jari-jari lingkaran kecil  
- $$d$$ = panjang garis singgung lingkaran dalam  
- $$p$$ = jarak titik pusat lingkaran  

**Rumus:**  
- $$d = \sqrt{p^2 - (R + r)^2}$$  
- $$p = \sqrt{d^2 + (R + r)^2}$$  
- $$R = \sqrt{p^2 - d^2} - r$$  
- $$r = \sqrt{p^2 - d^2} - R$$

---

### B. Garis Singgung Persekutuan Luar  

Diketahui:  
- $$L$$ = garis singgung lingkaran luar  

**Rumus:**  
- $$L = \sqrt{p^2 - (R - r)^2}$$  
- $$R = r + \sqrt{p^2 - L^2}$$  
- $$r = R - \sqrt{p^2 - L^2}$$
