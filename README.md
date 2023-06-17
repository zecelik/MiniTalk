# MiniTalk
Minitalk protokolü, bit bit işlem yaparak veri aktarımını gerçekleştirir. İstemci, göndermek istediği her bir karakteri bitlere ayırır ve bu bitleri SIGUSR1 veya SIGUSR2 sinyalleriyle sunucuya gönderir. Sunucu ise bu sinyalleri alır ve bitlerin düzenini okuyarak karakteri oluşturur. Bu işlem, tüm veri gönderildiğinde veya bir hata oluştuğunda sona erer.
