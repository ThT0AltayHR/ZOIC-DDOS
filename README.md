# 🔱 ZOIC-DDOS — Advanced Layer 4 & Layer 7 Stress Testing Platform

<p align="center">
  <img src="https://img.shields.io/github/stars/ThT0AltayHR/ZOIC-DDOS?style=for-the-badge&color=red" alt="Stars">
  <img src="https://img.shields.io/github/forks/ThT0AltayHR/ZOIC-DDOS?style=for-the-badge&color=black" alt="Forks">
  <img src="https://img.shields.io/github/issues/ThT0AltayHR/ZOIC-DDOS?style=for-the-badge&color=orange" alt="Issues">
  <img src="https://img.shields.io/github/license/ThT0AltayHR/ZOIC-DDOS?style=for-the-badge&color=blue" alt="License">
</p>

<p align="center">
  <a href="#-official-communities--resmî-topluluklarimiz">Communities</a> •
  <a href="#-core-modules--ana-modüller">Core Modules</a> •
  <a href="#-usage--kullanim">Usage</a> •
  <a href="#-legal-disclaimer--yasal-uyari">Disclaimer</a>
</p>

---

## 🦅 Official Communities / Resmî Topluluklarımız

<table>
  <tr>
    <td align="center">
      <a href="https://www.turkhackteam.org">
        <img src="https://img.shields.io/badge/Türk_Hack_Team-🔴_Anasayfa-black?style=for-the-badge&logo=opsgenie" width="220" alt="THT"><br>
        <sub><b>turkhackteam.org</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.turkhackteam.org/forumlar/anka-red-team.501/">
        <img src="https://img.shields.io/badge/Anka_Red_Team-🦅_Forum-red?style=for-the-badge&logo=target" width="220" alt="Anka"><br>
        <sub><b>İstediğimiz Zaman, İstediğimiz Yerde!</b></sub>
      </a>
    </td>
  </tr>
</table>

---

## 📝 Description / Açıklama

### 🇹🇷 Türkçe
**ZOIC-DDOS**, altyapıların ve web servislerinin yoğun trafik altındaki dayanıklılığını test etmek amacıyla geliştirilmiş çift modüllü bir stres test aracıdır. Cloudflare, HTTP tünelleme korumaları ve web servislerinin çevrimdışı kalma eşiklerini analiz etmek için optimize edilmiştir.

### 🇬🇧 English
**ZOIC-DDOS** is a dual-module stress testing infrastructure engineered to evaluate network and web-service resilience under high-load conditions. Optimized for analyzing Cloudflare defenses, HTTP tunnel bypass mechanisms, and web service failure thresholds.

---

## ⚡ Core Modules / Ana Modüller

Aracımız esnek analizler yapabilmek için iki temel mimari üzerine kurulmuştur:

*   **🛡️ Layer 4 (L4) Modülü:** Seçildiğinde, ağ katmanına yönelik farklı protokol metodlarını ve esnek varyasyonları devreye sokar.
*   **🌐 Layer 7 (L7) Modülü:** Doğrudan hedef domain (uygulama katmanı) üzerine odaklanarak HTTP/HTTPS koruma duvarlarını simüle eder.

---

## 🚀 Installation & Usage / Kurulum ve Kullanım

Aracı klonlayıp bağımlılıkları yükledikten sonra, tüm parametreleri ve yardım kılavuzunu görüntülemek için sadece yardım argümanını tetiklemeniz yeterlidir:

```bash
git clone [https://github.com/ThT0AltayHR/ZOIC-DDOS.git](https://github.com/ThT0AltayHR/ZOIC-DDOS.git)
cd ZOIC-DDOS
pip install -r requirements.txt

# Yardım menüsünü ve kullanım detaylarını listeler:
python zoic.py --help

⚖️ Legal Disclaimer / Yasal Uyarı
🇹🇷 Önemli
Bu yazılım yalnızca yasal sızma testleri ve altyapı stres analizleri için kullanılabilir. İzin alınmamış sistemler üzerinde kullanımı tamamen son kullanıcının sorumluluğundadır. Geliştirici ve bağlı topluluklar (Türk Hack Team / Anka Red Team) kötüye kullanımdan sorumlu tutulamaz.
🇬🇧 Legal Notice
This toolkit is developed strictly for authorized penetration testing and infrastructure simulation. The author and associated communities accept no liability for any unauthorized deployment or misuse.
<p align="center">
<b>ANKA RED TEAM — İSTEDİĞİMİZ ZAMAN, İSTEDİĞİMİZ YERDE</b>
</p>
