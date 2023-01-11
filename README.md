<h2>Intersion Sort</h2>
<li> [22,27,16,2,18,6]--> Intersion Sort a göre ilk iki sayıyı karşılaştırırız.Sıralama doğru olduğu için değişim yoktur. </li>
<li> [22,16,27,2,18,6]--> 27 ve 16 yı kıyasladığımızda 16 27 den küçük olduğu için yerlerini değiştiririz.</li>
<li> [16,22,27,2,18,6]--> 22 ve 16 yı kıyasladığımızda 16 22 den küçük olduğu için yerlerini değiştiririz.</li>
<li> [16,22,2,27,18,6]--> Bir sonraki adımda 27 ve 2 yi kıyaslayıp 2 küçük olduğu için yerlerini değiştiririz.</li>
<li> [16,2,22,27,18,6]--> 22 ve 2 yi kıyasladığımızda 2 22 den küçük olduğu için yerlerini değiştiririz.</li>
<li> [2,16,22,27,18,6]--> 16 ve 2 yı kıyasladığımızda 16 22 den küçük olduğu için yerlerini değiştiririz.</li>
<li> [2,16,22,18,27,6]--> Bir sonraki adım olarak 27 ve 18 i kıyaslarız. 18 27 den küçük olduğu için yerlerini değiştiririz. </li>
<li> [2,16,18,22,27,6]--> 22 ve 18 i kıyaslarız. 18 22 den küçük olduğu için yerlerini değiştiririz. </li>
<li> [2,16,18,22,27,6]--> 16 ve 18 i kıyaslarız. 16 18 den küçük olduğu için hiçbir şey yapmadan diğer adıma geçeriz. </li>
<li> [2,16,18,22,6,27]--> Bir sonraki adımda 27 ve 6 yı kıyaslarız. 6 27 den küçük olduğu için yerlerini değiştiririz. </li>
<li> [2,16,18,6,22,27]--> 22 ve 6 yı kıyaslarız. 6 22 den küçük olduğu için yerlerini değiştiririz. </li>
<li> [2,16,6,18,22,27]--> 18 ve 6 yı kıyaslarız. 6 18 den küçük olduğu için yerlerini değiştiririz. </li>
<li> [2,6,16,18,22,27]--> 16 ve 6 yı kıyaslarız. 6 16 dan küçük olduğu için yerlerini değiştiririz. </li>
<li> [2,6,16,18,22,27]-->  2 ve 6 yı kıyaslarız. 2 6 dan küçük olduğu için hiçbir şey yapmadan diğer adıma geçeriz. </li>
<li> [2,6,16,18,22,27] şeklinde küçükten büyüğe sıralanmıştır.</li>

<h2>Big O Gösterimi</h2>
<li>O (n^2) şeklindedir.</li>
<h2>Time Complexity</h2>
<li>18 sayısı Time complexity'lerden ortada bulunduğundan dolayı Average Case kısmına girmektedir.</li>

<h2>Selection Sort</h2>
<li>[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı şu şekildedir;</li>
<li>[2,3,5,8,7,9,4,15,6] en küçük sayı 2 olduğu için en baştaki sayı olan 7 ile yer değiştirilir.</li>
<li>[2,3,5,8,7,9,4,15,6] ardından en küçük sayı olan 3 olduğu için herhangi bir değişim gerçekleşmez.</li>
<li>[2,3,4,8,7,9,5,15,6] bu işlemden sonra en küçük sayı 4 olduğu için 5 ile yer değiştirir.</li>
<li>[2,3,4,5,7,9,8,15,6] 4.adımda bir sonraki en küçük sayı 5 olduğundan dolayı 8 ile yer değiştirir.</li>
