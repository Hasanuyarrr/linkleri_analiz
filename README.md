# linkleri_analiz

🚨 Pentester’lar ve OSINT meraklıları için mini bir araç!
Yeni bir araştırma yaparken, bir web sayfasındaki tüm linkleri manuel incelemek zaman kaybettirici olabilir. Bu durumu kolaylaştırmak için JavaScript tabanlı, konsoldan çalışan ama aynı zamanda tarayıcıya bookmark olarak eklenebilecek bir kod parçası yazdım.

🔎 Bu script ile:
✅ Sayfadaki tüm linkleri topluyoruz
✅ İçerdikleri parametreleri analiz ediyoruz
✅ Dorking mantığıyla belirli keyword’lere göre filtreleme yapabiliyoruz

Özellikle XSS, LFI veya IDOR gibi zafiyetlerin pasif izleme safhasında size ciddi zaman kazandırabilir.
İsterseniz “bookmarklet” olarak kaydedip tek tıkla çalıştırabilir, isterseniz doğrudan console üzerinden kullanabilirsiniz.

💻 Kodun temel mantığı:

document.querySelectorAll('a') ile tüm <a> etiketlerini yakalıyoruz

Her linkin href’ini URLSearchParams ile parse edip parametreleri listeliyoruz

Gelişmiş: Belirli dork’lara göre eşleşme kontrolü yapılabiliyor

🔗 Bookmarklet olarak nasıl kullanılır?
Kodu javascript: ile başlayan tek satır haline getirip tarayıcınızın yer imlerine eklemeniz yeterli.

Kodun tam halini ve kullanım videosunu yorumlara bırakıyorum.
Deneyenler mutlaka geri bildirim versin! 🚀

#infosec #websecurity #bookmarklet #javascript #bugbounty #osint #xss #pentest #securityresearch #cybersecurity
