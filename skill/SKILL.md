---
name: rigprint
description: Bir şarkının ya da gitaristin tonunu Quad Cortex preset'ine çevirirken kullan: öncelikli kaynaklardan araştırır, Original ve Community rig'lerini RigPrint sayfası olarak verir.
---

# RigPrint

Sürüm 1.0 · 28 Ekim 2026 · Cihaz sözlüğü CorOS 4.1.0 dönemi Neural DSP listesinden. Yeni CorOS sürümlerinde eklenen cihazlar sözlükte olmayabilir; şüphede listeyi tekrar kontrol et.

Gereken: kod çalıştırma (Settings > Capabilities > "Create and edit files") ve web araması açık olmalı.

Amaç: "bana şu şarkının tonunu ver" isteğine tahmin değil, kaynağa dayalı ve Quad Cortex'te birebir kurulabilir bir rig vermek. Sonuç her zaman aşağıdaki şablonla yayınlanan RigPrint sayfasıdır. Dil Türkçe.

Güven etiketleri: k = Kesin (belgeli), m = Muhtemelen (güçlü kaynak), t = Tahmin (başlangıç noktası), x = Test edildi (kullanıcı cihazda kurup kulakla onayladı). Kaynaklar çelişiyorsa blokta ayrıca "Tartışmalı" (tz alanı).

## 0. Girdi

- Şarkı ve bölüm (riff, intro, solo, ritim). Belirsizse en tanınan bölümü seç ve cevapta söyle.
- Kullanıcı kendi gitarını ve manyetiklerini söylediyse not al; söylemediyse sorma, "Senin gitarın" bilgisi ekleme.
- Kullanıcının sahip olmadığı ekipmanı "kullanıyorsun" diye yazma.

## 1. Kaynaklar (bu sırayla)

Erişim kuralı: URL'yi ezberden yazıp açma; ezberden yazılan adresler reddedilebiliyor. Önce WebSearch ile sayfayı bul, sonra sonuç linkini WebFetch ile aç. Arama snippet'i kaynak değildir: değer ya da ekipman aldığın her sayfayı aç.

**Katman 1: gitaristin ya da teknisyeninin kendi sözü → k**
- Guitar World, Guitar Player, MusicRadar (Total Guitar içerikleri ve "Rig tour" yazıları dahil), Bonedo, Neural DSP'nin sanatçı ayar yazıları.
- Muzines (muzines.co.uk): 80'ler ve 90'lar dergi röportajı arşivi; o dönemin kayıtları için en iyi kaynak.
- Premier Guitar Rig Rundown: asıl içerik videoda, sayfa metni ince. Sayfadaki etiketler ve "Shop the Rig" listesi kullanılabilir.
- Sound On Sound "Classic Tracks": kaydın stüdyo zinciri (mikrofon, kompresör, oda) için. Her şarkı için yazı yok.

**Katman 2: belgeleyen yayınlar → m**
- Equipboard (gitaristin ekipman listesi; yalnızca kaynak linki olan girdiler).
- Guitar.com rig diagramları, Killer Guitar Rigs, Reverb News ("Potent Pairings", "Copping the … sound" yazıları), Wikipedia (kayıt bilgisi, stüdyo, yıl).
- Forum tariflerinde yapay zekâ üretimi yazılara dikkat: QC'de olmayan cihaz adı (ör. "Scream 808"), tarifin her bloğa düzgün sayılar dağıtması ya da ChatGPT kalıbı varsa o değerleri t say ve notta belirt.
- Seymour Duncan ve Rig-Talk forumları: ekipman tarihçesi tartışmaları; tek başına m vermez, katman 1-2 ile desteklenmeli.

**Katman 3: somut değer veren topluluk tarifleri → Community'nin ana kaynağı**
- unity.neuraldsp.com (QC'ye özel, öncelikli).
- Fractal, Kemper ve Line 6 forumları: mantık QC'ye taşınır, değerler doğrudan değil.
- Guitar Chalk (şarkı bazında amfi ayarları), MusicStrive. ProSoundHQ yalnızca t (kaynak göstermiyor).
- İki bağımsız tarif örtüşüyorsa m, tekse değer t.

**Katman 4: preset pazarları → yalnızca "hangi amfiyi, hangi zinciri seçmişler" bilgisi**
- Liveplayrock, Gumroad satıcıları, Line 6 CustomTone ve Axe-Change (açıklama okunur, blok zinciri ve değerler görünmez), TONE3000 (QC NAM çalıştırmaz; yalnızca IR'lar işe yarar).
- Ücretli içerik kopyalanmaz, değerleri tahmin edilip "onların preset'i" diye sunulmaz.

**Kullanma (test edildi, işe yaramıyor):** Reddit (aramada ve okumada erişilemiyor), The Gear Page (aramada çıkmıyor), Cortex Cloud (preset sayfaları aramada çıkmıyor; yalnızca çıkış hedefi), Kemper Rig Exchange (yalnızca uygulama içi), Andertons Sound Like ve Riffhard (somut ayar yok).

Asgari: Original için en az iki katman 1-2 kaynağı; Community için en az bir katman 3 tarifi somut değerle. Original'e yetecek kaynak bulamazsan uydurma: sadece Community ver ve cevapta "orijinal ekipman belgeli değil" de. Community bulamazsan sadece Original ver.

## 2. İki versiyon

- **Original:** kayıtta kullanılan ekipmanın QC karşılığı; gitaristin kendi verdiği ayarlar varsa onlar. Albüm ve bugünkü canlı rig farklıysa ikinci bir lane olabilir; daha fazlasına gerek yok.
- **Community:** plakta duyulan sesi hedefler. Miks EQ'su, stüdyo kompresörü, chorus, stereo delay, gitaristin sonraki dönem amfisi burada olabilir. Dönem dışı cihaz kullanırsan blok notunda açıkça yaz ("ekipman bu değildi ama ses bu").
- Neden ikisi: tarihî ekipman tek başına çoğu zaman kayda benzemez; kaydın sesi miks zincirinden geçmiş hâlidir. Kullanıcı bulduğu bir preset'i paylaşırsa Community ile karşılaştır ve farkları söyle.

## 3. Kaynak çelişkisi

Kaynaklar aynı blok için farklı ekipman ya da ayar söylüyorsa birini seçip gizleme: blokta tz alanına iki tarafı kaynak adlarıyla yaz (en fazla 2 cümle). Mümkünse diğer seçeneği Community lane'ine koy.

## 4. Quad Cortex eşlemesi

- Cihaz adlarını aşağıdaki sözlükten al (kaynak: neuraldsp.com/device-list, CorOS 4.1.0 dönemi). Sözlükte yoksa listeyi WebSearch + WebFetch ile tekrar kontrol et; yine yoksa en yakınını seç ve notta "QC'de yok, en yakını" yaz.
- Parametre adları listede yok. Bilinen amfi düğmeleri (Gain, Bass, Middle, Treble, Presence, Master/Volume) dışında emin değilsen notta belirt.
- Plugin cihazları (Archetype serisi, Soldano SLO-100 X vb.) yalnızca o plugin'e sahip olanlarda açılır; varsayılan olarak kullanma.
- Cihaz listesini çekerken kategori atlama: synth ve morph cihazları ayrı kategoride duruyor; listede gördüğün her kategoriyi kontrol et.
- QC sınırları: NAM dosyası çalıştırmaz (IR yükler); preset dosyası dışa/içe aktarılamaz; Cortex Cloud'un açık API'si yok. Otomatik yükleme ya da cihaz root'lama önerme. Preset'i kullanıcı cihazda veya Cortex Control'de kurar.

### Parametre adları ve birimleri

Neural DSP cihaz bazında parametre listesi yayınlamıyor. Aşağıdakiler kaynaklarla doğrulanmış olanlar; listede olmayan cihazlarda orijinal donanımın panel adlarını kullan ve ayarı t işaretle. Birimini bilmediğin bir parametreyi 0-10'a çevirme: Hz, dB, %, ms ya da semitone olan parametreyi o birimle yaz; birimi bulamadıysan değeri sözle ver ("yavaş", "az", "kulakla") ve cihazda kontrol edilmesini söyle. Orijinal donanımda olmayan düğmeyi uydurma (ör. Plexi'de ve eski AC30'da Master yok; AC30 Normal kanalında tiz/bas yok, sadece Volume ve Cut).

- **Capture'lar (Neural Capture V1/V2, ör. Bogna X100B, ABA MPre1):** Gain, Bass, Mid, Treble, Volume, hepsi dB. Tonestack değil, capture'dan sonra çalışan EQ; Presence yok.
- **Amfiler:** Neural'ın genel listesi Gain, Volume, Bass, Middle, Treble, Master, Presence, Depth, Resonance, Bright ve Output; her amfide hepsi yok. Hangi düğmelerin olduğunu orijinal panelden çıkar.
- **Kabinler:** Mic (ör. Dynamic 57, Dynamic 421, Ribbon 160, Condenser 414; kabine göre değişir), Position (koninin merkezinden kenarına), Distance (yakından odaya), Level, Pan, Phase Inverter; iki ayrı IR bölümü; HPF ve LPF (Hz). Position/Distance için birim belgelenmemiş: sözle yaz ("merkez", "yakın").
- **Adaptive Gate:** Attack/Release yok, zaman sabitleri otomatik. Threshold'u kulakla ayarlat.
- **Wham:** Pedal (expression'a atanır, %0-100), Toe 1, Heel 1, Toe 2, Heel 2 (semitone), Blend. Whammy'deki gibi mod seçimi yok: +2 oktav = Toe 1 +24, Heel 1 0.
- **Mono Synth (Overlord):** Gate, Sensitivity, Glide, Env. Retrigger, Mix, Output; amp zarfı Decay/Attack (tek, iki yönlü düğme) + Sustain; OSC1/OSC2: Active, Waveform (Sine, Triangle, Sawtooth, Square, Pulse, White Noise, Pink Noise), Semitones (±24), Detune (±100 cent), Level, Unison (ses sayısı), Width, unison Detune; filtre: Active, Slope (dB/oktav), Cutoff (Hz), Resonance, Envelope (-100…+100), Decay/Attack, Drive. Filtre tipi seçimi ve LFO yok.
- **Parametric-3 / Parametric-8:** her bant için tip (Peak, Hi-Pass, Lo-Pass, Hi-Shelf, Lo-Shelf), Freq (Hz), Gain (dB), Q; ayrıca HPF ve Output. Değeri "Band 2 · Peak: 800 Hz · +2 dB" biçiminde yaz.
- **Graphic-9:** bant frekansları belgelenmemiş (HPF Off-500 Hz ve ikinci sayfada LPF var). EQ gerektiğinde Parametric-3 kullan.
- **Delay'ler:** Time, Feedback, Mix, Sync; Digital/Dual Delay'de Dyn Mode (Duck/Gate). Time'ı ms ya da nota değeriyle ver.
- **Reverb'ler:** Decay (%), Pre Delay, Mix (%), High/Low Pass, Trails.
- **Kullanıcının cihazından gelen bilgi** (ekran görüntüsü ya da "cihazda şöyle görünüyor") her kaynağın önüne geçer.

### Cihaz sözlüğü (QC adı = gerçek ekipman)

**Gitar amfileri:** Brit 2203 = Marshall JCM800 · Brit 900 Clean/Lead = JCM900 4100 · Brit Plexi 100 Bright/Normal/Patch = Super Lead 100 · Brit Plexi 50 Bright/Normal/Patch = Lead 50 · Brit TM45 Bright/Normal/Patch = JTM45 · Brit UBL Lead / Lead Clip = Silver Jubilee · Bogna Uber Clean/Lead = Bogner Uberschall Rev. Blue · Bogna Vishnu 20th Clean = Bogner Shiva 20th · CA 1Star Clean/Drive (50W/100W, Normal/Tweed) = Mesa Lone Star · CA Duo Ch3 Modern/Raw/Vintage = Mesa Dual Rectifier · CA John's 2C Ch1-3 = Mesa JP2C · CA Tremo Orange/Red = Mesa Trem-O-Verb · Captain 50 = Morgan SW50 · D-Cell H4 Ch1-4 = Diezel VH4 · D-Cell Hisbert Ch1-3 = Diezel Herbert · Dumbbell ODS = Dumble Overdrive Special · EV101IIIS Blue/Red EL34 100W = EVH 5150 III S EL34 · EV101IIIS Blue/Red 6L6 100W = EVH 5150 III 100S 6L6 · Freeman 100 Clean/Rhythm/Lead = Friedman HBE100 · Matchmore D30 Ch1/Ch2 = Matchless DC30 · Matchmore Jefe = Matchless Chieftain · PV-505 Lead/Rhythm = Peavey 6505 · Rols Jazz CH120 = Roland JC-120 · Solo 100 Crunch Bright/Normal, Solo 100 Lead = Soldano SLO 100 · UK C15 Normal/TopBoost = Vox AC15 · UK C30 Normal/TopBoost = Vox AC30 · US DLX 64 Vintage = Deluxe Reverb '64 · US DLX 65 Reissue = Deluxe Reverb '65 RI · US HP Tweed TWN Bright/Normal (+Patch) = High Power Tweed Twin 5F8-A · US Prince = Blackface Princeton Reverb · US SPR Normal/Vibrato = Super Reverb '65 · US Tweed Basslad Bright/Normal (+Patch) = Tweed Bassman · US TWN Normal/Vibrato = Twin Reverb · Victor Squid Ch1/Ch2 = Victory Kraken · Watt D103 Bright/Normal = Hiwatt DR103.

**Gitar amfisi capture'ları (V2):** Brit 2203 87 = JCM800 1987 · DC Heavy Crusader = DCA Heavy Metal Warfare · Dovre 50 = Dover DA-50 · Drywood Purple Horror = Driftwood Purple Nightmare · Dumbbell ODS = Dumble ODS · ENG Feral 120 = ENGL Savage 120 · EV101IIIS EL34 = 5150 III S EL34 · Fryed Pit Bull 50 = Fryette Pittbull Fifty · Nailer Battle 38 = Naylor Duel 38 · RV Amp G120 = Revv Generator 120 MK3 · US DLX 58 = Fender Deluxe 5E2 1958 · UK C10 64 = Vox AC10 1964 · Gibb GA8 = Gibson GA-8 · Super Bolt = Supro Thunderbolt.

**Gitar amfisi capture'ları (V1):** ABA MPre1 = ADA MP-1 · Bogna Fish = Bogner Fish · Bogna Uber = Uberschall · Bogna X Blue = Ecstasy Blue · Bogna X100B Ch1/Ch2/Ch3 = Ecstasy 100B (Pre Ch2 Hi/Lo, Pre Ch3 Lead/Plexi preamp varyantları da var) · Brit 2210 = JCM800 2210 · Brit 2555 Clean/Rhy/Lead = Silver Jubilee 2555 · CA 3Axe = Mesa Triaxis · CA John's Ch1-3 = Mesa JP2C · CA MkCC+ = Mesa Mark IIC+ · CA MkIIIRed = Mesa Mark III Red Stripe · CA Quad+290 = Mesa Quad Preamp · CA Studio+290 = Mesa Studio Preamp · CA Tremo Blues/Clean/Modern/Vintage = Trem-O-Verb · Comet 60 = Komet 60 · Corn Vixen = Cornford Hellcat · Crank Rev1 = Krank Rev1 · Cravin X100 = Carvin X100B · Custom 3SE = Custom Audio 3+SE · D-Cell H4 Ch1-4 = Diezel VH4 · D-Cell Herb = Diezel Herbert · ENG Energy = ENGL Powerball · ENG Marty's = ENGL Inferno · ENG Rainbow = ENGL Blackmore · Exotic BB = Xotic BB Preamp · Fryed Sig10 = Fryette SigX · MetalX M1K = Metaltronix M1000 · NoMatch Chief = Matchless Chieftain · Paul's MT16 = PRS MT15 · PV 505Sig = Peavey 5150 · Range Rock = Orange Rocker 30 · Range Rverb = Orange Rockerverb 100 · Range Stormverb = Orange Thunderverb 50 · SCity B120 = Sound City B120 · TeaBird = Antti T-Bird · TuneRoyal MK2 = Tone King Imperial MKII · US HRDLX ChA/ChB = Fender Hot Rod Deluxe · US Prince 65 = Princeton 65 · Victor Marshal = Victory Sheriff 22 · Victor Mega Squid = Victory Super Kraken · Watt Custom 1959/Clean/Jose/VH = Hiwatt Custom PA100.

**Overdrive / boost / fuzz:** 81 Creations Drive = 1981 DRV · Brit Blues = Bluesbreaker · Brit Governor = Guv'nor · Chief BD2 / DS1 / MT / OD1 / SD1 / HM2 = Boss BD-2 / DS-1 / MT-2 / OD-1 / SD-1 / HM-2 · Exotic = Xotic BB Preamp · Exotic Z Boost = Xotic RC Booster · Facial Fuzz = Fuzz Face · Freeman BOD = Friedman BE-OD · Fuzz Pi = Big Muff Pi · Green 808 = Ibanez TS808 · MK3 Silicon Fuzz = JHS Bender 1973 · Myth Drive = Klon Centaur · No-Bell OD1 = Nobels ODR-1 · Obsessive Drive = Fulltone OCD · OD250 = DOD 250 · Rage Booster = Dallas Rangemaster · Red Drive = Keeley Red Dirt · Rodent Drive = ProCo Rat · Thunderpaw = Mr Black Thunderclaw · Vemural Ray = Vemuram Jan Ray · Love Champion / DLX / TM / Drive 11 = Lovepedal Champ / 5E3 / JTM / OD Eleven · TW Tube Drive = Tube Works Tube Driver · Unsound Shivver = Shivver · Beehive Wasp Fuzz = Beetronics Vezzpa · Iba Basic Fuzz = Ibanez No. 59 · Love Believer = Lovepedal Believe · Love Bender Mk3 = MKIII Tonebender · Love Fuzz Lord III = Fuzz Master III · Otso Bender Mk1 = Otsola Mk1 · Reus Bender Mk2 = Germanium Bender · Trademark Fuzz = Hallmark Nu-Fuzz.

**Kompresör:** Chief CS3 = Boss CS-3 · Jewel = Diamond Compressor · Legendary 87 = UA 1176 · Solid State Comp = SSL Bus · Opto Comp, VCA Comp (genel) · 4-Comp Custom = Keeley 4 Knob · Bogna Bloom = Bogner Harlow · OC-76 Comp = Origin Cali76.

**Wah / filtre / pitch:** Crying Wah = Cry Baby GCB-95 · Crying Clyde Wah = Clyde McCoy · Crying Wah From Hell = Crybaby from Hell · Bad Horse = Morley Bad Horsie · Bubba Wah = Budda Budwah · Auto Wah, Env. Filter (genel) · Foog = Moogerfooger MF-101 · Love Meat = Lovetone Meatball · Wham = DigiTech Whammy · Chief OC2 = Boss OC-2 · Poly Octaver = EHX POG · Pitch Shifter, Transpose, Minivoicer, Multivoicer (genel).

**Modülasyon:** Chief CE2W = Boss CE-2W · Chief DC2W = Boss Dimension DC-2W · Chorus 229T = TC 2290 · Dream Chorus = TC Dreamscape · MX Flanger = MXR M117R · MX Phase 95 = MXR Phase 95 · MX Vibes = MXR UniVibe · Micro Processor (ST) = Eventide MicroPitch · genel: Chorus Engine, Dual Chorus, Vintage Chorus, Digital Flanger, Flanger Engine, Flangerish, Phaser, Tremolo, Harmonic Tremolo, Pattern Tremolo, Vibrato, Rotary.

**Synth / morph:** Mono Synth = Archetype: Rabea X'teki Overlord Synth'in ücretsiz versiyonu (CorOS 3.3.0+; iki oscillator: sine/triangle/sawtooth/square/pulse/noise, Semitones ±24, Detune, Unison + Unison Detune, filtre: Slope, Cutoff, Resonance, Envelope amount, tek düğmeli Attack/Decay, Drive; amp zarfı Attack/Decay + Sustain; Gate, Sensitivity, Glide, Mix; MIDI nota kontrolü) · Bit-Crusher · Phase-Locked Loop. Synth, klavye ya da synth bas tonu istenirse önce Mono Synth kullan; yalnızca tek nota takip eder.

**Delay (hepsi genel):** Analog Delay, Slapback Delay, Digital Delay, Dual Delay, Simple Delay, Simple Ping Pong Delay, Tape Delay, Reverse Delay, Dual Reverse Delay, Circular Delay, Arpeggio Delay, Crystal Delay.

**Reverb:** Room, Hall, Plate, Plate Lush, Plate Tight, Ambience, Cave, Mind Hall, Modulated, Shimmer, Spring (M/ST), Spring Reverb Engine · Studio Plate 70 (ST) = Lexicon PCM70 Rich Plate · Nordic Concert Hall (ST) = Valhalla VintageVerb Concert Hall · Blossom (ST) = Strymon BigSky Bloom · Vintage Digital = Oto BAM.

**EQ / utility:** Graphic-9, Parametric-3, Parametric-8, Low-High Cut · Adaptive Gate, Simple Gate, Utility Gate, Gain, Volume, Doubler, Transparent Blend · Phase Doctor = Little Labs IBP.

**Gitar kabinleri:** 110 US PRN C10R / Gold G10 / Brown FatJ 10s = Princeton · 112 UK C15 Blue = AC15 Alnico Blue · 112 US DLX Black C12K 00s = Blackface Deluxe · 112 US DLX SC64 · 112 US DLX Tweed WGS-Q 10s · 112 Brit P-Series TX 33 = Marshall 1933 · 112 Zila MiniMod RB '17 · 210 US TRMLX Oxf '63 = Tremolux · 212 UK C30 '65 = AC30 Silver Bell · 212 UK C30 GB '69 = AC30 Greenback · 212 US TWN C12Q 00s / CK2 = Twin Reverb · 212 US TWN Web Classic 08 = Tweed Twin · 212 US Bleached Basslad V30 01 = Blonde Bassman V30 · 212 US A-type 00s · 212 Rols Jazz '87 = JC-120 · 212 CA Recto V30 '98 / Legend V12 = Mesa Recto 2x12 · 212 Sur V-type 10 = Suhr · 212 Too Rock EV/G65/KM65 = Two Rock · 212 Zila CB '16 / Fatboy V30 '02 / Open CL80 19 / Open G65 82 / Open Gold '19 · 410 US Basslad PR10 = Tweed Bassman · 412 Brit 60A G75 80s = Marshall 1960A G12T-75 · 412 Brit 60A GB75Hz '89 = 1960A G12M25 · 412 Brit 60A LB50 12 = 1960A Lynchback · 412 Brit 60B GB '71 = 1960B Pulsonic Greenback · 412 Brit 60B GB 90s = 1960B Greenback · 412 Brit 60B V30 '95 = 1960B Vintage 30 · 412 Brit 35B Alnico Cream · 412 Brit Silver B 70w '87 = Jubilee 2551B · 412 Brit TV GB75Hz '69 = 1960TV · 412 Bogna Uber T75 00s / V30 00s · 412 CA Custom A Shadow 87 · 412 CA Dagger A V30 01 · 412 CA Stand OS A V30 '01 / '03 · 412 CA Stand OS S V30 90s · 412 CA Trad A V30 '92 · 412 CA Trad S H30 '15 · 412 CA Trad S UKV30 90s · 412 Cornfield V30 · 412 D-Cell Front V30 '04 · 412 ENG Pro V30 18 · 412 EV Straight G12 00s = EVH G12EVH · 412 Range PPC V30 '02/'03 = Orange PPC412 · 412 VH Fat P50 = VHT Fat Bottom · 412 Watt S4123 = Hiwatt SE4123 · 412 Zila Cust V30 '12 V2 · Match D30 Sig A/B · Match Jefe Sig 02 / V30 02.

## 5. Değer kuralları

- Ölçek 0-10. Saat konumu çevirisi: saat 7 = 0, saat 12 = 5, saat 5 = 10; her saat ≈ 1 birim.
- Her blokta iki ayrı etiket: ekipman güveni (oc) ve ayar güveni (sc).
- Birimler QC'deki gibi yazılır: reverb Decay yüzde (%) gösterilir, saniye yazma. Kaynak saniye veriyorsa yaklaşık çevir (0.8 s ≈ %20, 1.5 s ≈ %35, 2 s ≈ %45, 2.5 s ≈ %55) ve ayarı t olarak işaretle. Delay Time ms, Mix ve Feedback yüzde. Kullanıcı bir birimin cihazda farklı göründüğünü söylerse onun söylediği doğrudur; düzelt.
- Kaynağın verdiği değer olduğu gibi yazılır; dönüştürdüğün ya da tahmin ettiğin değer blok notunda belirtilir.
- Bir lane en fazla 8 blok. Ritim ve solo farklı amfi istiyorsa iki lane (scene olarak kurulacak).
- Kullanıcı gitarını söylediyse: kaynağın gitarıyla fark yaratan bloklara (amfi, drive, EQ) g alanında tek cümlelik uyarlama yaz ("Single coil'de gain'i 1 artır, tizi 1 kıs" gibi). Söylemediyse g yok.

## 6. Test edildi

Kullanıcı preset'i cihazda kurup sonucu söylerse ("gain 5 oldu, chorus'u kapattım"): ilgili blokların değerlerini güncelle, sc'yi x yap, gerekirse notu kısalt ve aynı dosya yoluyla yeniden yayınla. Kullanıcının söylemediği bloklara x verme.

## 7. Benzer şarkılar

Her şarkıya 2-3 "Bu rig'le çalınabilecekler" önerisi: aynı albüm ya da aynı dönem rig'i olan şarkılar. Biçim: [şarkı, "Sanatçı · Albüm", kısa neden]. Emin olmadığın bir ekipman iddiasını neden kısmına yazma; "Aynı albüm, aynı rig" yeterli.

## 8. Veri şeması

Her şarkı bir nesne:

- id: kısa, küçük harf, tire yok (ör. "rosanna")
- slot: artifact'taki sıraya göre 1A, 1B … 1H, sonra 2A … (QC'deki 8'li preset grubu mantığı)
- song, artist ("Grup · Gitarist"), meta ("Albüm · Yıl")
- guitar: [[etiket, html], …] — orijinal gitar(lar), sonuna güven rozeti: <span class='badge k'>Kesin</span> (m / t aynı şekilde). İsteğe bağlı ["Gitar ayarı", "Köprü, volume tam"].
- original: {lanes: [lane, …]}
- community: {lanes: [lane, …]} ya da null
- lane: {label: "Original · Ritim" / "Community · Solo" gibi, cells: [blok, …]}
- blok: {c: amp | drive | cab | mod | delay | rev | pitch | wah | util | eq | cap, d: QC cihaz adı, o: orijinal ekipman, oc: k|m|t, sc: k|m|t|x, p: [[etiket, değer, max, birim], …], n: not (en fazla 3 cümle), tz: çelişki notu (isteğe bağlı), g: gitar uyarlaması (isteğe bağlı), stomp: 1 (footswitch'e atanacaksa), pre: 1 (amfiden önce olması kritikse)}
- p kuralı: düğme için ["Gain", 6.5, 10] ya da ["Time", 380, 1000, "ms"]; metin değer için ["Mode", "Vibrato kanalı", null].
- orig: orijinal sinyal akışı. Tek zincir: ["Gitar", "Pedal", "Amfi", "Kabin"]. Birden fazla zincir: [["Ritim:", …], ["Solo:", …]] (ilk eleman ":" ile biterse satır etiketi olur).
- origNote: tek cümle ya da "".
- similar: [[şarkı, "Sanatçı · Albüm", neden], …]

Notlarda "Original" / "Community" adlarını kullan; V1/V2 yazma.

## 9. Sayfa (artifact)

- Sohbetteki ilk şarkı: aşağıdaki şablonu olduğu gibi kullan, sadece `/*SONGS*/[]` kısmını `[şarkı]` JSON'uyla değiştir.
- Ortamında HTML sayfası ya da artifact yayınlama imkânı varsa sayfayı öyle ver (simge seçiliyorsa: guitar). Yoksa rigprint.html dosyası olarak ver; kullanıcı tarayıcıda açar.
- Aynı sohbette sonraki şarkılar: aynı sayfadaki dizinin sonuna ekle ve aynı sayfayı güncelle (mümkünse aynı link). Sayfa açılışta en son eklenen şarkıyı gösterir; hepsi üstte yan yana listelenir.
- Kullanıcı önceki bir RigPrint sayfasının linkini ya da HTML'ini verirse: songs dizisini oradan al, yeni şarkıyı ekle.
- Şablonun başka hiçbir yerini değiştirme. Kod çalıştırabiliyorsan yayından önce JS'i node --check ile kontrol et.

## 10. Sohbet cevabı

Kısa tut, sayfadaki içeriği tekrarlama:

1. Bir cümle: neyi verdin, hangi versiyonlar var, en belirsiz nokta ne.
2. Scene/stomp planı tek satır (hangi scene'de hangi lane ve blok açık).
3. Cortex Cloud metni: ad "DS RigPrint · <Şarkı>" + 2-3 cümle açıklama; açıklamanın ilk kelimesi versiyon olsun ("Original." ya da "Community.") (hangi kayıt, hangi gitar ve manyetik, kaynak adları). Bu ad formatını değiştirme: herkes aynı formatla yüklerse Cortex Cloud'da "DS RigPrint" araması bütün test edilmiş preset'leri bir arada gösterir. Kullanıcıya preset'i test ettikten sonra bu adla yüklemesini öner.
4. "Sources:" listesi: açtığın sayfalar, markdown link. Kaynaklar sayfada gösterilmez; yeri burası.

## 11. Yapma

- Ücretli preset paketlerinin içeriğini kopyalama ya da yeniden dağıtma.
- Kaynaksız değeri k ya da m diye etiketleme; kullanıcı onaylamadan x verme.
- QC listesinde olmayan cihaz adı yazma.
- Community dönem dışıysa bunu gizleme.

## Şablon

```html
<title>RigPrint</title>
<meta name="claude:viewport-fit-sides" content="cover">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@500;600;700&family=Barlow:wght@400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap">
<style>
/* Floor-unit face: setlist strip, signal grid, parameter editor. Deliberately single dark theme (hardware panel). */
:root{
  --chassis:#16181b;--panel:#1e2125;--panel-2:#262a2f;--line:#353a41;
  --ink:#e8e6e1;--ink-dim:#9aa0a8;--led:#ffb547;--led-dim:#7a5a2a;--wire:#4b525b;
  --c-amp:#e0564b;--c-drive:#f08a3a;--c-cab:#8b939d;--c-mod:#4f9be0;--c-delay:#36b3a3;--c-rev:#9b7ae0;
  --c-pitch:#e05aa0;--c-wah:#d9b833;--c-util:#6c7a8a;--c-eq:#7cc35a;--c-cap:#c86be0;
  --k:#5fbf7a;--m:#e3b341;--t:#d77a5a;--x:#3fd0c9;--d:#b48cf2;
  --f-display:"Barlow Condensed","Arial Narrow",system-ui,sans-serif;
  --f-body:"Barlow",system-ui,-apple-system,sans-serif;
  --f-mono:"IBM Plex Mono",ui-monospace,Menlo,monospace;
  color-scheme:dark;
}
*{box-sizing:border-box}
body{background:var(--chassis);color:var(--ink);font-family:var(--f-body);font-size:15px;line-height:1.5;margin:0;
  padding-left:max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px));padding-block:20px 40px}
.wrap{max-width:1080px;margin:0 auto;display:flex;flex-direction:column;gap:18px}
header{display:flex;flex-wrap:wrap;align-items:end;justify-content:space-between;gap:8px 24px}
h1{font-family:var(--f-display);font-weight:700;font-size:clamp(28px,5vw,40px);letter-spacing:.02em;text-transform:uppercase;margin:0;line-height:1}
h1 span{color:var(--led)}
.legend{display:flex;flex-wrap:wrap;gap:10px;font-family:var(--f-mono);font-size:12px;color:var(--ink-dim)}
.legend b{font-weight:500}
.badge{display:inline-flex;align-items:center;gap:6px;font-family:var(--f-mono);font-size:11.5px;letter-spacing:.02em;padding:2px 8px;border-radius:999px;border:1px solid currentColor;white-space:nowrap}
.badge::before{content:"";width:6px;height:6px;border-radius:50%;background:currentColor}
.badge.k{color:var(--k)} .badge.m{color:var(--m)} .badge.t{color:var(--t)} .badge.x{color:var(--x)} .badge.d{color:var(--d)}
.setlist{display:grid;grid-template-columns:repeat(auto-fill,minmax(160px,1fr));gap:8px}
.preset{all:unset;cursor:pointer;display:flex;gap:10px;align-items:center;background:var(--panel);border:1px solid var(--line);border-radius:8px;padding:10px 12px;min-width:0}
.preset:hover{border-color:var(--wire)}
.preset:focus-visible{outline:2px solid var(--led);outline-offset:2px}
.preset[aria-selected="true"]{border-color:var(--led);background:var(--panel-2)}
.preset .slot{font-family:var(--f-mono);font-size:12px;color:var(--led);border:1px solid var(--led-dim);border-radius:4px;padding:1px 5px;flex:none}
.preset[aria-selected="true"] .slot{background:var(--led);color:#1a1205;border-color:var(--led)}
.preset .nm{min-width:0}
.preset .song{font-family:var(--f-display);font-weight:600;font-size:16px;letter-spacing:.02em;line-height:1.15;display:block;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.preset .art{font-size:12.5px;color:var(--ink-dim);display:block;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.device{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:16px;display:flex;flex-direction:column;gap:14px;box-shadow:0 1px 0 rgba(255,255,255,.04) inset}
.screen-head{display:flex;flex-wrap:wrap;justify-content:space-between;align-items:center;gap:8px 16px;border-bottom:1px solid var(--line);padding-bottom:10px}
.screen-head h2{font-family:var(--f-display);font-weight:700;font-size:24px;letter-spacing:.03em;margin:0;text-transform:uppercase}
.screen-head .meta{display:block;font-family:var(--f-mono);font-size:12px;color:var(--ink-dim)}
.ver{display:inline-flex;border:1px solid var(--line);border-radius:8px;overflow:hidden;flex:none}
.ver button{all:unset;cursor:pointer;font-family:var(--f-display);font-weight:600;font-size:13.5px;letter-spacing:.06em;text-transform:uppercase;padding:7px 14px;color:var(--ink-dim);white-space:nowrap}
.ver button+button{border-left:1px solid var(--line)}
.ver button[aria-pressed="true"]{background:var(--led);color:#1a1205}
.ver button:focus-visible{outline:2px solid var(--led);outline-offset:-2px}
.guitar{display:grid;grid-template-columns:auto 1fr;gap:4px 14px;font-size:14px;margin:0}
.guitar:empty{display:none}
.guitar dt{font-family:var(--f-display);font-weight:600;letter-spacing:.06em;text-transform:uppercase;font-size:12.5px;color:var(--ink-dim);padding-top:2px}
.guitar dd{margin:0;min-width:0}
.grid-scroll{overflow-x:auto;margin-inline:-4px;padding:4px}
.grid{min-width:760px;display:flex;flex-direction:column;gap:14px}
.lane-label{font-family:var(--f-display);font-weight:600;font-size:13px;letter-spacing:.08em;text-transform:uppercase;color:var(--ink-dim);margin-bottom:6px}
.lane{display:grid;grid-template-columns:34px repeat(8,1fr) 34px;align-items:center;gap:8px;position:relative}
.lane::before{content:"";position:absolute;left:17px;right:17px;top:50%;height:2px;background:var(--wire);z-index:0}
.io{position:relative;z-index:1;font-family:var(--f-mono);font-size:10.5px;color:var(--ink-dim);background:var(--chassis);border:1px solid var(--line);border-radius:50%;width:34px;height:34px;display:grid;place-items:center}
.cell{position:relative;z-index:1;height:68px}
.cell.empty::after{content:"";position:absolute;left:50%;top:50%;width:6px;height:6px;border-radius:50%;background:var(--line);transform:translate(-50%,-50%)}
.blk{all:unset;cursor:pointer;position:relative;z-index:1;display:flex;flex-direction:column;justify-content:space-between;height:68px;border-radius:8px;padding:7px 8px;background:var(--panel-2);border:1px solid var(--line);border-top:4px solid var(--cat);min-width:0}
.blk:hover{border-color:var(--cat)}
.blk:focus-visible{outline:2px solid var(--led);outline-offset:2px}
.blk[aria-pressed="true"]{background:color-mix(in srgb,var(--cat) 22%,var(--panel-2));border-color:var(--cat)}
.blk.pre{box-shadow:0 0 0 1px var(--led-dim) inset}
.blk .cat{font-family:var(--f-display);font-weight:600;font-size:10.5px;letter-spacing:.1em;text-transform:uppercase;color:var(--cat)}
.blk .dev{font-family:var(--f-display);font-weight:600;font-size:14px;line-height:1.1;letter-spacing:.01em;overflow:hidden;display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical}
.blk .stomp{position:absolute;top:5px;right:6px;width:7px;height:7px;border-radius:50%;background:var(--led);box-shadow:0 0 6px var(--led)}
.editor{background:var(--chassis);border:1px solid var(--line);border-radius:10px;padding:16px;display:flex;flex-direction:column;gap:14px}
.ed-head{display:flex;flex-wrap:wrap;gap:8px 14px;align-items:center}
.ed-cat{font-family:var(--f-display);font-weight:700;font-size:12px;letter-spacing:.12em;text-transform:uppercase;padding:3px 8px;border-radius:4px;background:var(--cat);color:#111}
.ed-head h3{font-family:var(--f-display);font-weight:700;font-size:22px;letter-spacing:.02em;margin:0}
.orig{font-size:14.5px;color:var(--ink-dim);margin:0}
.orig strong{color:var(--ink);font-weight:600}
.knobs{display:flex;flex-wrap:wrap;gap:14px 18px}
.knob{display:flex;flex-direction:column;align-items:center;gap:4px;width:82px}
.knob svg{width:64px;height:64px}
.knob .v{font-family:var(--f-mono);font-size:13px;font-variant-numeric:tabular-nums}
.knob .l,.switch .l{font-family:var(--f-display);font-weight:600;font-size:12px;letter-spacing:.08em;text-transform:uppercase;color:var(--ink-dim);text-align:center;line-height:1.15}
.switch{display:flex;flex-direction:column;align-items:center;gap:6px;min-width:82px;max-width:150px}
.switch .chip{font-family:var(--f-mono);font-size:12.5px;padding:6px 10px;border:1px solid var(--led-dim);color:var(--led);border-radius:6px;text-align:center}
.badges{display:flex;flex-wrap:wrap;gap:8px}
.note{font-size:14.5px;margin:0;max-width:72ch}
.dispute{font-size:14px;margin:0;max-width:72ch;color:var(--ink);border-left:2px solid var(--d);padding-left:10px}
.dispute b{color:var(--d);font-weight:600}
.adapt{font-size:12.5px;color:var(--ink-dim);margin:0;max-width:72ch;border-top:1px dashed var(--line);padding-top:10px}
.adapt b{color:var(--ink);font-weight:600}
.similar{list-style:none;margin:0;padding:0;display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:8px}
.similar li{background:var(--panel-2);border:1px solid var(--line);border-radius:8px;padding:8px 10px;min-width:0}
.similar .s{font-family:var(--f-display);font-weight:600;font-size:15px;letter-spacing:.02em;display:block}
.similar .a{font-size:12.5px;color:var(--ink-dim);display:block}
.similar .w{font-size:13px;display:block;margin-top:4px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:14px 16px;min-width:0}
.card h4{font-family:var(--f-display);font-weight:600;font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--ink-dim);margin:0 0 10px}
.chain{display:flex;flex-wrap:wrap;gap:6px;align-items:center;font-size:14px;margin:0;padding:0;list-style:none}
.chain li{background:var(--panel-2);border:1px solid var(--line);border-radius:6px;padding:3px 8px}
.chain li+li::before{content:"→";color:var(--ink-dim);margin-right:6px;margin-left:-2px}
.chain+.chain{margin-top:8px}
.chain .lbl{background:none;border:0;padding:3px 2px;font-family:var(--f-display);font-weight:600;font-size:12.5px;letter-spacing:.08em;text-transform:uppercase;color:var(--ink-dim)}
.chain .lbl+li::before{content:none}
.chain-note{font-size:14px;color:var(--ink-dim);margin:10px 0 0}
.chain-note:empty{display:none}
footer{font-size:13px;color:var(--ink-dim);text-align:center;padding-top:6px}
footer a{color:var(--led);text-decoration:none;font-weight:600}
footer a:hover{text-decoration:underline}
footer a:focus-visible{outline:2px solid var(--led);outline-offset:2px;border-radius:2px}
@media (prefers-reduced-motion:reduce){*{transition:none!important}}
</style>

<div class="wrap">
  <header>
    <h1>Rig<span>Print</span></h1>
    <div class="legend" aria-label="Güven etiketleri">
      <span class="badge k">Kesin</span><b>belgeli</b>
      <span class="badge m">Muhtemelen</span><b>güçlü kaynak</b>
      <span class="badge t">Tahmin</span><b>başlangıç noktası</b>
      <span class="badge x">Test edildi</span><b>kulakla onaylı</b>
      <span class="badge d">Tartışmalı</span><b>kaynaklar çelişiyor</b>
    </div>
  </header>

  <nav class="setlist" role="tablist" aria-label="Şarkılar" id="setlist"></nav>

  <div class="device">
    <div class="screen-head">
      <div><h2 id="songTitle"></h2><span class="meta" id="songMeta"></span></div>
      <div class="ver" id="ver" role="group" aria-label="Versiyon"></div>
    </div>
    <dl class="guitar" id="guitar"></dl>
    <div class="grid-scroll"><div class="grid" id="grid"></div></div>
    <div class="editor" id="editor" aria-live="polite"></div>
  </div>

  <div class="card"><h4>Orijinal sinyal akışı</h4><div id="origChain"></div><p class="chain-note" id="origNote"></p></div>

  <div class="card" id="simCard"><h4>Bu rig'le çalınabilecekler</h4><ul class="similar" id="similar"></ul></div>

  <footer>© Bu bir <a href="https://www.ssslap.com" target="_blank" rel="noopener">Slap Studio</a> güzelliğidir.</footer>
</div>

<script>
const CAT={amp:["Amp","--c-amp"],drive:["Drive","--c-drive"],cab:["Kabin","--c-cab"],mod:["Mod","--c-mod"],delay:["Delay","--c-delay"],rev:["Reverb","--c-rev"],pitch:["Pitch","--c-pitch"],wah:["Wah","--c-wah"],util:["Utility","--c-util"],eq:["EQ","--c-eq"],cap:["Capture","--c-cap"]};
const songs=/*SONGS*/[];
const $=s=>document.querySelector(s);
const confTxt={k:"Kesin",m:"Muhtemelen",t:"Tahmin",x:"Test edildi"};
let cur=songs[0],sel=null,ver="original";
try{if(localStorage.getItem("rigprint-ver")==="community")ver="community"}catch(e){}
const hasComm=()=>!!(cur.community&&cur.community.lanes&&cur.community.lanes.length);
const mode=()=>ver==="community"&&hasComm()?"community":"original";
const lanesOf=()=>cur[mode()].lanes;
function setVer(v){ver=v;try{localStorage.setItem("rigprint-ver",v)}catch(e){}renderSong()}

function knob(p){
  const [l,v,max,unit]=p;
  if(max===null||max===undefined||typeof v==="string")return `<div class="switch"><div class="chip">${v}</div><div class="l">${l}</div></div>`;
  const f=Math.max(0,Math.min(1,v/max)),a0=-135,a=a0+270*f,r=26,cx=32,cy=32,rad=d=>(d-90)*Math.PI/180;
  const pt=d=>[cx+r*Math.cos(rad(d)),cy+r*Math.sin(rad(d))];
  const [x0,y0]=pt(a0),[x1,y1]=pt(a),[xe,ye]=pt(135),large=(a-a0)>180?1:0;
  const ix=cx+16*Math.cos(rad(a)),iy=cy+16*Math.sin(rad(a));
  return `<div class="knob"><svg viewBox="0 0 64 64" aria-hidden="true">
   <path d="M${x0} ${y0} A${r} ${r} 0 1 1 ${xe} ${ye}" fill="none" stroke="#353a41" stroke-width="4" stroke-linecap="round"/>
   ${f>0?`<path d="M${x0} ${y0} A${r} ${r} 0 ${large} 1 ${x1} ${y1}" fill="none" stroke="var(--cat)" stroke-width="4" stroke-linecap="round"/>`:""}
   <circle cx="32" cy="32" r="18" fill="#262a2f" stroke="#4b525b"/>
   <line x1="32" y1="32" x2="${ix}" y2="${iy}" stroke="#e8e6e1" stroke-width="2.5" stroke-linecap="round"/>
  </svg><div class="v">${unit?`${v} ${unit}`:v}</div><div class="l">${l}</div></div>`;
}
function renderSetlist(){
  $("#setlist").innerHTML=songs.map(s=>`<button class="preset" role="tab" aria-selected="${s===cur}" data-id="${s.id}">
    <span class="slot">${s.slot}</span><span class="nm"><span class="song">${s.song}</span><span class="art">${s.artist}</span></span></button>`).join("");
  document.querySelectorAll(".preset").forEach(b=>b.onclick=()=>pick(b.dataset.id));
}
function renderSong(){
  $("#songTitle").textContent=cur.song;
  $("#songMeta").textContent=`${cur.artist} · ${cur.meta}`;
  const opts=hasComm()?[["original","Original"],["community","Community"]]:[["original","Original"]];
  $("#ver").innerHTML=opts.map(([k,t])=>`<button type="button" data-v="${k}" aria-pressed="${mode()===k}">${t}</button>`).join("");
  document.querySelectorAll("#ver button").forEach(b=>b.onclick=()=>setVer(b.dataset.v));
  $("#guitar").innerHTML=(cur.guitar||[]).map(([k,v])=>`<dt>${k}</dt><dd>${v}</dd>`).join("");
  $("#grid").innerHTML=lanesOf().map((ln,li)=>{
    const cells=[];
    for(let i=0;i<8;i++){
      const b=ln.cells[i];
      if(!b){cells.push(`<div class="cell empty"></div>`);continue;}
      const [cn,cv]=CAT[b.c];
      cells.push(`<button class="blk${b.pre?" pre":""}" style="--cat:var(${cv})" data-l="${li}" data-i="${i}" aria-pressed="false" aria-label="${cn}: ${b.d}">
        ${b.stomp?`<span class="stomp" title="Footswitch'e ata"></span>`:""}<span class="cat">${cn}</span><span class="dev">${b.d}</span></button>`);
    }
    return `<div><div class="lane-label">${ln.label}</div><div class="lane"><div class="io">IN</div>${cells.join("")}<div class="io">OUT</div></div></div>`;
  }).join("");
  document.querySelectorAll(".blk").forEach(b=>b.onclick=()=>select(+b.dataset.l,+b.dataset.i));
  const o=cur.orig||[],rows=Array.isArray(o[0])?o:[o];
  $("#origChain").innerHTML=rows.map(r=>`<ul class="chain">${r.map((x,j)=>j===0&&/:$/.test(x)?`<li class="lbl">${x.slice(0,-1)}</li>`:`<li>${x}</li>`).join("")}</ul>`).join("");
  $("#origNote").textContent=cur.origNote||"";
  const sim=cur.similar||[];
  $("#simCard").hidden=!sim.length;
  $("#similar").innerHTML=sim.map(([s,a,w])=>`<li><span class="s">${s}</span><span class="a">${a}</span>${w?`<span class="w">${w}</span>`:""}</li>`).join("");
  const firstAmp=lanesOf()[0].cells.findIndex(c=>c.c==="amp");
  select(0,firstAmp>=0?firstAmp:0);
}
function select(l,i){
  sel=[l,i];
  document.querySelectorAll(".blk").forEach(b=>b.setAttribute("aria-pressed",(+b.dataset.l===l&&+b.dataset.i===i)?"true":"false"));
  const b=lanesOf()[l].cells[i],[cn,cv]=CAT[b.c],ed=$("#editor");
  ed.style.setProperty("--cat",`var(${cv})`);
  ed.innerHTML=`<div class="ed-head"><span class="ed-cat">${cn}</span><h3>${b.d}</h3>${b.pre?`<span class="badge m">amfiden önce</span>`:""}</div>
   ${b.o?`<p class="orig">Orijinal: <strong>${b.o}</strong></p>`:""}
   <div class="badges"><span class="badge ${b.oc}">Ekipman: ${confTxt[b.oc]}</span><span class="badge ${b.sc}">Ayarlar: ${confTxt[b.sc]}</span>${b.tz?`<span class="badge d">Tartışmalı</span>`:""}</div>
   <div class="knobs">${b.p.map(knob).join("")}</div>
   ${b.tz?`<p class="dispute"><b>Tartışmalı:</b> ${b.tz}</p>`:""}
   ${b.n?`<p class="note">${b.n}</p>`:""}
   ${b.g?`<p class="adapt"><b>Senin gitarın:</b> ${b.g}</p>`:""}`;
}
function pick(id){
  cur=songs.find(s=>s.id===id)||songs[0];
  if(location.hash.slice(1)!==cur.id){try{history.replaceState(null,"","#"+cur.id)}catch(e){location.hash=cur.id}}
  renderSetlist();renderSong();
}
function boot(){
  let id=location.hash.slice(1);
  pick(songs.some(s=>s.id===id)?id:songs[songs.length-1].id);
}
window.addEventListener("hashchange",()=>{const id=location.hash.slice(1);if(id!==cur.id&&songs.some(s=>s.id===id))pick(id)});
document.addEventListener("keydown",e=>{
  if(!sel||!["ArrowLeft","ArrowRight"].includes(e.key)||!e.target.closest(".grid"))return;
  const row=lanesOf()[sel[0]].cells;const i=sel[1]+(e.key==="ArrowRight"?1:-1);
  if(i>=0&&i<row.length){select(sel[0],i);document.querySelector(`.blk[data-l="${sel[0]}"][data-i="${i}"]`)?.focus()}
});
boot();
</script>
```
