
1. [22,27,16,2,18,6] -> insertion sort


- Verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yapınız.
- Time Complexity: Dizi sıralandıktan sonra 18 sayısı hangi case'e girer?


    0. Adım -> [22,27,16,2,18,6]
    1. Adım -> [22,27,16,2,18,6] -> Dizideki en küçük sayı (2) bulunur. 
    2. Adım -> [2,27,16,22,18,6] -> En küçük sayı en sola yani dizinin başına gitirilmek için en baştaki sayı ile yeri değiştirilir. 
    3. Adım -> [2,27,16,22,18,6] -> Dizide 2'den büyük olan ancak diğer sayılar içerisinde en küçük olan sayı (6) bulunur.
    4. Adım -> [2,6,16,22,18,27] -> Dizideki 2. en küçük sayı olan 6 sayısı ile 2. sıradaki 27 sayısının yerleri değiştirilir.
    N. Adım -> [2,6,16,18,22,27] -> Dizideki tüm sayılar soldan sağa doğru küçükten büyüğe olarak sıralanmış durumdadır. 

    - Big-O -> O(n^2)

    - Time Complexity -> Aradığımız sayı 18 -> Avarage Case 

2. [7,3,5,8,2,9,4,15,6] Dizisinin Section Sort'a göre 4 adımını yazın.


    0. Adım -> [7,3,5,8,2,9,4,15,6] Dizinin en küçük sayısı (2) bulunur.
    1. Adım -> [2,3,5,8,7,9,4,15,6]
    2. Adım -> [2,3,4,8,7,9,5,15,6]
    3. Adım -> [2,3,4,5,7,9,8,15,6]
    4. Adım -> [2,3,4,5,6,9,8,15,7]
    n. Adım -> [2,3,4,5,6,7,8,9,15]



