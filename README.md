# MiniTalk
Minitalk protokolü, bit bit işlem yaparak veri aktarımını gerçekleştirir. İstemci, göndermek istediği her bir karakteri bitlere ayırır ve bu bitleri SIGUSR1 veya SIGUSR2 sinyalleriyle sunucuya gönderir. Sunucu ise bu sinyalleri alır ve bitlerin düzenini okuyarak karakteri oluşturur. Bu işlem, tüm veri gönderildiğinde veya bir hata oluştuğunda sona erer.

Minitalk, basit ve hafif bir iletişim protokolüdür ve özellikle düşük seviyeli sistem programlaması veya ağ programlaması gibi durumlarda kullanışlıdır. İletişimin hızlı olması ve düşük bellek tüketimi gibi avantajlara sahiptir.
