

## 🇹🇷 Neden Bu Paneli Yaptım + Eksik Yanları

Bazı web siteleri, özellikle Render gibi ücretsiz servislerde barındırıldığında, bir süre trafik almazsa “uyku moduna” geçiyor. Yani site aslında yayında ama ilk açıldığında geç tepki veriyor. Bu da hem kullanıcıyı bekletiyor hem de SEO açısından kötü bir durum.

Ben de bu sorunu çözmek için küçük bir panel yaptım. Bu panel:
- Eklediğiniz sitelere arka planda düzenli olarak ping (küçük yoklama) gönderiyor.
- Böylece site sürekli aktif kalıyor, uykuya geçmiyor.
- Siteye ne kadar sürede yanıt verdiğini ölçüyor.
- Yanıt hızlıysa yeşil, yavaşsa veya hiç gelmediyse kırmızı gösteriyor.
- Bağlantılar tıklanabilir, yani doğrudan siteye gidebiliyorsunuz.

🔸 **Eksik tarafı ne?**  
Bu panelin çalışabilmesi için tarayıcınızda açık olması gerekiyor. Yani arka planda ping gönderebilmesi için uygulamanın aktif halde çalışıyor olması şart. Eğer panel kapalıysa ping gönderimi durur ve siteler tekrar uykuya geçebilir.

🔸 Ayrıca:  
- Ping gönderimi sadece tarayıcı açıkken yapılır, sunucu taraflı değildir.  
- Çok fazla site eklendiğinde tarayıcı performansını etkileyebilir.  
- Ping süresi sabit (5 dakika), ama bu süre bazı projeler için fazla ya da az olabilir.

Kısacası bu panel, sitelerin uyanık kalmasını sağlıyor ve durumlarını kolayca takip etmenizi sağlıyor. Hem sade hem işlevsel. Kod bilmeseniz bile mantığı çok basit: “Siteyi ara sıra yokla, uyanık tut.” Ama bunu yapabilmesi için panelin açık kalması gerekiyor.

---

## 🇬🇧 Why I Built This Panel + Limitations

Some websites, especially those hosted on free platforms like Render, go into “sleep mode” if they don’t get traffic for a while. That means the site is online, but when someone visits, it takes time to wake up. Not great for users or SEO.

So I built this simple panel to fix that. It:
- Sends small background pings to the sites you add.
- Keeps them awake so they respond faster.
- Measures how long it takes for each site to reply.
- Shows green if it’s fast, red if it’s slow or unreachable.
- You can click the links to visit the sites directly.

🔸 **What’s the downside?**  
The panel needs to be open in your browser to work. If it’s closed, it stops sending pings, and your sites may go back to sleep. It’s not a server-side tool—it only works while the app is running in the background.

🔸 Also:  
- Pings are sent only while the browser is active.  
- Adding too many sites may affect browser performance.  
- The ping interval is fixed (5 minutes), which may not suit every project.

In short, this panel helps your sites stay active and lets you track their status easily. Even if you don’t know how to code, the idea is simple: “Check the site now and then, keep it awake.” Just keep in mind—it only works while the panel is open.

---

Hazırsan bir sonraki adımda README’ye başlık, görsel veya kullanım örneği de ekleyebiliriz. Yardımcı olmamı ister misin? 😊
