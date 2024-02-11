# Linux Dosya Sistemi

![linux-dosya-sistemi](https://github.com/kaaneeksi/Linux-Dosya-Sistemi/blob/main/G%C3%B6rseller/linux-dosya-sistemi.png?raw=true)

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

 `/usr` dizini neredeyse bütün komut dosyalarının, kütüphanelerin ve dökümantasyonlarla beraber sistemin işleyişi için gerekli olan dosyaların tutulduğu dizindir. 
 
 Aslında `lib,bin,sbin` `/usr` dizini altında çalışır

 ![usr](https://github.com/kaaneeksi/Linux-Dosya-Sistemi/blob/main/G%C3%B6rseller/usr-dizini.png?raw=true)

 ---

## /opt

`/opt` dizini harici olarak kurulan toolların dosyalarının barındırıldığı dizindir.

---

## /media & /mnt

`/media` ve `/mnt` dizinlerinin ikiside medya aygıtları için kullanılan dizinlerdir. 

Aralarında ki fark ise; 

`/media` dizini "USB bellek, harici disk, CD/DVD sürücüsü vb." gibi medya aygıtlarını bağlamak için kullanılırken,

`/mnt` dizini ise geçici olarak disk bölümlerini bağlamak için kullanılan bir dizindir.

---

## /proc

`/proc` (**proc**ess) dizini sistemde o anda çalışan işlemler hakkında bilgiler içeren sanal bir dosya sistemidir. 

 ---

 ## /tmp

 `/tmp` (**temp**orary) yani geçici ifadesinin kısaltmasından ismini almıştır. Geçici olarak tutulması gereken dosyalar ve klasörler için kullanılan bir dizindir. Bu dosyalar RAM üzerinde tutulduğu için sistem yeniden başlatıldığnda silinmiş olurlar.

 ---

 ## /root

 `/root` dizini root kullanıcısını **home** dizinidir. 

 ---

 ## /var

 `/var` (**var**iable) yani değişken kelimesinden geliyor.Bu dizinde Log dosyaları, çeşitli veri tabanı dosyaları ve benzeri pek çok veri bu dizinin altında tutulur.

 ---

 ## /sys

 `/sys` bu dizin bazı sistem bileşenleri ve sürücüler hakkında bilgiler içeren bir dizindir.

 ---

 ## /srv

 `/srv` (**s**e**rv**ice) sunucunun sunduğu çeşitli hizmetlerin (FTP ve Nginx gibi) tutuluduğu bir dizindir.

 ---

 ## /run

 `/run` Sistem başlangıcından itibaren, sistem kaynaklarının nasıl kullanıldığına dair çeşitli bilgileri tutan bir dizindir. Bu veriler, sistemin o anda çalışan işlemlerinin ihtiyaçlarını karşılamak için gerekli olan türde geçici verilerdir.
