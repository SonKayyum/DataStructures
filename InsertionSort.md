# Insertion Sort Projesi
[Patika.dev Profilim](https://app.patika.dev/sonkayyum) 

### [22,27,16,2,18,6] Insertion Sort algoritması ile sıralanması istenmektedir.

Sıralamaya ilk sayıdan başlıyoruz. Yani 22.
**İlk geçişte (pass)** 22 sayısını olduğu gibi bırakıyoruz.

22 | 27 16 2 18 6

**İkinci geçişte** sıralayacağımız sayı 27. Büyük olduğu için yer değiştirmiyor.

22 27 | 16 2 18 6

**Üçüncü geçişte** 16 geliyor. İlk iki sayı ile karşılaştırdığımızda en küçüç olduğu için başa geçiyor.

16 22 27 | 2 18 6

Her yeni gelen sayıda kendinden önceki ile karşılaştırarak eğer küçükse soluna geçiyor. 

2 16 22 27 | 18 6

2 16 18 22 27 | 6

2 6 16 18 22 27 |

### Big-O gösterimi: 

O(n²)

### Time Complexity:

Average case: O(n²)
Worst case: O(n²)
Best case: O(n)

### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

Avarage Case

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

 1) 7 | 3 5 8 2 9 4 15 6
 2) 3 7 | 5 8 2 9 4 15 6
 3) 3 5 7 | 8 2 9 4 15 6
 4) 3 5 7 8 | 2 9 4 15 6