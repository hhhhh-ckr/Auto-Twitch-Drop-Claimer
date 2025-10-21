<a alt="English" href="/README.md" target="_blank" style="text-decoration: none">
  <img src="https://img.shields.io/badge/language-English-blue?style=flat">
</a>
&nbsp;
<a alt="Turkish" href="/README-tr.md" target="_blank" style="text-decoration: none">
  <img src="https://img.shields.io/badge/language-Turkish-red?style=flat">
</a>
&nbsp;
<a alt="Greasy Fork Page" href="https://greasyfork.org/tr/scripts/553315-auto-twitch-drop-claimer" target="_blank" style="text-decoration: none">
  <img src="https://img.shields.io/badge/Greasy_Fork-gray?style=flat&logo=greasyfork&logoColor=black">
</a>

### Otomatik Twitch Drop Toplayıcı

Bu kullanıcı betiği (**userscript**), **Twitch Drop Envanteri** sayfasında Drop’ları senin için otomatik olarak toplar.

#### 🧩 Nasıl çalışır
[https://www.twitch.tv/drops/inventory](https://www.twitch.tv/drops/inventory) sayfasını açtığında, betik sürekli olarak **“Şimdi Al”** butonlarını izler.  
Yeni bir toplanabilir drop olduğunda, hiçbir şey yapmana gerek kalmadan otomatik olarak butona tıklar.

Arka planda çalışan bir gözlemci (`MutationObserver`), sayfadaki değişiklikleri algılar ve toplama işlemini otomatik olarak tetikler.  
Oturumunun güncel kalması için, betik envanter sayfasını varsayılan olarak her **5 dakikada bir** yeniler.

#### ⚙️ Temel özellikler
- “Şimdi Al” butonlarını otomatik algılar ve tıklar.  
- Tamamen tarayıcı içinde çalışır — hiçbir harici sunucu veya API kullanmaz.  
- Hafif, açık kaynaklı ve okunabilir koddur.  

#### 🔒 Gizlilik ve güvenlik
- Betik **herhangi bir kullanıcı verisi toplamaz veya göndermez.**  
- **Takip, reklam veya gizli istekler** içermez.  
- Tüm işlemler yalnızca tarayıcında, Twitch sitesinde gerçekleşir.

#### 💡 Notlar
- Sayfanın ne sıklıkta yenileneceğini değiştirmek için koddaki `refreshMinute` değerini düzenleyebilirsin.  
- Yalnızca Twitch’in Drop Envanteri sayfasında çalışır.  
- Drop envanteri sayfasını açtığında, betiğin etkinleşmesi için sayfayı en az bir kez yenilemen gerekebilir. </br>
  Kullanıcı betiği yöneticinde betiğin etkin olduğundan emin ol. </br>
  <img width=auto alt="image" src="https://github.com/user-attachments/assets/99c4935d-d042-4a05-8bff-4953c8e3f599" />

</br>

#### ℹ AFK Drop Toplamak için Örnek Canlı Yayın İzleme
<img width=auto src="https://github.com/user-attachments/assets/56f83312-dcfa-4a1e-925a-1f1c16ee9766" />
