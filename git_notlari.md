staging area bizim gorebilecegimiz bir sey degil. burada somut olarak algilayabilecegimiz tek sistem working space. staging area ve commit store soyut alanlar. staging area gecici olarak versiyonlarin depolandigi bir yer. calisma alanimda (working space) bir dosya uretiyorum. orada olusturdugum yapiyi oncelikle staging area ya gonderiyorum gecici bir sekilde orada tutuluyor. karar verip de bunun bir versiyonunu olusturacagim dersem o zaman bu versiyon staging areadan commit store a gonderilir. commit store lokalimizde versiyonlarin tutuldugu yerdir.

<font color = 'red'>working space --> staging area </font>

**git add .**

*git add dosya_adi
<br />git add .*

<font color = 'red'>staging area --> commit store</font>

**git commit -m"mesaj"**

----------------------------

**git status** --> working space veya staging area'nin durumunu gormek icin kullanilir

**git init** - bunu bir dosya icin bir kez kullaniriz, baslangicta kullaniriz

---------------------------------------------------------

**U** --> untracked, bu dosyayi takip etmiyorsun (dosya adi yaninda cikar)

**M** --> modifiye edildi

--------------------------------------------------------