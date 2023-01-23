<a href="https://app.patika.dev/nisacerenunnu">
    <img alt="patika" title="Patika" src="https://custom-icon-badges.demolab.com/badge/Patika.dev  |  nisacerenunnu-FF6600.svg?logo=patika_beyaz&logo_Color=white&style=flat-square&labelColor=FF6600"/>
    </a>

## [22,27,16,2,18,6] -> Insertion Sort verilen dizinin sort türüne göre aşamalarını yazınız. 

1. En küçük sayıyı alıp baştaki sayı ile yerlerini değiştir. [ 22 , 27 , 16 , 2 , 18 , 6 ] > [ 2 , 27 , 16 , 22 , 18 , 6 ]
2. İkinci en küçük sayı 6. 6'yi alıp  ikinci sıraya koyuyoruz ve ikinci sırada olan 27'yi alıp 6'nın eski yerine yerleştiriyoruz. [ 2 , 6 , 16 , 22 , 18 , 27 ]
3. Üçüncü sayı zaten en küçük üçüncü sayı olduğundan işlem yapılmaz. [ 2 , 6 , 16 , 22 , 18 , 27 ]
4. Dördüncü en küçük sayı 18'dir. 22 ile 18 sayısının yerleri değiştirilir. [ 2 , 6 , 16 , 18 , 22 , 27 ]
5. Beşinci sayı zaten en küçük beşinci sayı olduğundan işlem yapılmaz. 
6. Sıralanacak eleman kalmadığından elimizdeki dizi sıralanmış olarak elde edilmiştir. [ 2 , 6 , 16 , 18 , 22 , 27 ]


                            

## Big-O Gösterimi

En başta dizide n tane sayı olduğunu varsayalım.

1. Yapılan işlem sayısını bulmalıyız.
    1. Yapılan işlem sayısı baktığımızda ilk olarak 2 sayısının yeri değişti, bu işlemde bulunan eleman sayısı n. Sonra 6'nın yeri değişti, bu işlemde bulunan eleman sayısı n-1. Bu şekilde son sayıya kadar devam eder yani 1 olana kadar. O zaman yapılan işlem sayısı n + (n-1) + (n-2) + ... + 1 şeklinde olur.
    2. 1'den n'ye kadar olan sayıların toplamı [n.(n+1)] / 2 formülüyle bulabiliriz.
    3. Buradan yapılan işlem sayısının formülü (n²+n) / 2 olarak bulunur.
2. Big - O notion'ı bulabilmek için fonksiyonu en büyük en büyük domine edeni alıyorduk. " n² " ifadesinde kare olduğu için fonksiyon olarak seçilir.
3. Big - O notion = O( n² ) olmaktadır.

              
               

## Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız 

Average case, aradığımız sayının ortada olması. Worst case, aradığımız sayının sonda olması. Best case, aradığımız sayının dizinin en başında olması.

Aradığımız sayı, ortada yer aldığından ***average case*** kapsamına girer.

              
                       

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. En küçük sayıyı alıp baştaki sayı ile yerlerini değiştir. [2,3,5,8,7,9,4,15,6]
2. İkinci sayı zaten en küçük İkinci sayı olduğundan işlem yapılmaz. [2,3,5,8,7,9,4,15,6]
3. Üçüncü en küçük sayı 4. 4'ü alıp üçüncü sıraya koyuyoruz ve üçüncü sırada olan 5'i alıp 4'ün eski yerine yerleştiriyoruz. [2,3,4,8,7,9,5,15,6]
4. Dördüncü en küçük sayı 5'tir. 8 ile 5 sayısının yerleri değiştirilir. [2,3,4,5,7,9,8,15,6]
5. Beşinci sayı zaten en küçük beşinci sayı olduğundan işlem yapılmaz. [2,3,4,5,7,9,8,15,6]
