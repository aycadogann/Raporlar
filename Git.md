**ls ->** bulunduğumuz klasörün içindeki dosya ve klasörleri gösterir

**cd *klasör\_adı* ->** o klasörün içine yerleşir.                              *cd:change directory*

**cd .. ->** bir üst dizine/klasöre çıkılır.

**clear ->** ekranı temizle

**mkdir *klasör\_adı* ->** klasör oluştur                                       *mkdir:make directory*



**GİT**

Git, bir versiyon kontrol sistemidir. Sadece yazılım geliştirirken değil, kitap yazarken, ödev yaparken de kullanılabilir.



**git config --global user.name "*kullanıcı\_adı*"** 

**git config --global user.email "*mail\_adresi*"**  - git'e kullanıcı adı ve mail kaydetme komutu



**git status**            	 - Klasörün güncel git durumunu gösterir.

**git init**              	 - Bulunduğu klasörde git'i başlatır.

**git add *dosya\_adı***     - Dosyayı staging area'ya ekler.
**git add .**				 - Klasördeki tüm değiştirilmiş dosyaları staging area'ya ekler.

**git commit -m "*mesaj*"**  - Staging area'daki dosyayı local repository kaydeder. Bir save point noktası oluşturur.
							   Her commit'in kendine ait bir hash var.

**git log**					 - Commit geçmişini listeler.

**.gitignore**				 - git tarafından takip edilmeyecek dosyaların, dosya uzantılarının yazdığı bir dosyadır.


