# ⚡ Sayısal Sistemler (Lojik Devreler) — Abdülkadir Çakır Vize Kurtarma Kampı

Isparta Uygulamalı Bilimler Üniversitesi (ISUBÜ) Teknoloji Fakültesi Elektrik-Elektronik Mühendisliği **Sayısal Sistemler (Lojik Devreler)** dersi (**Prof. Dr. Abdülkadir Çakır**) için sıfırdan 90+ hedefleyen, tek dosyalık (`index.html`) interaktif **Son Gece Vize Kurtarma Rehberi**.

## 📚 İçerik ve Bölümler

1. **🛟 Bölüm 1: Taban Aritmetiği & Tümleyen (`r` ve `r-1`) Tuzakları**
   - Kesirli sayıların (`485.171875`) 2'lik, 8'lik ve 16'lık tabana tam kısım (bölme) ve kesirli kısım (çarpma) olarak adım adım çevrilmesi.
   - 16'lık (`Hex`) ↔ 8'lik (`Octal`) dönüşümünde 10'luk tabana uğramadan `4'lü aç → 3'lü grupla` kısayolu (`BC3D₁₆ → 136075₈`).
   - 🚨 **Sazan Tuzağı Kutusu:** `M = (11001)₂` ve `N = (101)₂` için `M - N` işleminde `N` sayısını `00101` yapmadan tümleyen alanların elenme tuzağı ve `r` / `r-1` tümleyen çıkarma akış şemaları.
   - 🧮 **Canlı Taban & Tümleyen Simülatörü.**

2. **🔢 Bölüm 2: Kodlama Sistemleri (Hileli Tablo)**
   - **BCD (8421)**, **Artı-3 (Excess-3)**, **Aiken (2421 - 0..4 normal, 5..9 simetrik)**, **5'te 2 Kodu (`74210` ağırlıklı, `0 = 11000` özel durumu)**, **Tek/Çift Parity**, **ASCII (7 bit)**, **EBCDIC (8 bit)** ve **Barkod (EAN-13)** karşılaştırmalı tablosu.
   - İkili ↔ Gray Kodu dönüşümünün görsel oklarla anlatımı ve **Canlı Kodlama Dönüştürücü**.

3. **📐 Bölüm 3: Boolean Cebri, Minterm/Maxterm & Sözel Hikaye Soruları**
   - De Morgan, Yutma ve Basitleştirme ($A + A'B = A + B$) kuralları.
   - İç içe parantezli klasik sınav sorularını ($F = AC + [(BC'D)' \cdot (A'+C)]' + B'D$) 2 adımda çözme taktiği.
   - 🎯 **Hoca Klasiği Sözel Problemler:** 55 kişilik mecliste 11'er kişilik 5 grup (salt çoğunluk 28 kişi → en az 3 bit `'1'`) ve 4 anahtardan sadece ikisi kapalıyken yanan lamba ($\sum(3,5,6,9,10,12)$).

4. **🗺️ Bölüm 4: Karnaugh Haritaları (2-6 Değişken), Don't Care (`X`) & Quine-McCluskey**
   - 3 ve 4 değişkenli renkli Karnaugh gruplama örnekleri ve Don't Care (`X`) jokeri kuralı.
   - 5 ve 6 değişkenli Karnaugh sorularında tablo çizmeden bit değişiminden 10 saniyede cevap bulma taktiği.
   - Quine-McCluskey (Tablo) yönteminin 2 adımda özeti (`1` sayısına göre gruplama ve Esas Asal Bileşen tek çarpı kuralı).

5. **🔌 Bölüm 5: Lojik Kapılar, Entegreler & Bileşik Devreler (`MUX` / `Decoder` / `ALU`)**
   - "En az kaç tane 2 girişli NAND / NOR kapısı gerekir?" algoritması ($L = AB'C + BC' + A'$ ve $A = m_0 + m_3 + m_4$).
   - Diyot matrisli Encoder'da 10 saniyelik `'1'` sayma hilesi (`2,3,4,5,6,7,8,10 → 14 diyot`).
   - $8 \times 1$ MUX (`74151`) katlama tablosu yöntemi.
   - ⚡ **Son Gece Ezber Kartları:** İnteraktif 7-Segment Display (`'-' → g`, `'7' → a,b,c`, `7447`), `74xx` Entegre Kodları (`74147`, `7442`, `74151`, `74LS138`, `7485`, `7483`, `74181` ALU, `74285` Çarpıcı), Kapı/Transistör hileleri ve TTL Elektriksel Parametreler (Fan-out, `ns`, `mW`, `0.4V` Gürültü Bağışıklığı).

6. **💣 Bölüm 6: Çıkmış 53 Soru & Taktikli Çözümleri**
   - Konu filtreli, canlı skor sayaçlı ve her sorunun altında `<details><summary>💡 Mala Anlatır Gibi Çözümü Gör</summary>...</details>` açılır çözüm kutuları bulunan 53 soruluk interaktif vize prova testi.
