## **AĞ TEMELLERİ**

# **IP**

İnternete veya yerel bir ağa bağlı her cihazın bilgi alışverişi yapmasını sağlayan bir kimlik numarasıdır, benzersizdir. 

						*192.168.1.1* - *Bir IP örneğidir*

Nokta ile ayrılmış dört gruptan oluşan bu sayısal değerleri akılda tutmak zor olduğu için IP adreslerine karşılık gelen alan adları vardır. 

Şuan IPv4 kullanıyoruz ama yetersiz geldiği için IPv6 geliştirilmiştir.


# **PORT**

Bir cihazın dış dünya ile iletişim kurmak için kullandığı kapıdır. Fiziksel ve sanal olmak üzere ikiye ayrılır.

**Fiziksel Portlar**

Cihazımızın üzerinde bulunan giriş/çıkış noktalarıdır. *USB*, *HDMI* gibi...

**Sanal Portlar**

Sanal kapılar olarak da adlandırabiliriz. Bir cihazın belirli bir görevi yerine getirmek için kullandığı yazılım tabanlı özel ağ kapılarıdır. *Port numarası* üzerinden iletişim sağlanır.

IP adresinden sonra :(iki nokta) eklenerek port numarası yazılır.

			*192.168.1.1:443* 

Aşağıdaki görselde uygulamalar ve portları yer almaktadır

![Sanal Portlar](https://miro.medium.com/v2/resize:fit:1200/1*8oi5Ultq-6DhRKYas7TrnA.png)


# **TCP (Transmission Control Protocol)**

Bilgisayarlar arasındaki veri iletişimi küçük paketler halinde ve kayıpsız olarak gerçekleşmesini sağlayan bir ağ protokoldür.

En önemli özelliği veriyi gönderirken ve alırken kimlik doğrulaması yapmasıdır. 

Bu protokolde veri paketleri kaybolmaz, eksik geldiğinde tekrar istek gönderilerek paketlerin tamamının alınması sağlanır. Böylece veri bütünlüğü korunmuş olur.

Bu protokol üç aşamada gerçekleşir. İlk aşamada bağlantı için istek gönderilir. İkinci aşamada veri gönderilir. Üçüncü aşamada ise veri gönderme işlemi biter ve bağlantı sonlandırılır.


# **UDP (User Datagram Protocol)**

Verileri bağlantı kurmadan iletir. Hızlıdır ama veri kayıpları yaşanabilir. Güvenli değildir. 

Ses ya da görüntü aktarımında kullanılabilir.


# **DNS (Domain Name Server)**



