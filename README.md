# lejos-docs-turkish
Ev3'e java ile program yazılabilmesi için kullanılan leJOS'un dokümentasyonu.
## Gereksinimler 
* En fazla 32GB kapasiteli bir sd kart.
* Windows işletim sistemine sahip bir bilgisayar.
* Ev3. 
## Bilgisayara Java jdk ve jre Yüklenmesi
* Ev3 için javada program yazabilmek için bilgisayarınıza java development kit (**jdk**) ve java runtime environment (**jre**) yüklü olması gerekmektedir.
* [Java Development kit](http://www.oracle.com/technetwork/java/javase/downloads/jdk10-downloads-4416644.html)
* [Java Runtime Environment](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html)
* Linklerden girince **lisans sözleşmesini** kabul edip **Windows** a tıklayarak indirmenizi başlatabilirsiniz.
* İndirdikten sonra installerın size söylediği komutları gerçekleştirerek bilgisayarınıza java **jdk** ve **jre** yükleyebilirsiniz.

## Sd Kart Formatlama
32 GB'dan küçük bir sd kartınız var ise, içine lejos yüklemeden önce formatlamamız gerekecek. Formatlamak için de internetten bir program indirmemiz gerekiyor.
* [Sd kart formatlama programı](https://www.sdcard.org/downloads/formatter_4/)
* Aşağıdan **For Windows**'a tıklayınca sizi başka bir sayfaya yönlendirecektir. O sayfada lisans sözleşmesini kabul ettikten sonra indirmeniz başlayacaktır.
* İndirdikten sonra gelen installer sizi yönlendirecektir.
> Başka bir sd kart formatlama programı kullanabilirsiniz ama bazı programların çalışmadığı görülmüştür. Bu programı kullanmanız önerilmektedir.

## Sd Karta leJOS'un Yüklenmesi
Sd kartı formatladıktan sonra içine **jeJOS**'u yüklemeniz lazım. Bunun için de Ev3 java jre'yi indirmeniz lazım.
* [Ev3 Java jre](http://www.oracle.com/technetwork/java/embedded/downloads/javase/javaseemeddedev3-1982511.html)
* Ev3 java jre'yi indirdikten sonra masaüstüne atalım.

Ondan sonra da **Ev3 leJOS image**'ı indirmeniz lazım.
* [Ev3 leJOS image](https://sourceforge.net/projects/ev3.lejos.p/files/)
* Bunu da indirdikten sonra masaüstüne atın.

Son olarak **leJOS ev3 installer**'ı indirmeniz lazım.
* [leJOS ev3 installer](https://sourceforge.net/projects/ev3.lejos.p/files/)
* Bunu da masaüstüne atalım.

**leJOS ev3 installer**'ı çalıştırıp oradaki adımları uygulayalım.
Sd karta yükleme gerçekleştikten sonra sd kartı ev3'e takıp ev3 ü açalım. Bir ekran gelecek. Yeterince bekleyince ev3 açılacaktır.(uzun sürebilir)
## Bilgisayara Eclipse Kurulması
**Eclipse** açık kaynak bir **IDE**(integrated development environment). Eclipse'e **leJOS eklentilerini** yükledikten sonra robotumuza kod yazıp atabileceğiz.
	* [Eclipse](http://www.eclipse.org/downloads/packages/release/photon/r/eclipse-ide-java-developers)
	* Yanda **Windows 64-bit**'e tıklayıp, gelen sayfada da **Download**'a tıklayıp indirmenizi başlatabilirsiniz.
	* **Eclipse**'i çalıştırın.
	* Eğer bilgisayarınızda java yüklü olmamasıyla alakalı bir hata mesajı geliyorsa **Bilgisayara java jre ve jdk yüklenmesi** kısmını bir daha okuyun.
## Eclipse Eklentilerinin Yüklenmesi
* **Eclipse**'i açtıktan sonra yukarıdan help->install new software kısmına geldikten sonra **add** butonuna tıklayın.
* Çıkan menüde name kısmına **EV3 LEJOS PLUGINS**, location kısmına **http://lejos.sourceforge.net/tools/eclipse/plugin/ev3** yazın.
* Çıkan sorulara evet diyin.
## Ev3'e Program Atma ve Yararlı Kaynaklar
