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

**git branch**				 - Güncel branch'leri gösterir.
**git branch branch_adı**	 - Yeni branch oluşturur.

**git switch branch_adı**	 - Branch değiştirmemizi sağlar.

**git merge branch_adı**	 - main branch'teyken başka bir branch'te yapılan değişiklikleri birleştirmek istediğimizde kullanılır.

**git stash**				 - Kodlarım commit etmeye hazır olmadığında, farklı bir branch'te yapılması gereken bir iş olduğunda 
							   bu komut ile git hazır olmayan kodları kendi içinde bir alanda saklıyor.
**git stash pop**			 - Saklakdığımız kodları tekrar çalışma alanımıza ekliyor. Birden fazla stash varsa hepsini ekler.

**git restore dosya_adı**    - Bu komut ile uygulamamızın bir önceki commit'teki haline geri dönüyoruz.

**git checkout commit_id**	 - Uygulamayı yazılan commit id'deki haline döndürür. Burada dikkat edilmesi gereken nokta eski 
							   commit'e dönsek bile main branch'teki uygulama son commit'te kalıyor. Bu yüzden eski commit'e 
							   döndüğümüz yer için yeni bir branch açmalıyız.

**git reset commit_id**		 - Verilen commit id'den sonraki commit'leri siler ama uygulamada yapılan değişiklikler silinmez.

**git reset hard commit_id** - Verilen commit id'den sonraki commitleri siler, uygulamada yapılan değişiklikleri de siler.

**git revert commit_id**	 - main branch'teyken hem commit'i hem de uygulamadaki değişiklikleri git'e eklemek istediğim zaman 
							   ayrıca checkout'taki gibi farklı bir branch eklemeden main branch'ten devam etmek istediğim zaman kullanabilirim.

							   
