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
| **[Kontrat Yöneticisi](https://github.com/Dostlar-Studio/FS25_ContractManager)** · `FS25_ContractManager` | Kontrat üretimini, limitleri, ödül ve ceza modelini sunucu yöneticisinin eline verir. Kontrat ürününü hırsızlığa karşı korur, ortak kontrat ve devir açar. | 1.24.7.0 | Yayında |
| **[Discord Bridge](https://bridge.dostlarkonagi.com/)** · `FS25_DiscordBridge` | Sunucudaki bakiye, tarla, araç, fiyat, kontrat ve olay verisini Discord'a ve tarayıcıya taşır. Köprü bizim altyapımızda çalışır; sen yalnızca modu sunucuya atarsın. | 1.3.11.0 | Yayında |
| **[AFK Koruması](https://studio.dostlarkonagi.com/mods/afk-guard/)** · `FS25_AFKGuard` | Boşta kalan oyuncuyu önce uyarır, onay gelmezse sunucudan düşürür. Slotu tutan ama oynamayan oyuncuyu temizler. | 1.2.3.0 | Yayında |
| **[Uyku Bekçisi](https://studio.dostlarkonagi.com/mods/sleep-hunter/)** · `FS25_SleepHunter` | Uykuyu saat penceresine hapseder: en erken 20:00'de yatılır, en geç 08:00'de kalkılır. | 1.2.1.0 | Yayında |
| **[Satış Yönetimi](https://studio.dostlarkonagi.com/mods/selling-admin/)** · `FS25_SellingAdmin` | Haritadaki bütün satış noktalarını ve aldıkları ürünleri tek panelde toplar. Ürün fiyatına çarpan, taban ve tavan koy; oyunun dinamik fiyat sistemi bozulmasın. | 1.3.0.0 | Geliştirmede |
| **[Araç Sıfırlama Kapalı](https://studio.dostlarkonagi.com/mods/no-vehicle-reset/)** · `FS25_NoVehicleReset` | Araç sıfırlama düğmesini oyunculara tamamen kapatır. Suya batan araç ışınlanmaz; zincirle çekilir, tamirhanede onarılır. | 2.0.4.0 | Geliştirmede |
| **[Oyuncu Pazarı](https://studio.dostlarkonagi.com/mods/farm-market/)** · `FS25_FarmMarket` | Üretim çıktıları için oyuncular arası ticaret. Fabrika sahibi ürettiğini satışa açar, girdi için alış ilanı verir; başka çiftlikler gelip alır ya da getirip satar. | 1.7.0.0 | Geliştirmede |
| **[Sunucu Teşhis](https://studio.dostlarkonagi.com/mods/server-diagnostics/)** · `FS25_ServerDiagnostics` | Sunucun neden takılıyor? Bu mod tahmin etmez, ölçer: mod başına süre, araç ve yapı başına süre, ağ sayaçları, takılma yakalayıcı. | 1.4.0.0 | Geliştirmede |
| **[Mezat](https://studio.dostlarkonagi.com/mods/vehicle-auction/)** · `FS25_VehicleAuction` | Sabit fiyatlı ikinci el pazarını saatli açık artırmayla değiştirir. Sınırlı sayıda araç belirli saatlerde gelir ve en yüksek teklifi verene satılır. | 0.16.0.0 | Geliştirmede |
| **[Gelişmiş Peyzaj](https://studio.dostlarkonagi.com/mods/advanced-landscaping/)** · `FS25_AdvancedLandscaping` | Fırçayla sürterek değil, ölçerek peyzaj. Dört direk dikersin, kipi seçersin, taşınacak toprağı ve ücreti görürsün, sonra uygularsın. | 0.5.0.0 | Geliştirmede |
| **[Kostanjevec Riječki](https://studio.dostlarkonagi.com/mods/kostanjevec-rijecki/)** · `FS25_KostanjevecRijecki` | Hırvatistan'ın Kalnik tepelerindeki Kostanjevec Riječki köyü. Gerçek arazi, yol, dere ve ormanlara dayanan 2x2 km harita, 113 tarla. | 1.0.0.0 | Geliştirmede |
| **[Palet Deposu](https://studio.dostlarkonagi.com/mods/pallet-storage/)** · `FS25_DSPalletStorage` | Oyunun kendi nesne deposu sistemi üzerine kurulu, üç boyda kapalı palet deposu. Paletler dokta girer, içerideki raflarda görünür, fabrikaya ya da pazara buradan gider. | 1.11.6.0 | Geliştirmede |
| **[Palet Kasa Dorse](https://studio.dostlarkonagi.com/mods/pallet-cargo-semi/)** · `FS25_PalletCargoSemi` | Tırlar için kapalı kasa dorse; paletli ürünleri litre olarak taşır. Oyunun orijinal Krone Profi Liner şasisi üzerinde sert bir Dostlar STUDIO kasa. | 1.15.5.0 | Geliştirmede |
| **[Palet Kasa Römork](https://studio.dostlarkonagi.com/mods/pallet-cargo-trailer/)** · `FS25_PalletCargoTrailer` | Traktörler için kapalı kasa römork; paletli ürünleri litre olarak taşır. Oyunun orijinal Annaburger HTS 22B.79 şasisi üzerinde sıfırdan çizilmiş bir Dostlar STUDIO kasa. | 1.15.5.0 | Geliştirmede |
| **[Sunucu İnce Ayar](https://studio.dostlarkonagi.com/mods/server-tuner/)** · `FS25_ServerTuner` | Dedicated sunucuda hangi modun yük yarattığını kendi ölçer ve pahalı olanları daha seyrek çağırır. Mod listesi tutmaz, hangi modların kurulu olduğunu bilmesi gerekmez. | 0.2.0.0 | Geliştirmede |
| **[Server Warden](https://studio.dostlarkonagi.com/mods/server-warden/)** · `FS25_ServerWarden` | Sunucu ve admin yönetimi: AFK koruması, uyku saatleri, araç reset kuralları, ekonomi ve oyun kuralları tek ayar penceresinde. | 0.3.0.0 | Geliştirmede |
| **[Kontrat Ürün Koruması](https://studio.dostlarkonagi.com/mods/contract-guard/)** · `FS25_ContractGuard` | Tarla kontratı ürününün çalınmasını engelleyen ilk mod. Geliştirmesi durdu; koruma katmanı olduğu gibi Kontrat Yöneticisi'ne taşındı. | 1.0.0.0 | Yerini bıraktı |

Her modun ayrıntılı sayfası, özellik listesi ve indirme bağlantısı
[studio.dostlarkonagi.com](https://studio.dostlarkonagi.com) üzerinde.

Lisans, yasal uyarı ve gizlilik: [studio.dostlarkonagi.com/yasal](https://studio.dostlarkonagi.com/yasal/).
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
| [FS25_ContractManager](https://github.com/Dostlar-Studio/FS25_ContractManager) | Puts contract generation, limits and the reward/penalty model in the server admin's hands. Guards the contract product against theft and opens up shared contracts. | 1.24.7.0 | Released |
| [FS25_DiscordBridge](https://bridge.dostlarkonagi.com/) | Carries balance, field, vehicle, price, contract and event data from the server to Discord and to your browser. The bridge runs on our infrastructure; all you do is drop the mod onto your server. | 1.3.11.0 | Released |
| [FS25_AFKGuard](https://studio.dostlarkonagi.com/en/mods/afk-guard/) | Warns an idle player first, then drops them from the server if no confirmation arrives. Clears players who hold a slot without playing. | 1.2.3.0 | Released |
| [FS25_SleepHunter](https://studio.dostlarkonagi.com/en/mods/sleep-hunter/) | Confines sleeping to a time window: no sleep before 20:00, everyone is up by 08:00 at the latest. | 1.2.1.0 | Released |
| [FS25_SellingAdmin](https://studio.dostlarkonagi.com/en/mods/selling-admin/) | Collects every selling point on the map and the goods it buys into one panel. Set a multiplier, a floor and a cap per product without breaking the game's dynamic pricing. | 1.3.0.0 | In development |
| [FS25_NoVehicleReset](https://studio.dostlarkonagi.com/en/mods/no-vehicle-reset/) | Takes the vehicle reset button away from players entirely. A vehicle that sinks is not teleported; it gets towed out and repaired at a workshop. | 2.0.4.0 | In development |
| [FS25_FarmMarket](https://studio.dostlarkonagi.com/en/mods/farm-market/) | Player-to-player trade around production. A factory owner lists outputs for sale and posts buy offers for inputs; other farms come to buy, or bring goods and sell. | 1.7.0.0 | In development |
| [FS25_ServerDiagnostics](https://studio.dostlarkonagi.com/en/mods/server-diagnostics/) | Why does your server stutter? This mod does not guess, it measures: time per mod, time per vehicle and placeable, network counters, a stall catcher. | 1.4.0.0 | In development |
| [FS25_VehicleAuction](https://studio.dostlarkonagi.com/en/mods/vehicle-auction/) | Replaces the fixed-price used vehicle market with timed auctions. A limited number of vehicles arrives in scheduled windows and goes to the highest bidder. | 0.16.0.0 | In development |
| [FS25_AdvancedLandscaping](https://studio.dostlarkonagi.com/en/mods/advanced-landscaping/) | Landscaping by measuring instead of smearing a brush. You plant four posts, pick a mode, see the soil to be moved and the cost, then apply. | 0.5.0.0 | In development |
| [FS25_KostanjevecRijecki](https://studio.dostlarkonagi.com/en/mods/kostanjevec-rijecki/) | The village of Kostanjevec Riječki in the Kalnik hills of Croatia. A 2x2 km map built on the real terrain, roads, streams and forests, with 113 fields. | 1.0.0.0 | In development |
| [FS25_DSPalletStorage](https://studio.dostlarkonagi.com/en/mods/pallet-storage/) | A closed pallet storage in three sizes, built on the game's own object storage system. Pallets enter at the dock, show up on the racks inside, and go on to factories or the market from here. | 1.11.6.0 | In development |
| [FS25_PalletCargoSemi](https://studio.dostlarkonagi.com/en/mods/pallet-cargo-semi/) | A closed-body semi-trailer for trucks that carries pallet goods as litres. A rigid Dostlar STUDIO body on the game's original Krone Profi Liner chassis. | 1.15.5.0 | In development |
| [FS25_PalletCargoTrailer](https://studio.dostlarkonagi.com/en/mods/pallet-cargo-trailer/) | A closed-body trailer for tractors that carries pallet goods as litres. A Dostlar STUDIO body drawn from scratch on the game's original Annaburger HTS 22B.79 chassis. | 1.15.5.0 | In development |
| [FS25_ServerTuner](https://studio.dostlarkonagi.com/en/mods/server-tuner/) | Measures on its own which mod loads a dedicated server and calls the expensive ones less often. It keeps no mod list and does not need to know which mods are installed. | 0.2.0.0 | In development |
| [FS25_ServerWarden](https://studio.dostlarkonagi.com/en/mods/server-warden/) | Server and admin management: AFK protection, sleep hours, vehicle reset rules, economy and game rules in a single settings window. | 0.3.0.0 | In development |
| [FS25_ContractGuard](https://studio.dostlarkonagi.com/en/mods/contract-guard/) | The first mod that stopped field contract crops from being stolen. Development has stopped; its guard layer moved into Contract Manager unchanged. | 1.0.0.0 | Replaced |

Mod pages and downloads: [studio.dostlarkonagi.com/en](https://studio.dostlarkonagi.com/en/).
License, legal notice and privacy: [studio.dostlarkonagi.com/en/legal](https://studio.dostlarkonagi.com/en/legal/).
In short: you may use the mods, edit them and include them in a modpack as long as you credit
Dostlar STUDIO. Reuploading the zip elsewhere and selling the mods are not allowed.
Design notes: no custom HUD, the game's own screens only; rules are server authoritative;
multiplayer and dedicated first; Turkish, English and German (plus French in Contract Manager).

Put the mod zip into the `mods` folder of the server and of every player, enable it for the savegame
and restart. All players need the same version. PC/Mac only, script mods.

Bug reports: the Issues tab of the repository, our [Discord](https://discord.gg/jT6KmCXfKu),
or <hello@kahrastudio.art>. Please attach the relevant lines of `log.txt`.

</details>
