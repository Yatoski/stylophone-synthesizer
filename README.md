# stylophone-synthesizer
An interactive, highly realistic retro Stylaphone S-1 synthesizer simulator built with Web Audio API, Tailwind CSS, and HTML5 Canvas. Features CRT oscilloscopes, VU meters, custom audio effects, and authentic stylus cable physics.
# 🎹 Stylaphone S-1 Retro Synthesizer Simulator

[English](#english) | [Türkçe](#türkçe)

---

## English

An interactive, highly realistic **Retro Stylaphone S-1** synthesizer simulator built from scratch for modern web browsers using Web Audio API, Tailwind CSS, and HTML5 Canvas.

It delivers an authentic retro instrument experience through its sound engine and detailed visual design, featuring an analog VU meter, a CRT oscilloscope display, and dynamic coiled stylus cable physics.

### 🚀 Live Preview
Try the live simulator directly in your browser here:
👉 **[PASTE YOUR LIVE LINK HERE]** *(e.g., https://yourusername.github.io/your-repo/)*

### ✨ Features
* **Authentic Sound Engine:** Real-time analog waveforms (Square/Sawtooth morphing) generated purely via the Web Audio API.
* **Advanced Audio Effects:** Hardware-specific Vibrato (pitch modulation), adjustable Decay knob, and a built-in Delay/Echo effect chain.
* **Live Audio Visualizers:**
  * A nostalgic green-phosphor **CRT Oscilloscope** that draws real-time audio frequencies.
  * A responsive, needle-driven **Analog VU Meter** showing live audio volume output.
* **Physics-Based Stylus Cable:** An interactive, coiled cable simulation rendered on HTML5 Canvas that responds elastically to mouse/stylus movements.
* **Dual Control Scheme:** Play by clicking directly on the keys (stylus touch) or by mapping your computer keyboard (QWERTY and number keys).

### 🛠️ How to Play
1. **Power Switch:** Click the analog power switch on the right side to turn on the instrument.
2. **Keyboard Mapping:** Use your computer's letter keys (`Q`, `W`, `E`, `R`...) or number keys to trigger notes. The corresponding physical keys are written directly on the screen's layout.
3. **Adjust Effects:** * **Vibrato:** Adds a nostalgic pitch modulation to the sound.
   * **Decay Knob:** Controls how long the note fades out after releasing the key.
   * **Delay / Echo:** Click and drag the potentiometer knobs up/down to rotate them and add space to your tone.

### 💻 Technologies Used
* **Front-end:** HTML5, Tailwind CSS
* **Audio Engine:** Web Audio API (`OscillatorNode`, `GainNode`, `DelayNode`, `BiquadFilterNode`)
* **Graphics & Physics:** HTML5 Canvas (Verlet Integration for the coiled wire simulation)
* **Fonts:** Inter & JetBrains Mono (via Google Fonts)

---

## Türkçe

Web Audio API, Tailwind CSS ve HTML5 Canvas kullanılarak modern web tarayıcıları için sıfırdan geliştirilmiş, yüksek gerçeklikte ve etkileşimli bir **Retro Stylaphone S-1** simülatörüdür. 

Hem ses motorunun yapısıyla hem de analog VU metre, CRT osiloskop ekranı ve dinamik sarmal kablo fiziği gibi ince detaylara sahip görsel tasarımıyla otantik bir retro enstrüman deneyimi sunar.

### 🚀 Canlı Önizleme
Projenin çalışan halini tarayıcınızda hemen denemek için aşağıdaki bağlantıya tıklayabilirsiniz:
👉 **[CANLI YAYIN LİNKİNİ BURAYA YAPIŞTIRIN]** *(Örn: https://kullaniciadi.github.io/repo-adi/)*

### ✨ Özellikler
* **Otantik Ses Motoru:** Web Audio API kullanılarak üretilen gerçek zamanlı analog dalga formları (Kare/Testere dişi geçişleri).
* **Gelişmiş Ses Efektleri:** Enstrümana özel Vibrato (perde bükme), ayarlanabilir Decay (sönümlenme) potu ve dahili Delay/Eko efekt zinciri.
* **Canlı Görselleştiriciler:**
  * Ses frekansını anlık çizen nostaljik yeşil fosforlu **CRT Osiloskop**.
  * Ses seviyesini gösteren dinamik, iğneli **Analog VU Metre**.
* **Fizik Tabanlı Kalem Kablosu:** HTML5 Canvas üzerinde, fare hareketlerine esnek ve sarmal bir şekilde tepki veren gerçekçi kalem (stylus) kablo simülasyonu.
* **Çift Kontrol Şeması:** Hem fareyle tıklayarak (stylus dokunuşu) hem de bilgisayar klavyenizle (QWERTY veya sayı tuşları) çalma desteği.

### 🛠️ Nasıl Oynanır?
1. **Güç Anahtarı:** Sağ taraftaki analog güç anahtarına (Power Switch) tıklayarak enstrümanı çalıştırın.
2. **Klavye Eşleştirmesi:** Klavyenizdeki harf tuşlarını (`Q`, `W`, `E`, `R`...) veya sayı tuşlarını kullanarak notaları tetikleyebilirsiniz. Ekrandaki tuşların üzerinde hangi harfe denk geldikleri yazmaktadır.
3. **Efektleri Ayarlayın:** * **Vibrato:** Sese nostaljik bir titreme efekti verir.
   * **Decay Knob:** Tuşlardan elinizi çektiğinizde sesin ne kadar sürede sönümleneceğini ayarlar.
   * **Delay / Echo:** Sese derinlik ve eko katmak için potansiyometreleri farenizle yukarı/aşağı sürükleyerek döndürün.

### 💻 Kullanılan Teknolojiler
* **Front-end:** HTML5, Tailwind CSS
* **Ses İşleme (Audio Engine):** Web Audio API (`OscillatorNode`, `GainNode`, `DelayNode`, `BiquadFilterNode`)
* **Grafik & Fizik:** HTML5 Canvas (Verlet Entegrasyonu ile sarmal kablo fiziği)
* **Yazı Tipleri:** Inter & JetBrains Mono (Google Fonts)

---

## 📄 License / Lisans

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this software for personal or commercial projects.

Bu proje **MIT Lisansı** altında lisanslanmıştır. Kodları dilediğiniz gibi alıp değiştirebilir, geliştirebilir veya kendi projelerinizde kaynak göstererek özgürce kullanabilirsiniz.
