# Insertion-Sort
Patika.dev
[22,27,16,2,18,6] -> Insertion Sort
1.
- İlk önce bütün öbeği inceleriz ve en küçük olanı ilk sırada olan sayı ile yer değişir.
  [2,27,16,22,18,6] -> 2 ile 22 yer değiştiriyor.
- İkinci sıra için de 2'den sonra gelen en küçük sayıyı arar ve ikinci sırada olan sayı ile yer değişiriz.
  [2,6,16,22,18,27] -> 6 ile 27 yer değiştiriyor.
- Aynı kuralı izleyrekten son sayıya kadar gelir.
  [2,6,16,22,18,27] -> 3. sıradaki sayı diğerleri arasında en küçük olduğu için yer değiştirme olmaz.
  [2,6,16,18,22,27] -> 18 ile 22 yer değiştiriyor.
  [2,6,16,18,22,27] -> 5. sıradaki sayı en küçük olduğu için yer değiştirme olmaz.
  [2,6,16,18,22,27] -> 6. sıradaki eleman en büyük olur ve öbeğimiz küçükten büyüğe sıralanmış olur.

2.
İlk turda n elemanımız olsun ve biz en küçüğü bulmak n elemanı kontrol ederiz. Sonrasında ise geri kalan elemanları kontrol ederiz yani n-1 elamana bakarız. Böyle devam eder ve n+(n-1)+(n-2).. şeklinde ilerler. Yani 1'den n'e kadar olan sayıların toplamından (n.(n-1))/2 gelir buradan da Big-O Notation'umuz O(n2) olur yani O(6^2) yani O(36)'dır.

3.
- Average Case: 16, 18
- Worst Case: 27
- Best Case: 2

4.
Average Case

5.
- [2,3,5,8,7,9,4,15,6]
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
