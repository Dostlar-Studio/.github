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
sunucu verisi. Her mod önce kendi sunucumuzda çalışıyor, sonra yayına giriyor.

## Modlar

| Mod | Ne yapar | Sürüm | Durum |
| --- | --- | --- | --- |
| **[Kontrat Yöneticisi](https://github.com/Dostlar-Studio/FS25_ContractManager)** · `FS25_ContractManager` | Kontrat üretimini, ödül ve ceza modelini, limitleri sunucu yöneticisinin eline verir. Kontrat ürününü hırsızlığa karşı korur, ortak kontrat açar. | 1.13.1.0 | Yayında |
| **Satış Yönetimi** · `FS25_SellingAdmin` | Haritadaki bütün satış noktalarını tek panelde toplar. Ürün fiyatına çarpan, taban ve tavan koyar; oyunun dinamik fiyat sistemi bozulmaz. | 1.3.0.0 | Geliştirmede |
| **Araç Sıfırlama Kapalı** · `FS25_NoVehicleReset` | Araç sıfırlamayı hem menüde hem sunucu tarafında kapatır. Suya batan araç ışınlanmaz, zincirle çekilir ve tamirhanede onarılır. | 2.0.2.0 | Geliştirmede |
| **[Discord Bridge](https://bridge.dostlarkonagi.com/)** · `FS25_DiscordBridge` | Sunucu verisini Discord'a ve web panosuna taşır: canlı pano, uyarılar, on beş slash komut, savegame yedeği. Köprü bizim altyapımızda; kurulum tarayıcıdan, dört adım. | 1.3.8.0 | Yayında |
| **AFK Koruması** · `FS25_AFKGuard` | Boşta kalan oyuncuyu önce uyarır, onay gelmezse sunucudan düşürür. Slotu tutan ama oynamayan oyuncuyu temizler. | 1.2.0.0 | Geliştirmede |
| **Uyku Bekçisi** · `FS25_SleepHunter` | Uykuyu saat penceresine hapseder: en erken 20:00'de yatılır, en geç 08:00'de kalkılır. İki katman pencereyi dolanmayı engeller. | 1.2.0.0 | Geliştirmede |
| **Production Upgrade** · `FS25_ProductionUpgrade` | Üretim noktalarına yükseltme seviyeleri ekler: üretim hızı, depo kapasitesi, verim. | 0.1.0.0 | Erken geliştirme |
| **Kontrat Ürün Koruması** · `FS25_ContractGuard` | Koruma katmanı olduğu gibi Kontrat Yöneticisi'ne taşındı, kayıt verisi de devrediliyor. | 1.0.0.0 | Yerini bıraktı |

Her modun ayrıntılı sayfası, özellik listesi ve indirme bağlantısı
[studio.dostlarkonagi.com](https://studio.dostlarkonagi.com) üzerinde.

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
vehicle reset, server economy, Discord integration. Every mod runs on our own server before release.

| Mod | What it does | Version | Status |
| --- | --- | --- | --- |
| [FS25_ContractManager](https://github.com/Dostlar-Studio/FS25_ContractManager) | Contract generation, reward and penalty model, limits, server-side product guard, partner contracts | 1.13.1.0 | Released |
| FS25_SellingAdmin | Multiplier, floor and ceiling prices for every selling point, without breaking the game's dynamic pricing | 1.3.0.0 | In development |
| FS25_NoVehicleReset | Disables vehicle reset in the menu and on the server; sunken vehicles are towed and repaired instead | 2.0.2.0 | In development |
| [FS25_DiscordBridge](https://bridge.dostlarkonagi.com/) | Server data in Discord and in a web panel: live dashboard, alerts, fifteen slash commands, savegame backup. We host the bridge; setup runs in the browser | 1.3.8.0 | Released |
| FS25_AFKGuard | Warns idle players, then drops them from the server when no confirmation arrives | 1.2.0.0 | In development |
| FS25_SleepHunter | Confines sleeping to a time window and enforces the wake-up time on every player | 1.2.0.0 | In development |
| FS25_ProductionUpgrade | Upgrade levels for production points: speed, storage, efficiency | 0.1.0.0 | Early development |
| FS25_ContractGuard | Merged into Contract Manager, which also migrates its save data | 1.0.0.0 | Replaced |

Mod pages and downloads: [studio.dostlarkonagi.com/en](https://studio.dostlarkonagi.com/en/).
Design notes: no custom HUD, the game's own screens only; rules are server authoritative;
multiplayer and dedicated first; Turkish, English and German (plus French in Contract Manager).

Put the mod zip into the `mods` folder of the server and of every player, enable it for the savegame
and restart. All players need the same version. PC/Mac only, script mods.

Bug reports: the Issues tab of the repository, our [Discord](https://discord.gg/jT6KmCXfKu),
or <hello@kahrastudio.art>. Please attach the relevant lines of `log.txt`.

</details>
