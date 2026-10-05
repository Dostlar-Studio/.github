<div align="center">

# Dostlar STUDIO

**Farming Simulator 25 sunucuları için Lua script modları.**

[![Web sitesi](https://img.shields.io/badge/studio.dostlarkonagi.com-2f6b3a?style=flat-square&logo=cloudflare&logoColor=white)](https://studio.dostlarkonagi.com)
[![Discord](https://img.shields.io/badge/Discord-Dostlar%20Kona%C4%9F%C4%B1-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/jT6KmCXfKu)
[![Topluluk](https://img.shields.io/badge/dostlarkonagi.com-2f6b3a?style=flat-square)](https://dostlarkonagi.com)

</div>

---

Dostlar STUDIO, [dostlarkonagi.com](https://dostlarkonagi.com) topluluğunun mod atölyesi.
Kiralık dedicated sunucularda karşılaştığımız gerçek sorunlardan yola çıkıyoruz: kontrat ürününü
çalan oyuncu, tek tuşla eve ışınlanan araç, anlamını yitiren sunucu ekonomisi, Discord'a taşınmayan
sunucu verisi, nedeni bilinmeyen takılma, fabrikanın önünde yığılan paletler. Kontrat ve ekonomi
modlarının yanında oyuncular arası pazar, ikinci el mezatı, palet lojistiği ve sunucu ölçümü de
yazıyoruz. Her mod önce kendi sunucumuzda çalışıyor, sonra yayına giriyor.

## Modlar

| Mod | Ne yapar | Sürüm | Durum |
| --- | --- | --- | --- |
| **[Kontrat Yöneticisi](https://github.com/Dostlar-Studio/FS25_ContractManager)** · `FS25_ContractManager` | Kontrat üretimini, limitleri, ödül ve ceza modelini sunucu yöneticisinin eline verir. Kontrat ürününü hırsızlığa karşı korur, ortak kontrat ve devir açar. | 1.25.1.0 | Yayında |
| **[Discord Bridge](https://bridge.dostlarkonagi.com/)** · `FS25_DiscordBridge` | Sunucudaki bakiye, tarla, araç, fiyat, kontrat ve olay verisini Discord'a ve tarayıcıya taşır. Köprü bizim altyapımızda çalışır; sen yalnızca modu sunucuya atarsın. | 1.4.2.0 | Yayında |
| **[Oyuncu Pazarı](https://studio.dostlarkonagi.com/mods/farm-market/)** · `FS25_FarmMarket` | Üretim çıktıları için oyuncular arası ticaret. Fabrika sahibi ürettiğini satışa açar, girdi için alış ilanı verir; başka çiftlikler gelip alır ya da getirip satar. | 1.8.1.0 | Geliştirmede |
| **[Mezat](https://studio.dostlarkonagi.com/mods/vehicle-auction/)** · `FS25_VehicleAuction` | Sabit fiyatlı ikinci el pazarını saatli açık artırmayla değiştirir. Sınırlı sayıda araç belirli saatlerde gelir ve en yüksek teklifi verene satılır. | 0.16.0.0 | Geliştirmede |
| **[Palet Deposu](https://studio.dostlarkonagi.com/mods/pallet-storage/)** · `FS25_DSPalletStorage` | Oyunun kendi nesne deposu sistemi üzerine kurulu, üç boyda kapalı palet deposu. Paletler dokta girer, içerideki raflarda görünür, fabrikaya ya da pazara buradan gider. | 1.12.8.0 | Geliştirmede |
| **[Dostlar Ticaret Merkezi](https://studio.dostlarkonagi.com/mods/trade-center/)** · `FS25_DSTradeCenter` | Haritaya yerleştirilen, kantarlı ve herkese açık bir satış noktası. Fiyatlar piyasayı izler ve ürün ürün dalgalanır, her satışa numaralı fatura kesilir; sunucu yöneticisi fiyatları tek tablodan ayarlar. | 1.18.5.0 | Geliştirmede |
| **[Palet Kasa Dorse](https://studio.dostlarkonagi.com/mods/pallet-cargo-semi/)** · `FS25_PalletCargoSemi` | Tırlar için kapalı kasa dorse; paletli ürünleri litre olarak taşır. Oyunun orijinal Krone Profi Liner şasisi üzerinde sert bir Dostlar STUDIO kasa. | 1.15.6.0 | Geliştirmede |
| **[Palet Kasa Römork](https://studio.dostlarkonagi.com/mods/pallet-cargo-trailer/)** · `FS25_PalletCargoTrailer` | Traktörler için kapalı kasa römork; paletli ürünleri litre olarak taşır. Oyunun orijinal Annaburger HTS 22B.79 şasisi üzerinde sıfırdan çizilmiş bir Dostlar STUDIO kasa. | 1.15.6.0 | Geliştirmede |

Her modun ayrıntılı sayfası, özellik listesi ve indirme bağlantısı
[studio.dostlarkonagi.com](https://studio.dostlarkonagi.com) üzerinde. Rafa kaldırılan modlar sitenin
[Arşiv](https://studio.dostlarkonagi.com/arsiv/) sayfasında.

Kullanım şartları, lisans, yasal uyarı ve gizlilik: [studio.dostlarkonagi.com/yasal](https://studio.dostlarkonagi.com/yasal/).
Kısacası modları kullanabilir, düzenleyebilir ve bir mod paketine koyabilirsin; tek şart Dostlar STUDIO
adını belirtmek. Zip'i başka bir siteye yeniden yüklemek ve modları satmak yasak.

## Nasıl yazıyoruz

- **Oyunun kendi ekranları.** Ayrı bir HUD kurmuyoruz. Kurallar ESC menüsündeki ayarlar sekmesinde,
  işlemler oyunun kendi sayfalarında. Tuş ataması çoğu modda gerekmiyor.
- **Sunucu yetkili.** Kural ve koruma kararları sunucu tarafında veriliyor. Modifiye istemci de
  kuralı deleyemiyor.
- **Çok oyunculu önce gelir.** Modlar dedicated sunucuda test ediliyor; ayarlar kayıt dosyası başına
  saklanıyor ve tüm oyuncularda senkron kalıyor.
- **Üç dil, tek paket.** Türkçe, İngilizce ve Almanca metinler her modun içinde geliyor;
  Kontrat Yöneticisi'nde ayrıca Fransızca var.
- **Ölçülü maliyet.** Her karede iş yapan kanca yazmıyoruz; diske yazma ve olay kancaları
  sunucuyu kasmayacak sıklıkta çalışıyor.

## Kurulum

Mod zip'ini sunucunun ve bağlanan tüm oyuncuların `mods` klasörüne koy, kayıt için modu etkinleştir
ve sunucuyu yeniden başlat. Herkeste aynı sürüm olmalı. Script modu oldukları için yalnızca PC ve Mac.

Ayar dosyaları `Documents/My Games/FarmingSimulator2025/modSettings/` altında ilk çalıştırmada
varsayılanlarla oluşuyor; içindeki her şey oyun içinden de değiştirilebiliyor.

## Sorun bildirimi

- Depoların **Issues** sekmesi (örn. [FS25_ContractManager](https://github.com/Dostlar-Studio/FS25_ContractManager/issues))
- Discord: [Dostlar Konağı](https://discord.gg/jT6KmCXfKu)
- E-posta: <hello@kahrastudio.art>

Hata bildirirken `log.txt` dosyasının ilgili satırlarını eklersen çok daha hızlı çözülüyor.

---

<details>
<summary><b>English</b></summary>

**Dostlar STUDIO** is the mod workshop of the [dostlarkonagi.com](https://dostlarkonagi.com) community.
Everything below is also on our site in English: [studio.dostlarkonagi.com/en](https://studio.dostlarkonagi.com/en/).
We write Lua script mods for Farming Simulator 25, aimed at rented dedicated servers: contract abuse,
vehicle reset, server economy, Discord integration, stutter diagnostics, player-to-player trade,
used vehicle auctions and pallet logistics. Every mod runs on our own server before release.

| Mod | What it does | Version | Status |
| --- | --- | --- | --- |
| [FS25_ContractManager](https://github.com/Dostlar-Studio/FS25_ContractManager) | Puts contract generation, limits and the reward/penalty model in the server admin's hands. Guards the contract product against theft and opens up shared contracts. | 1.25.1.0 | Released |
| [FS25_DiscordBridge](https://bridge.dostlarkonagi.com/) | Carries balance, field, vehicle, price, contract and event data from the server to Discord and to your browser. The bridge runs on our infrastructure; all you do is drop the mod onto your server. | 1.4.2.0 | Released |
| [FS25_FarmMarket](https://studio.dostlarkonagi.com/en/mods/farm-market/) | Player-to-player trade around production. A factory owner lists outputs for sale and posts buy offers for inputs; other farms come to buy, or bring goods and sell. | 1.8.1.0 | In development |
| [FS25_VehicleAuction](https://studio.dostlarkonagi.com/en/mods/vehicle-auction/) | Replaces the fixed-price used vehicle market with timed auctions. A limited number of vehicles arrives in scheduled windows and goes to the highest bidder. | 0.16.0.0 | In development |
| [FS25_DSPalletStorage](https://studio.dostlarkonagi.com/en/mods/pallet-storage/) | A closed pallet storage in three sizes, built on the game's own object storage system. Pallets enter at the dock, show up on the racks inside, and go on to factories or the market from here. | 1.12.8.0 | In development |
| [FS25_DSTradeCenter](https://studio.dostlarkonagi.com/en/mods/trade-center/) | A placeable public selling point with a weighbridge. Prices follow the market and drift per product, every sale gets a numbered invoice, and the server admin sets prices from a single table. | 1.18.5.0 | In development |
| [FS25_PalletCargoSemi](https://studio.dostlarkonagi.com/en/mods/pallet-cargo-semi/) | A closed-body semi-trailer for trucks that carries pallet goods as litres. A rigid Dostlar STUDIO body on the game's original Krone Profi Liner chassis. | 1.15.6.0 | In development |
| [FS25_PalletCargoTrailer](https://studio.dostlarkonagi.com/en/mods/pallet-cargo-trailer/) | A closed-body trailer for tractors that carries pallet goods as litres. A Dostlar STUDIO body drawn from scratch on the game's original Annaburger HTS 22B.79 chassis. | 1.15.6.0 | In development |

Mod pages and downloads: [studio.dostlarkonagi.com/en](https://studio.dostlarkonagi.com/en/).
Shelved mods are on the site's [Archive](https://studio.dostlarkonagi.com/en/archive/) page.
Terms of use, license, legal notice and privacy: [studio.dostlarkonagi.com/en/legal](https://studio.dostlarkonagi.com/en/legal/).
In short: you may use the mods, edit them and include them in a modpack as long as you credit
Dostlar STUDIO. Reuploading the zip elsewhere and selling the mods are not allowed.
Design notes: no custom HUD, the game's own screens only; rules are server authoritative;
multiplayer and dedicated first; Turkish, English and German (plus French in Contract Manager).

Put the mod zip into the `mods` folder of the server and of every player, enable it for the savegame
and restart. All players need the same version. PC/Mac only, script mods.

Bug reports: the Issues tab of the repository, our [Discord](https://discord.gg/jT6KmCXfKu),
or <hello@kahrastudio.art>. Please attach the relevant lines of `log.txt`.

</details>
