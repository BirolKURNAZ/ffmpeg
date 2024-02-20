# FFMPEG


#### <span style="color: blue;">Merhaba</span>

<p style="text-align: center; font-family: 'Roboto'; color: blue; font-size: 2.5em;">mp4 to mkv convert</p>

***<p style="text-align: center;">Text with basic formatting applied</p>***

<div align="center" color="blue">
  my text here.
</div>
---

ffmpeg -i girdi.mp4 -c:v copy -c:a copy çıktı.mkv

ffmpeg -i girdi.mp4 -s hd720 -c:v libx264 -crf 23 -c:a aac -strict -2 çıktı.mkv

ffmpeg -i input.mp4 -s hd720 -c:v libx264 -crf 23 -c:a aac -strict -2 output.mkv

	* -i grdi.mp4 	: Girdi dosyasının adını belirtir.
	* -s hd720		: Çıktı dosyasının çözünürlüğünü belirtir (720p).
	* -c:v libx264	: Video codec'i olarak libx264'ü kullanır.
	* -crf 23		: Video kalitesini belirtir. Daha düşük bir sayı, daha yüksek kalite anlamına gelir.
	* -c:a acc		: Ses codec'i olarak acc'yi kullanır.
	* -strict -2	: ACC ses codec'i için gerekli olan ekstra parametreleri belirtir.

-crf 23 değeri 18 ile 24 arasında bir değer alabilir. Bu değer ne kadar düşerse, o kadar yüksek kalitede bir
video elde edilir. Daha yüksek bir değer, daha düşük bir kalite anlamına gelir. Örneğin, -crf 18 çok yüksek
kalitede bir video üretirken, -crf 24 daha düşük bir kaliteye sahip olacaktır.

---



<span style="font-size:2.5em;color:blue;">-</span>

<span style="font-size:0.7em;">Şahsım için Notlar.</span>


---

<font size="1.8em">Merhaba!</font>

<font color="blue">Merhaba!</font>

<center>Merhaba!</center>
---

