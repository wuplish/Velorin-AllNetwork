selamlar arkadaşlar hemen nasıl çalıştığını söyleyim;

Velorin.exe'yi %localappdata%/Velorin/ içine atın yoksa klasörü açın
Logger veya Patcher'ı açın attığınız Velorin.exe'yi binnary patch atarak 0x393F78 değerini değiştiricek.
Patcher bazı istekleri otomatik cahce klasöründen veri alıp o veriyi gösterir örnek skin dataları vb dll'ide cahceden alır
Logger sıkıntısız çalışır Logger'ı açıp Velorin'i açarsanız tüm istekleri görebilirsiniz.




bazı login istekleri (http tarafı)


{ // status 200

&#x20;  "avatarUrl" : "https://api.velorin.cc/uploads/avatars/dca972a5-7afb-48f7-9254-b2ba0d31a331\_1788992773.png",

&#x20;  "displayName" : "wuplish",

&#x20;  "email" : "",

&#x20;  "expiresAt" : "",

&#x20;  "isAdmin" : ,

&#x20;  "isPremium" : ,

&#x20;  "refreshToken" : "",

&#x20;  "role" : "user",

&#x20;  "sessionSecret" : "",

&#x20;  "subscription" : "",

&#x20;  "subscriptionEnd" : "",

&#x20;  "subscriptionEndUnix" : ,

&#x20;  "subscriptionProof" : "",

&#x20;  "token" : "",

&#x20;  "userId" : "1",

&#x20;  "username" : "wuplish"

}





{ // status 401

&#x20;  "code" : "invalid\_credentials",

&#x20;  "error" : "Kullanıcı adı veya şifre hatalı.",

&#x20;  "errorEn" : "Wrong username or password."

}



// status 402 Payment Required





bu taz şeyler işte anlatım bu kadardı

özel teşekkürler \*metox86\*

