# Odometer Gizlilik Politikası

*Son güncelleme: 27 Eylül 2026*

[English version below](#odometer-privacy-policy)

Bu politika, Odometer uygulamasının (iOS ve Android) hangi verileri topladığını, bunları nasıl kullandığını ve kimlerle paylaştığını açıklar. Uygulamanın geliştiricisi ve veri sorumlusu Çağrı Döşeyen'dir. Sorularını ve taleplerini **doseyenc.dev@gmail.com** adresine gönderebilirsin.

## Özet

- Sürüşlerin, araçların ve kayıtların **önce yalnızca telefonunda** saklanır.
- Hesap açmadan uygulamayı kullanabilirsin. Hesap; yedekleme, arkadaşlar ve sıralama için gerekir.
- Verini **satmıyoruz** ve reklam amaçlı kullanmıyoruz.
- Arkadaşlarınla neyi paylaşacağına sen karar verirsin. Sürüş ve konum paylaşımı varsayılan olarak kapalıdır.

## 1. Topladığımız veriler

### Cihazında kalan veriler
- **Konum ve sürüş verileri:** GPS konumu, hız, rota, süre ve mesafe. Otomatik sürüş kaydı açıksa uygulama arka planda da konum kullanır. Konum izni vermezsen sürüşleri elle başlatabilirsin.
- **Hareket algılama:** Otomatik kayıt için cihazın hareket/aktivite sensörü (araçta olup olmadığın) kullanılır.
- **Araç ve gider kayıtları:** Araç bilgileri, yakıt, bakım, masraf ve hatırlatıcılar, araç fotoğrafları.
- **Fiş fotoğrafları:** Fiş tarama özelliğinde fotoğraftaki yazı **cihazda** okunur (Google ML Kit / Apple Vision). Fotoğrafın kendisi sunucuya gönderilmez.

### Hesap açarsan
- **Hesap bilgileri:** Ad, e-posta adresi ve şifre (şifre Firebase Authentication tarafından saklanır, biz göremeyiz).
- **Bulut yedeği:** Yedeklemeyi kullanırsan araçların, sürüşlerin (rotalar dahil), yakıt/bakım/gider kayıtların, hatırlatıcıların ve araç fotoğrafların hesabına bağlı olarak Firebase'de saklanır.

### Sosyal özellikleri kullanırsan
- **Profil:** Takma ad, profil fotoğrafı, bölge ve araç etiketi (örneğin "VW Golf").
- **Sıralama:** Haftalık/aylık mesafe, en yüksek hız ve benzeri skorların. Sıralamadan istediğin zaman çıkabilirsin.
- **Arkadaşlar:** Arkadaş kodun, arkadaş listen ve her arkadaş için seçtiğin paylaşım ayarları.
- **Paylaşılan sürüşler:** Sürüş paylaşımını açarsan sürüşlerinin özeti ve rotası seçtiğin arkadaşlarına görünür.
- **Canlı konum ve sürüş durumu:** Açarsan, sürüş sırasında konumun, hızın ve yönün yalnızca izin verdiğin arkadaşlarına gösterilir. Geçmiş tutulmaz. Kayıt sürekli üzerine yazılır ve kısa süre sonra otomatik silinir.
- **Dürtmeler ve bildirimler:** Gönderdiğin/aldığın dürtmeler ve bildirim göndermek için cihazının bildirim jetonu ile dil tercihi.
- **Davet programı:** Kimin kimi davet ettiği ve kazanılan ödüller.

### Otomatik toplanan veriler
- **Kullanım analitiği:** Açılan ekranlar, kullanılan özellikler, abonelik ekranı etkileşimleri ve kurulum kaynağı (Google Play yükleme yönlendiricisi). Firebase Analytics ve Mixpanel ile toplanır.
- **Reklam kimliği:** Uygulamada reklam yoktur. Reklam kimliğini (Android Advertising ID, Apple IDFA) toplamıyoruz.
- **Çökme raporları:** Cihaz modeli, işletim sistemi sürümü ve hata ayrıntıları (Firebase Crashlytics).
- **Uygulama bütünlüğü:** İsteklerin gerçek uygulamadan geldiğini doğrulamak için Firebase App Check (Play Integrity, App Attest/DeviceCheck).
- **Satın alımlar:** Abonelik durumu ve satın alma geçmişi (RevenueCat üzerinden). Ödeme bilgilerini App Store veya Google Play işler, biz görmeyiz.

## 2. Verileri ne için kullanıyoruz

- Sürüşlerini kaydetmek, istatistik, ısı haritası ve sürüş tekrarı göstermek.
- Yedeklemek ve cihaz değiştirdiğinde geri yüklemek.
- Arkadaşlar, sıralama, dürtme ve canlı konum gibi sosyal özellikleri çalıştırmak.
- Bildirim göndermek (arkadaş etkinliği, dürtmeler, hatırlatıcılar, ödüller).
- Pro aboneliğini ve davet ödüllerini yönetmek.
- Uygulamayı geliştirmek, hataları bulmak ve kötüye kullanımı önlemek.


## 3. Hukuki dayanaklar

Kişisel verilerini KVKK madde 5 ve GDPR madde 6 kapsamında şu dayanaklarla işliyoruz:

| İşleme | Dayanak |
|---|---|
| Hesap, bulut yedeği, abonelik ve davet ödülleri | Sözleşmenin kurulması ve ifası |
| Konum, hareket algılama, bildirimler, arkadaş paylaşımları ve canlı konum | Açık rıza. İzinler ve paylaşım ayarları üzerinden verilir ve her an geri alınabilir. |
| Yapay zekâ ile fiş tarama ve sürüş koçu | Açık rıza. Yalnızca özelliği kendin başlattığında çalışır. |
| Kullanım analitiği, çökme raporları ve kötüye kullanımın önlenmesi | Meşru menfaat: uygulamayı çalışır ve güvenli tutmak |
| Yetkili makamların taleplerine yanıt | Hukuki yükümlülük |

Veriler uygulama aracılığıyla elektronik ortamda, otomatik yollarla ve senin girdiğin bilgilerle toplanır.

## 4. Yapay zekâ özellikleri

- **Fiş tarama:** Cihazda okunan fiş **metni** (fotoğraf değil), tutar ve kategoriyi çıkarmak için sunucumuz üzerinden Anthropic'in Claude modeline gönderilir.
- **Sürüş koçu:** Ortalama tüketim, eko skor, sert fren/hızlanma sayısı gibi **özet** sürüş istatistiklerin öneri üretmek için aynı şekilde gönderilir. Rotan veya konumun gönderilmez.

Bu isteklerde adın, e-postan veya hesap kimliğin yapay zekâ sağlayıcısına iletilmez.

## 5. Paylaştığımız hizmet sağlayıcılar

Verin yalnızca uygulamayı çalıştırmak için aşağıdaki hizmetlerle paylaşılır:

| Sağlayıcı | Amaç |
|---|---|
| Google Firebase (Authentication, Firestore, Storage, Cloud Functions, Cloud Messaging, Analytics, Crashlytics, App Check) | Hesap, yedek, sosyal özellikler, bildirimler, analitik, çökme raporları |
| Mixpanel | Kullanım analitiği |
| RevenueCat | Abonelik yönetimi |
| Mapbox | Harita görüntüleri. Harita yüklenirken gösterilen bölge ve IP adresi Mapbox'a ulaşır. |
| Anthropic | Fiş tarama ve sürüş koçu (yukarıya bak) |
| Apple App Store / Google Play | İndirme, satın alma, uygulama içi değerlendirme |

Sunucu tarafı işlemler Firebase'in Avrupa (europe-west1) bölgesinde çalışır. Sağlayıcılar veriyi kendi gizlilik politikalarına göre başka ülkelerde de işleyebilir.

Verini **satmıyoruz**, reklam ağlarıyla paylaşmıyoruz. Yasal bir zorunluluk olursa yetkili makamlarla paylaşabiliriz.


## 6. Yurt dışına aktarım

Hizmet sağlayıcılarımızın bir kısmı (Google, Mixpanel, RevenueCat, Mapbox, Anthropic) verileri Türkiye ve Avrupa Ekonomik Alanı dışında, başta ABD olmak üzere başka ülkelerde işleyebilir. Bu aktarımlar KVKK madde 9 ve GDPR'ın 5. bölümü çerçevesinde, sağlayıcıların sunduğu standart sözleşme hükümleri ve ilgili mevzuatın öngördüğü diğer güvencelerle yapılır.

## 7. Saklama süresi

- Cihazdaki veriler, uygulamayı silene veya sen silene kadar cihazında kalır.
- Bulut yedeği ve profil verileri, hesabını silene kadar saklanır. Hesabını sildiğinde hemen silinir.
- Canlı konum kaydı kısa süre sonra otomatik silinir.
- Analitik ve çökme verileri sağlayıcıların saklama sürelerine tabidir.

## 8. Hakların ve seçimlerin

- **İzinler:** Konum, hareket ve bildirim izinlerini cihaz ayarlarından istediğin zaman kapatabilirsin.
- **Paylaşım:** Sürüş paylaşımını, canlı konumu ve bildirimleri her arkadaş için ayrı ayrı kapatabilirsin.
- **Sıralama:** Sıralamadan istediğin zaman çıkabilirsin.
- **Hesabını silme:** Uygulamada **Profil → Hesabımı sil** ile hesabını ve buluttaki tüm verilerini (yedek, profil, sıralama kayıtları, arkadaşlıklar, paylaşılan sürüşler, fotoğraflar, bildirim jetonları) kalıcı olarak silebilirsin. Silme hemen gerçekleşir ve geri alınamaz. Uygulamaya erişemiyorsan aynı talebi **doseyenc.dev@gmail.com** adresine hesabının e-postasından yazarak iletebilirsin, 30 gün içinde yerine getiririz.
- **Abonelik:** Hesabını silmek Pro aboneliğini iptal etmez. Aboneliğini App Store veya Google Play abonelik ayarlarından iptal etmelisin.
- **Erişim ve düzeltme:** Verilerinin bir kopyasını istemek veya düzeltmek için **doseyenc.dev@gmail.com** adresine yazabilirsin.

KVKK madde 11 kapsamında; verilerinin işlenip işlenmediğini öğrenme, işlenmişse bilgi talep etme, işlenme amacını ve amacına uygun kullanılıp kullanılmadığını öğrenme, yurt içinde veya yurt dışında aktarıldığı üçüncü kişileri bilme, eksik veya yanlış işlenmişse düzeltilmesini, silinmesini veya yok edilmesini ve bu işlemlerin aktarıldığı üçüncü kişilere bildirilmesini isteme, münhasıran otomatik sistemlerle analiz edilmesi sonucu aleyhine bir sonuç çıkmasına itiraz etme ve kanuna aykırı işleme nedeniyle zarara uğraman hâlinde zararın giderilmesini talep etme haklarına sahipsin. GDPR kapsamında ayrıca verilerini taşınabilir biçimde alma, işlemeyi kısıtlatma ve rızanı geri alma hakların vardır.

Taleplerini **doseyenc.dev@gmail.com** adresine iletebilirsin, en geç 30 gün içinde yanıtlarız. Yanıtımızdan memnun kalmazsan Türkiye'de Kişisel Verileri Koruma Kurulu'na, Avrupa Birliği'nde ise yaşadığın ülkenin veri koruma otoritesine şikâyette bulunabilirsin.

## 9. Güvenlik

Veriler cihaz ile sunucu arasında şifreli bağlantı (HTTPS/TLS) üzerinden taşınır. Buluttaki verilere yalnızca sen erişebilirsin. Arkadaşların yalnızca senin paylaşmayı seçtiğin verileri görebilir. Hiçbir sistem tamamen güvenli değildir, ama verini korumak için makul önlemleri alıyoruz.

## 10. Çocuklar

Odometer 13 yaşından küçük çocuklara yönelik değildir ve bilerek onlardan veri toplamayız.

## 11. Değişiklikler

Bu politikayı güncelleyebiliriz. Önemli değişiklikleri uygulama içinde veya bu sayfada duyururuz. Sayfanın başındaki tarih son güncellemeyi gösterir.

## 12. İletişim

Çağrı Döşeyen — **doseyenc.dev@gmail.com**

---

# Odometer Privacy Policy

*Last updated: 27 September 2026*

This policy explains what data the Odometer app (iOS and Android) collects, how it is used and who it is shared with. The developer and data controller is Çağrı Döşeyen. Send questions and requests to **doseyenc.dev@gmail.com**.

## Summary

- Your drives, vehicles and records are stored **on your phone first**.
- You can use the app without an account. An account is needed for backup, friends and the leaderboard.
- We **do not sell** your data or use it for advertising.
- You decide what to share with friends. Drive and location sharing are off by default.

## 1. Data we collect

### Data that stays on your device
- **Location and drive data:** GPS location, speed, route, duration and distance. If automatic drive logging is on, the app also uses location in the background. Without location permission you can start drives manually.
- **Motion detection:** The device's motion/activity sensor is used to detect when you are in a vehicle.
- **Vehicle and expense records:** Vehicle details, fuel, service, expenses, reminders and vehicle photos.
- **Receipt photos:** In receipt scanning, the text is read **on your device** (Google ML Kit / Apple Vision). The photo itself is never sent to a server.

### If you create an account
- **Account details:** Name, email address and password (the password is stored by Firebase Authentication and we cannot see it).
- **Cloud backup:** If you use backup, your vehicles, drives (including routes), fuel/service/expense records, reminders and vehicle photos are stored in Firebase, linked to your account.

### If you use social features
- **Profile:** Nickname, profile photo, region and vehicle label (for example "VW Golf").
- **Leaderboard:** Your weekly/monthly distance, top speed and similar scores. You can leave the leaderboard at any time.
- **Friends:** Your friend code, friend list and the sharing settings you choose for each friend.
- **Shared drives:** If you turn on drive sharing, your drive summaries and routes are visible to the friends you choose.
- **Live location and driving status:** If you turn it on, your location, speed and heading while driving are shown only to friends you allow. No history is kept. The record is overwritten and deleted automatically shortly afterwards.
- **Nudges and notifications:** Nudges you send and receive, and your device's push token and language, used to deliver notifications.
- **Referral program:** Who invited whom and the rewards earned.

### Collected automatically
- **Usage analytics:** Screens opened, features used, subscription screen interactions and install source (Google Play Install Referrer). Collected with Firebase Analytics and Mixpanel.
- **Advertising ID:** The app shows no ads. We do not collect the advertising ID (Android Advertising ID, Apple IDFA).
- **Crash reports:** Device model, OS version and error details (Firebase Crashlytics).
- **App integrity:** Firebase App Check (Play Integrity, App Attest/DeviceCheck) verifies requests come from the genuine app.
- **Purchases:** Subscription status and purchase history (via RevenueCat). Payments are handled by the App Store or Google Play and we never see payment details.

## 2. How we use data

- To record your drives and show statistics, the heat map and drive replay.
- To back up your data and restore it when you switch devices.
- To run social features such as friends, the leaderboard, nudges and live location.
- To send notifications (friend activity, nudges, reminders, rewards).
- To manage your Pro subscription and referral rewards.
- To improve the app, find bugs and prevent abuse.


## 3. Legal bases

We process personal data on the following bases under Article 6 of the GDPR and Article 5 of Turkey's KVKK:

| Processing | Basis |
|---|---|
| Account, cloud backup, subscription and referral rewards | Performance of a contract |
| Location, motion detection, notifications, friend sharing and live location | Consent, given through permissions and sharing settings and revocable at any time |
| AI receipt scanning and driving coach | Consent; these run only when you start the feature |
| Usage analytics, crash reports and abuse prevention | Legitimate interest in keeping the app working and secure |
| Responding to lawful requests from authorities | Legal obligation |

Data is collected electronically through the app, by automated means and from what you enter.

## 4. AI features

- **Receipt scanning:** The receipt **text** read on your device (not the photo) is sent through our server to Anthropic's Claude model to extract the amount and category.
- **Driving coach:** **Summary** driving statistics such as average consumption, eco score and harsh braking/acceleration counts are sent the same way to generate tips. Your routes and location are not sent.

Your name, email or account ID are not passed to the AI provider in these requests.

## 5. Service providers we share data with

Your data is shared only with the following services, only to run the app:

| Provider | Purpose |
|---|---|
| Google Firebase (Authentication, Firestore, Storage, Cloud Functions, Cloud Messaging, Analytics, Crashlytics, App Check) | Account, backup, social features, notifications, analytics, crash reports |
| Mixpanel | Usage analytics |
| RevenueCat | Subscription management |
| Mapbox | Map imagery. The area being shown and your IP address reach Mapbox when maps load. |
| Anthropic | Receipt scanning and driving coach (see above) |
| Apple App Store / Google Play | Downloads, purchases, in-app reviews |

Server-side processing runs in Firebase's European region (europe-west1). Providers may also process data in other countries under their own privacy policies.

We **do not sell** your data or share it with ad networks. We may disclose data to authorities where required by law.


## 6. International transfers

Some of our providers (Google, Mixpanel, RevenueCat, Mapbox, Anthropic) may process data outside Turkey and the European Economic Area, mainly in the United States. These transfers rely on the providers' standard contractual clauses and the other safeguards required under Chapter V of the GDPR and Article 9 of the KVKK.

## 7. Retention

- Data on your device stays there until you delete it or uninstall the app.
- Cloud backup and profile data are kept until you delete your account, and are deleted immediately when you do.
- Live location records are deleted automatically shortly after they are written.
- Analytics and crash data follow the retention periods of those providers.

## 8. Your rights and choices

- **Permissions:** You can turn off location, motion and notification permissions in your device settings at any time.
- **Sharing:** You can turn off drive sharing, live location and notifications separately for each friend.
- **Leaderboard:** You can leave the leaderboard at any time.
- **Deleting your account:** In the app, go to **Profile → Delete my account** to permanently delete your account and all your cloud data (backup, profile, leaderboard entries, friendships, shared drives, photos, push tokens). Deletion happens immediately and cannot be undone. If you can't access the app, email the same request to **doseyenc.dev@gmail.com** from your account's email address and we will complete it within 30 days.
- **Subscription:** Deleting your account does not cancel a Pro subscription. Cancel it in your App Store or Google Play subscription settings.
- **Access and correction:** Email **doseyenc.dev@gmail.com** to request a copy of your data or to correct it.

Under the GDPR you have the right to access, rectify and erase your data, to restrict or object to processing, to data portability and to withdraw consent at any time. Under Article 11 of the KVKK you also have the right to learn whether your data is processed, to request information about it, to know the third parties it is transferred to in Turkey or abroad, to have corrections and deletions notified to them, to object to outcomes against you arising solely from automated analysis, and to claim compensation for damage caused by unlawful processing.

Send requests to **doseyenc.dev@gmail.com** and we will respond within 30 days. If you are not satisfied with our response, you can complain to the Personal Data Protection Authority (KVKK) in Turkey or to the data protection authority in your country in the European Union.

## 9. Security

Data travels between your device and our servers over encrypted connections (HTTPS/TLS). Only you can access your cloud data. Friends can only see what you choose to share. No system is perfectly secure, but we take reasonable measures to protect your data.

## 10. Children

Odometer is not directed at children under 13 and we do not knowingly collect data from them.

## 11. Changes

We may update this policy. We will announce significant changes in the app or on this page. The date at the top shows the latest update.

## 12. Contact

Çağrı Döşeyen — **doseyenc.dev@gmail.com**
