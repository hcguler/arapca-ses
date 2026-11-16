# arapca-ses

[Ayet Ayet Arapça](https://hcguler.github.io/apps/arapca/) uygulamasının Türkçe sesli anlatım kayıtları.
Yayın adresi: `https://hcguler.github.io/arapca-ses/` (uygulama kayıtları buradan çalar).

- Bu depoda yalnızca üretilmiş dosyalar vardır: `yetiskin/kayitlar.json`, `yetiskin/giris.mp3`,
  `yetiskin/c01/s000.mp3 …` (cüz başına klasör, sayfa başına bir kayıt). Elle düzenlenmez.
- Anlatım metni ve üretici betikler ana depodadır:
  [hcguler/hcguler.github.io](https://github.com/hcguler/hcguler.github.io) →
  `tools/arapca-anlatim.mjs` (metin), `tools/tts/seslendir.py` (ses).
- Ses yalnızca bir bilgisayarda, yerel bir modelle üretilir (Antalia-2 Mini, erkek sesi); bulut TTS
  kullanılmaz. Mono MP3, 24 kHz, 24 kbps, −18 LUFS.
- Arapça kelimeler anlatımda okunmaz; Arapçanın sesi uygulamada kâri kaydından (Suûd eş-Şüreym) gelir.
- Ayrı depo, ana sitenin GitHub Pages boyut sınırını (1 GB) korumak için açılmıştır
  (bkz. ana depoda `docs/planlar/ayet-ayet-arapca.md`).
