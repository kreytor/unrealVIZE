Blueprint kuralları
Yeni bir şey eklemeden önce BP_MoveCharacter’daki mevcut graph’ları oku ve benim düzen tarzımı öğren: node’ların ne kadar aralıklı dizildiği, exec akışının yönü, değişkenleri nereye koyduğum, Get node’larını tekrar kullanıp kullanmadığım. Yeni node’ları aynı tarzda yerleştir.
Node’lar soldan sağa aksın, kablolar mümkün olduğunca üst üste binmesin. Gerekirse Reroute node kullan.
Her mantıklı bloğu (ör. “Havada mıyım kontrolü”, “Hız hesabı”) bir Comment kutusuna al. Comment başlıkları Türkçe, kısa ve sade olsun.
Değişken ve fonksiyon isimleri projedeki mevcut stile uysun (AirJumpsLeft, bCanDash gibi İngilizce PascalCase; boolean’lar b ile başlasın).
Bir öğrencinin yazacağı gibi sade tut: gereksiz optimizasyon, makro veya karmaşık yapı kullanma.
Var olan, çalışan node’ları bana sormadan silme veya değiştirme.
Her değişiklikten sonra compile et ve eklediğin node’ları, bağlantılarıyla birlikte Türkçe özetle.