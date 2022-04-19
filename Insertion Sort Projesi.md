# Insertion Sort Projesi

# Proje 1

**[22,27,16,2,18,6]** -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

(Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.)

1. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

 4.  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---

---

1 - 

 ***[22,27,16,2,18,6]** için insertion sort sıralaması aşağıdaki gibidir.*

- **[2,27,16,22,18,6]**
    - **[2,6,16,22,18,27]**
        - **[2,6,16,18,22,27]**

---

2 -

- Insertion Sort algoritması sıralama yaparken her aşamada dizideki sıralanmamış bütün elemanları kıyaslıyor.
- n tane elemanı olan bir dizide ilk aşamada n kere işlem yapıyor. ikinci aşamada n-1 tane ve dizide bir eleman kalana kadar bu işlem böyle devam ediyor.
- Big-O Notation için n+(n-1)+(n-2)...buda n ardışık sayının toplamı formülünden n*(n+1)/2 bu formülü açtığımınzda (n^2+2n+1)/2 gelir bu formülde baskın olan n^2 olduğu için Big-o Notation n^2 oluyor. **O(n^2)**

---

3 -  

Diziyi sıraladığımızda [2,6,16,18,22,27] sonucu çıkar, bu durumda 18 sayısı **avarage case** kapsamına girer.

---

4 -

***[7,3,5,8,2,9,4,15,6]** için 4. aşamaya kadar insertion sort sıralaması aşağıdaki gibidir.*

- **[2,3,5,8,7,9,4,15,6]**
    - [2,3,4,8,7,9,5,15,6]
        - [2,3,4,5,7,9,8,15,6]
            - [2,3,4,5,6,9,8,15,7]