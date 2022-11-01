# Patikadev Insertion Sort Projesi 

[patika.dev](https://app.patika.dev/erhnako) kapsaminda almis oldugum egitimin bir parcasi olan bu projeyi paylasiyorum. Patika hesabima ve siteye linkten ulasabilirsiniz.

## Proje 1 

---

[22,27,16,2,18,6] -> Insertion Sort

        Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
        Big-O gösterimini yazınız.
        Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
        Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---

### 1. Asamalari;
[22,27,16,2,18,6] - (n), [2,27,16,22,18,6] - (n-1), [2,6,16,22,18,27] - (n-2), [2,6,16,18,22,27] - (n-3)

### 2. Big-O gosterimi;
O(n^2), O(n^2), O(n)

### 3. Cases;"'""
[2,6,16,18,22,27] Dizinin sıralanmış hali. 18 Aradığımız sayı dizinin ortasında bulunduğu için Average case kapsamına girer.

### 4. Ilk 4 adim;
[7,3,5,8,2,9,4,15,6], [2,7,5,8,3,9,4,15,6], [2,3,5,8,7,9,4,15,6], [2,3,4,8,7,9,5,15,6]