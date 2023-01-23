<a href="https://app.patika.dev/nisacerenunnu">
    <img alt="patika" title="Patika" src="https://custom-icon-badges.demolab.com/badge/Patika.dev  |  nisacerenunnu-FF6600.svg?logo=patika_beyaz&logo_Color=white&style=flat-square&labelColor=FF6600"/>
    </a>
    
  
## [16,21,11,8,12,22] -> Merge Sort dizinin sort türüne göre aşamalarını ve Big-O gösterimini yazınız.
  
  
```markdown

                                            [ 16 , 21 , 11 , 8 , 12 , 22 ]

                                            /                              \

                                   [ 16 , 21 , 11 ]                    [ 8 , 12 , 22 ]

                                     /          \                        /          \

                               [ 16 , 21 ]      [ 11 ]             [ 8 , 12 ]       [ 22 ]

                                /       \           \              /        \            \

                            [ 16 ]     [ 21 ]      [ 11 ]       [ 8 ]      [ 12 ]       [ 22 ]

                                \       /            /              \        /            /

                               [ 16 , 21 ]       [ 11 ]             [ 8 , 12 ]        [ 22 ]

                                    \             /                     \             /

                                   [ 11 , 16 , 21 ]                     [ 8 , 12 , 22 ]

                                              \                            /

                                              [ 8 , 11 , 12 , 16 , 21 , 22 ]
```
  
Yarıya bölerek büyük ve küçük sıralaması yapıldığından 2ˣ = n olarak eleman sayısına eşitlenir. x'i yalnız bırakaırsak yapılan işlem sayısını öğrenmiş oluruz. x = log₂n olur. Ancak Big-O Notion'da katsayıları, tabanları görmezden gelerek sadece fonksiyonu ele alırız. Yani x = logn olarak kabul ederiz. Bulduğumuz logn tek satırın işlemi için geçerliydi. Eleman sayısı kadar işlem yapılacağı için logn'yi n (eleman sayısı) ile çarparız ve Big-O gösterimini nlogn olarak elde ederiz.
  
Bu dizinin Big-O gösterimi : O(nlogn)
