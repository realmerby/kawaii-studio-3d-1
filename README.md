# 🍓 Cute VRM Dress Up ~ (´｡• ω •｡`)

**@pixiv/three-vrm** ve **Three.js** ile güçlendirilmiş, gerçek anime 3D VRM modellerini destekleyen giydirme ve pozlama uygulaması.

---

## ✨ Özellikler

- **Gerçek Anime VRM Modelleri**: VRoid Studio / CustomCast uyumlu, MToon gölgelendirme (toon shading) ve anime outline desteği
- **Mimikler & İfadeler (Morph Targets)**: Mutlu, üzgün, kızgın, rahat, şaşkın ve otomatik doğal göz kırpma (blink)
- **Kemik & Poz Sistemi**: Idle nefes alma animasyonu, barış işareti (peace), el sallama (wave), eller belde pozları
- **Dinamik Renk Özelleştirme**: Göz irisi, saç, kıyafet ve çorap renklerini canlı değiştirme
- **Kafa Kemiğine Bağlı Aksesuarlar**: 🎀 Fiyonk, 👓 Gözlük, 🐱 Kedi Kulakları, 👑 Taç
- **Fotoğraf Modu (Screenshot)**: Tek tıkla yüksek çözünürlüklü PNG fotoğraf kaydetme
- **Sürükle & Bırak (Drag & Drop)**: İstediğin `.vrm` dosyasını tarayıcıya bırakıp anında giydir

---

## 🎀 VRM Modeli Nasıl Eklenir?

1. **[VRoid Studio](https://vroid.com/studio)** (Ücretsiz) üzerinden kendi karakterini tasarla veya **[VRoid Hub](https://hub.vroid.com/)** üzerinden bir model indir.
2. Modeli klasör içine **`model.vrm`** adıyla kaydet (veya uygulama açıkken doğrudan tarayıcıya sürükleyip bırak).

---

## 🚀 Yerel Çalıştırma

```bash
npm start
```
Tarayıcınızda açın: `http://localhost:3000`

---

## 🌐 Vercel Deployment

`vercel.json` içerisinde VRM & WebGL uyumluluğu için gerekli COOP & COEP başlıkları yapılandırılmıştır.
```bash
npx vercel --prod
```
