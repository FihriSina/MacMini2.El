# Mac-Mini-Tutorial

1.	Dış Cephesine Bak.
2.	Port Kontrolleri
3.	Fan Izgaralarına bak.(Toz)
4.	Adaptör Kablo fiziki kontrol
5.	Cihazı açarken 5 10 sn civarında apple logosu gelmeli
6.	Seri numara kontol
7.	ICloud testi
8.	Apple Diagnostics
9.	SSD testi






















💻 2. EL MAC MINI TEST REHBERİ (ADIM ADIM)
🟢 1. ADIM – Cihazı eline alınca ilk yapacakların
1.	Mac mini’yi eline al.
o	Alt kısmına ve arkasına bak: ezik, çizik, yamukluk, vida izi, darbe izi var mı?
§	➕ Normal: ufak çizikler olabilir.
§	❌ Kötü: gövde eğri, köşede ezik, vida izleri (içini açmış olabilir).
1.	Portları (USB, HDMI, Ethernet, kulaklık girişi) incele.
o	Hepsi düz olmalı, kablo taktığında gevşeklik olmamalı.
§	➕ Normal: kablo sıkı oturuyor.
§	❌ Kötü: kablo sallanınca bağlantı kesiliyor.
1.	Fan ızgaralarına bak.
o	Çok tozluysa uzun süre temizlenmemiştir, ısınma sorunu olabilir.
1.	Adaptör kablosuna bak (varsa).
o	➕ Normal: temiz, yanık izi yok.
o	❌ Kötü: ucunda siyahlık veya yanık kokusu varsa alma.
🔢 2. ADIM – Seri numarasını kontrol et
1.	Cihazın seri numarasını bul:
o	Alt kısmında küçük gri yazıyla yazar: “Serial Number: XXXXXXXX…”
o	Veya cihaz açıkken ekranın sol üst köşesindeki  > Bu Mac Hakkında menüsünden görebilirsin.
1.	Tarayıcıdan bu siteye git 👉
 🔗 https://checkcoverage.apple.com/
2.	Açılan sayfada:
o	Seri numarasını yaz.
o	Güvenlik kodunu gir.
o	“Continue” butonuna bas.
1.	Karşına bazı bilgiler çıkacak:
o	Model adı: (örneğin “Mac mini (M1, 2020)”).
§	➕ Model cihazın üstündekiyle aynı olmalı.
o	Valid Purchase Date (Satın alma tarihi geçerli)
§	➕ Yazıyorsa: cihaz Apple tarafından tanınıyor, sahte değil.
o	Repairs and Service Coverage
§	“Active” yazıyorsa garantisi var → harika!
§	“Expired” yazıyorsa garanti bitmiş → normal (ama bilin).
o	Find My (Bul) etkin mi?
§	Bu sitede görünmez, ama ileride test edeceğiz.
❌ Eğer “Invalid Serial Number” veya “Please enter a valid serial” yazarsa → sahte ya da değiştirilmiş cihaz olabilir. Alma.
🧠 3. ADIM – Açılış testi (güç, sistem, fan)
1.	Güç kablosunu tak.
2.	Cihazı aç (arka tuş).
3.	Bekle: Apple logosu 5–10 saniye içinde gelmeli.
o	➕ Normal: 10 saniyeden kısa sürede Apple logosu gelir, yüklenir.
o	❌ Kötü: çok geç açılıyor, bip sesi, siyah ekran, ya da fan gürültüsü → donanım sorunu olabilir.
1.	Cihaz açıldıktan sonra ekran geliyorsa, macOS normal görünüyorsa iyi.
🔐 4. ADIM – iCloud / Aktivasyon kilidi testi
Bu en kritik adımdır! Çünkü cihaz çalıntı olabilir.
Eğer kurulum ekranı geliyorsa:
1.	“Select your country / language” ekranından geç →
 Eğer Apple ID (mail) şifresi isteyen ekran gelirse:
 ❌ Kilitli cihaz → ASLA alma.
Eğer macOS içine girmişsen:
1.	Sol üstten  > Sistem Ayarları > Apple ID kısmına gir.
o	Eğer satıcının adı / e-posta adresi görünüyorsa:
 ❌ Satıcı çıkış yapmamış, cihaz hâlâ onun hesabına bağlı.
 Ona “Çıkış yap” de.
o	Çıkış yaptıktan sonra yeniden başlat → Apple ID istememeli.
⚙️ 5. ADIM – Apple Diagnostics (donanım testi)
Bu test Apple’ın kendi iç testidir.
1.	Cihazı kapat.
2.	Güç tuşuna basarken aynı anda D tuşunu basılı tut.
3.	“Apple Diagnostics” yazar veya test otomatik başlar.
4.	Yaklaşık 2–3 dakika sürer.
Sonuç ekranı:
·	“No issues found” veya “All tests passed” → ➕ Her şey sağlam.
·	“Error code: PPF…” veya benzeri hata kodu → ❌ Arıza var (kod not alın).
Kod varsa: Apple sitesine hata kodunu yazıp anlamına bak. “PPF” = fan, “PPT” = güç, “VFD” = ekran gibi.
 Donanım hatası varsa almayın veya fiyatı ciddi indirin.
💽 6. ADIM – Disk (SSD) testi
1.	Cihaz açıkken: Finder → Uygulamalar → Disk İzlencesi (Disk Utility) aç.
2.	Solda “Macintosh HD” yazan diski seç.
3.	Üstte “İlk Yardım (First Aid)” butonuna tıkla → “Çalıştır (Run)” de.
4.	İşlem 1–2 dakika sürecek.
Sonuç:
·	➕ “Disk başarıyla doğrulandı / Onarım başarılı.” → Tamam.
·	⚠️ “Uyarılar var ama onarıldı.” → İdare eder, dikkat et.
·	❌ “Onarım başarısız oldu / Disk hatalı.” → Disk arızalı, alma.
🧩 7. ADIM – Bağlantı portlarını test et
1.	Her USB girişine bir şey tak (örneğin USB bellek, fare, klavye).
o	Finder’da USB bellek görünmeli.
1.	HDMI çıkışını monitöre veya TV’ye tak.
o	Görüntü hemen gelmeli.
1.	Ethernet (kablolu internet) varsa tak, “Yeşil nokta” yanmalı (Sistem Ayarları > Ağ).
Sonuç:
·	➕ Tüm portlar çalışıyor → iyi.
·	❌ Bazı portlar çalışmıyor → anakartta arıza olabilir, tamiri pahalı.
🔊 8. ADIM – Ses, mikrofon, Wi-Fi ve Bluetooth
1.	YouTube aç, bir video oynat.
o	➕ Ses net geliyorsa tamam.
o	❌ Cızırtı, yankı varsa hoparlör sorunu.
1.	Kulaklık tak, ses geliyor mu dinle.
o	❌ Tek kulaktan geliyorsa jack arızalı.
1.	Wi-Fi’ye bağlan, birkaç site aç (örnek: apple.com, youtube.com).
o	➕ Sorunsuz bağlanıyorsa tamam.
o	❌ Sürekli kopuyorsa Wi-Fi anteni arızalı olabilir.
1.	Bluetooth cihazı (telefon, kulaklık) bağla.
o	➕ Bağlanıyorsa tamam.
o	❌ Bağlanmıyorsa veya kopuyorsa donanım problemi olabilir.
🌡️ 9. ADIM – Isınma ve fan sesi
1.	Aynı anda birkaç şey aç: Safari (3 sekme), YouTube videosu, bir film dosyası.
2.	Elini üst kısmına koy, fan sesini dinle.
o	➕ Hafif ısınma ve yumuşak fan sesi = normal.
o	❌ Aşırı sıcak, yanma kokusu, “cırt” ya da “tık tık” sesi = fan veya termal sorun.
💾 10. ADIM – Sistem bilgileri kontrolü
1.	Sol üstten  > Bu Mac Hakkında seç.
o	Burada göreceksin:
§	Mac mini (Yıl, Çip türü) → örnek: “Mac mini (M1, 2020)”
§	Bellek (RAM) → en az 8 GB olmalı.
§	Depolama → 256 GB veya daha fazlası tercih edilir.
1.	Sistem Raporu tuşuna bas:
o	“Denetleyiciler” kısmında “T2 Security Chip” yazıyorsa: güzel (ek güvenlik).
o	Yoksa da sorun değil ama yeni modellerde olur.
📊 11. ADIM – Disk Hız testi (isteğe bağlı ama faydalı)
1.	“Blackmagic Disk Speed Test” uygulamasını Mac App Store’dan indir.
2.	Aç → “Select Target Drive” kısmında ana diski seç → “Start”a tıkla.
3.	Test 1 dakika sürer.
o	➕ M1/M2 modellerde 2000 MB/s civarı okuma-yazma = çok iyi.
o	⚠️ 500 MB/s altı = yavaş SSD (eski model).
o	❌ 100 MB/s civarı = SSD sorunlu veya bozulmak üzere.
⚠️ 12. ADIM – Son kontrol (reddetme sebepleri)
Aşağıdakilerden biri bile varsa ASLA ALMA:
·	iCloud hesabı aktif veya Apple ID şifre istiyor.
·	Apple Diagnostics hata kodu verdi.
·	Disk İzlencesi “Onarım başarısız” dedi.
·	Portlardan biri bile çalışmıyor.
·	Aşırı ısınma / fan sesleri var.
·	“Seri numarası geçersiz” veya Apple sitesinde çıkmıyor.
·	Satıcı “sıfırlamayalım, sonra yaparsın” diyorsa → reddet.
🧾 13. ADIM – Satın alma sırasında
1.	Satıcıdan seri numarasını fatura veya satış belgesine yazmasını iste.
2.	Ödemeyi banka üzerinden yap (nakitte mutlaka yazılı belge al).
3.	Son kez sıfırlama yaptır:
o	Ayarlar > Genel > Aktar veya Mac’i Sıfırla > Tüm İçeriği ve Ayarları Sil
o	Kurulum ekranı geldiğinde durdur, cihazın tamamen sana ait olduğuna emin ol.
✅ KISACA “GEÇTİ / KALDI” ÖZETİ
Test	Beklenen Sonuç	Sonuç Kötüyse
Fiziksel Durum	Ufak çizikler normal	Ezik / yamuk → alma
Seri Numarası	Apple sitesinde geçerli	Geçersiz → alma
iCloud	Kapalı / Sıfırlanmış	Açık → alma
Disk	First Aid başarılı	Hata → alma
Apple Diagnostics	“No issues found”	Hata kodu → alma
Fan / Isı	Sessiz / normal ısınma	Aşırı sıcak / ses → alma
Portlar	Hepsi çalışıyor	Çalışmayan varsa pazarlık veya alma
Wi-Fi / Bluetooth	Kopmadan bağlanıyor	Sürekli kopuyorsa alma



