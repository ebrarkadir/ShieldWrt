# 🛡️ ShieldWrt

**ShieldWrt**, ev kullanıcıları ve küçük ofisler için düşük maliyetli, kullanıcı dostu bir ağ güvenlik çözümüdür. Web arayüzü üzerinden kolayca kural ekleme, düzenleme ve silme işlemleri yapabileceğiniz bu proje, temel ağ güvenliği ihtiyaçlarınızı teknik bilgiye ihtiyaç duymadan karşılamanızı hedefler.

---

## 🚀 Proje Tanıtımı

**ShieldWrt**, React ile geliştirilmiş bir kullanıcı arayüzü (UI) ve Node.js/Express ile yazılmış bir API sunucusundan oluşur.  
Her iki sistem de bir **Raspberry Pi** üzerinde çalışan **OpenWRT** tabanlı bir firewall'a bağlanarak ağ kurallarını yönetir.

---

## 🧰 Kullanılan Teknolojiler

- ⚛️ **React** — Arayüz için
- 🟩 **Node.js & Express** — API sunucusu için
- 📡 **OpenWRT** — Firewall cihazı (Raspberry Pi üzerinde)
- 🔒 **SSH (ssh2)** — OpenWRT ile haberleşme
- 📊 **CSV Loglama** — Her işlem sonrası kayıt

---

## 📁 Alt Repos

- 🎛️ Kullanıcı Arayüzü (UI): [shieldwrt-ui](https://github.com/kendi-adresin/shieldwrt-ui)
- 🔧 API Sunucusu: [shieldwrt-api](https://github.com/kendi-adresin/shieldwrt-api)

---

## 🧱 Uygulamada Desteklenen 7 Kural Türü

Aşağıdaki tüm kurallar UI'dan yönetilebilir ve doğrudan OpenWRT'ye uygulanır:

| 🔢 | Kural Türü               | Açıklama                                                                 |
|----|--------------------------|--------------------------------------------------------------------------|
| 1  | **DNS Blocking**         | Belirli alan adlarının çözümünü engelleyerek internet erişimini durdurur. |
| 2  | **MAC Rules**            | Belirli cihazların MAC adresine göre ağa erişimini kısıtlar veya izin verir. |
| 3  | **QoS Rules**            | Cihazlara trafik önceliği atayarak bant genişliğini kontrollü şekilde dağıtır. |
| 4  | **Port Forwarding**      | Belirli portlardan gelen trafiği iç ağdaki belirli cihazlara yönlendirir. |
| 5  | **Port Blocking**        | Belirli portları veya port aralıklarını hedef alarak dış erişimi engeller. |
| 6  | **Zaman Bazlı Kurallar** | Erişim izinlerini belirli günler ve saatlerle sınırlayarak zaman kontrolü sağlar. |
| 7  | **Genel Firewall Kuralları** | Protokol, IP ve port bazlı özel kurallarla detaylı trafik kontrolü sunar. |


---

## 🖼️ Arayüz Ekran Görüntüleri

### 🏠 Ana Sayfa
![Ana Sayfa](screenshots/home.jpeg)

### 🌐 DNS Engelleme
![DNS Blocking](screenshots/dns_blocking.jpeg)

### 📶 MAC Adresi Kuralları
![MAC Rules](screenshots/mac_rules.jpeg)

### 🚦 Trafik Önceliklendirme (QoS)
![QoS Rules](screenshots/qos_rules.jpeg)

### 🔁 Port Yönlendirme
![Port Forwarding](screenshots/port_forwarding.jpeg)

### ⛔ Port Engelleme
![Port Blocking](screenshots/port_blocking.jpeg)

### 🕒 Zaman Bazlı Kurallar
![Time-Based Rules](screenshots/time_rules.jpeg)

### 🔥 Genel Firewall Kuralları
![Genel Kurallar](screenshots/firewall_rules.jpeg)

---

## 👤 Geliştirici

**Ebrar Kadir Çetin**  
📧 cetinebrarkadir@gmail.com  
🔗 [GitHub Profilim](https://github.com/ebrarkadir)

---

## 📜 Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Ayrıntılar için `LICENSE` dosyasına bakabilirsiniz.

---

