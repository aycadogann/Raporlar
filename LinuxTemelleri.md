# Linux Temelleri

## Terminal Komutları

* **ls** - Bulunduğumuz dizindeki dosya ya da klasörleri listeler.

* **mkdir *[klasör_adi]*** - Yeni bir klasör oluşturur.		*mkdir : make directory*

* **cd *[dizin_adi]*** - Başka bir dizine geçiş yapar. 		*cd : change directory*

* **grep *[aranacak_kelime]* *[dosya.uzanti]*** - Dosya içinde arama yapar.		*grep : Global Regular Expression Print*

* **chmod** - Dosya veya klasörlerin erişim izinlerini değiştirmek için kullanılır.		*chomod : change mod*

* **top** - Çalışan işlemleri anlık izlememizi sağlar. 


## Paket Yönetimi

Linux'ta bir program sadece o programın kodlarından ibaret değildir. Genellikle çalışması için başka kütüphanelere, araçlara ve bağımlılıklara ihtiyaç duyar. Kurmak istediğiniz program X kütüphanesini ister, X kütüphanesi de Y kütüphanesinin 2.0 sürümünü ister ama sizin sisteminizde 1.0 vardır... Paket yönetimi programın tüm ihtiyaçlarını bir arada toplar.

Yazılımların kurulması, güncellenmesi, kaldırılması gibi işlemleri kapsar. Paket yöneticisi bu işlemleri merkezi ve güvenli bir şekilde yönetir. Dağıtımlara göre paket yöneticileri değişir.


**apt** - .deb uzantlı Debian ya da Ubuntu paketlerin yönetiminden sorumlu paket yöneticisidir.    *apt : advanced package tool*

**pacman** - Arch Linux'de kullanılan paketlerin yönetiminden sorumlu olan paket yöneticisidir.  *pacman : Package Manager*

**dnf** - Red Hat tabanlı sistemlerin paket yöneticisidir.  *dnf : Dandified YUM*