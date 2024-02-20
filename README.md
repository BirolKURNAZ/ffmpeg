# FFMPEG


<div align="center"; color="blue">
  mp4 to mkv convert
</div>
---

```
ffmpeg -i girdi.mp4 -c:v copy -c:a copy çıktı.mkv
```

```
ffmpeg -i girdi.mp4 -s hd720 -c:v libx264 -crf 23 -c:a aac -strict -2 çıktı.mkv
```

```
ffmpeg -i input.mp4 -s hd720 -c:v libx264 -crf 23 -c:a aac -strict -2 output.mkv
```


	* -i grdi.mp4 	: Girdi dosyasının adını belirtir.
	* -s hd720		: Çıktı dosyasının çözünürlüğünü belirtir (720p).
	* -c:v libx264	: Video codec'i olarak libx264'ü kullanır.
	* -crf 23		: Video kalitesini belirtir. 
 				Daha düşük bir sayı, daha yüksek kalite anlamına gelir.
	* -c:a acc		: Ses codec'i olarak acc'yi kullanır.
	* -strict -2	: ACC ses codec'i için gerekli olan ekstra parametreleri belirtir.

<p> -crf 23 değeri 18 ile 24 arasında bir değer alabilir. </p>
<p> Bu değer ne kadar düşerse, o kadar yüksek kalitede bir video elde edilir. </p>
<p> Daha yüksek bir değer, daha düşük bir kalite anlamına gelir. </p>
<p> Örneğin, </p>
<p> -crf 18 çok yüksek kalitede bir video üretirken, </p>
<p> -crf 24 daha düşük bir kaliteye sahip olacaktır.</p>
<p> </p>
<p> </p>

<p> </p>
<p> </p>
 



	
	

---

-
--
---
----
-----
------

