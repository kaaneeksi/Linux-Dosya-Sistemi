# Linux Dosya Sistemi

![linux-dosya-sistemi](https://github.com/kaaneeksi/Linux-Dosya-Sistemi-Hiyerarsisi/blob/main/linux-dosya-sistemi.png?raw=true)

## / | Root | Kök Dizin

İsimden de anlaşılaceği gibi dosya sisteminin başlangıcını temsil eder, `/` işareti ile gösterilir, diğer bütün dizinler kök dizinin altında yer alır ve  kök dizin linux sisteminin başlatılabilmesi için gerekli olan bütün dosyları içermelidir.

---

## /bin & /sbin
`/bin`  (**Bin**ary) tüm kullanıcıların erişebiliceği temel işlevleri gerçekleştirmek için kullanılan programları içeren dizindir.

`/sbin`  (**S**ystem **Bin**aries) sistem yöneticisi tarafından kullanılan, sistem yönetimi ve bakımı ile ilgili programları içeren dizindir.

---

## /boot

`/boot` ön yükleme aşaması için gerekli olan dosyaları barındıran dizindir.

---

## /dev

`/dev` (**Dev**ices) kelimesinin kısaltmasıdır bu sebeble ki sisteme bağlı olan donanım aygıtlarını temsil eden aygıt dosyalarını içerir.

---

## /etc

`/etc` dizini sistemde konfigürasyon dosyalarını barındıran dizindir. Hizmet yapılandırması ve temel ayar değişiklikleri için genellikle **etc** dosyasını kullanırız.

---

## /home

 `/home` dizini içinde sistemi kullanan kullanıcıların şahsi klasörleri olur. `/home/kullanıcı-adı` dizinde `/Desktop , /Documents , /Downloads ,...` dosyaları bulunur. 

 ---

 ## /lib

 `/lib` (**Lib**rary) sistemdeki araçların ortak olarak kullandığı dosyaları barındıran dizindir. Bu şekilde aynı dosyaların bellekte yer işgal etmesi önleniyor. 
 
 `lib64`,`lib32`,`libx32` gibi dizinler uyumluluk için 32 ve 64 bit kütüphane dosyalarını barındırıyor.

 ---

 ## /usr

 `/usr` dizini neredeyse bütün komut dosyalarının, kütüphanelerin ve dökümantasyonlarla beraber sistemin işleyişi için gerekli olan dosyaların tutulduğu dizindir. Aslında `lib,bin,sbin` `/usr` dizini altında çalışır
