# Baqti Nasiib — Qaybta Fadhiga

Web-app hal fayl ah oo si caddaalad ah u qaybisa **fadhiga maalinta ciyaarta**.
Kooxdu waa 16 ciyaartoy, 10 ayaa ciyaaraya, 6-na way fadhiyaan — kuwaas oo lagu
doorto baqti nasiib toos ah oo muuqaal qurux badan leh.

*A single-file web app that fairly picks which 6 of a 16-player squad sit out on
matchday, through a live lottery draw. UI language: Somali.*

## Sida loo isticmaalo

1. Fur `index.html` browser-ka (ama ka hoos maree server maxalli ah).
2. **Tallaabo 1** — Ma jiraan ciyaartoy iskood u fadhiista? Haddii haa, dooro.
3. **Tallaabo 1c** — Ma jiraan ciyaartoy baqtigii hore ku dhacay? Kuwaas waa la
   ilaalinayaa: si toos ah ayay u galayaan 10-ka ciyaaraya, qorshahana kama mid aha.
4. **Tallaabo 2** — Riix *Bilow Baqti Nasiibka*. Magacyada hal slot ayaa la muujiyaa.
5. **Tallaabo 3** — Natiijada la wadaagi karo, iyo badhanka *Soo deji PDF*.

## Xeerarka caddaaladda

- **Hal baqti nasiib maalintii.** Marka la sameeyo, waa la xiray — cusboonaysiintu
  natiijada ma beddesho (`localStorage`).
- Natiijada waa la xisaabiyaa waana la keydiyaa isla markii la bilaabo;
  muuqaalku waa **muujin uun**, badhanka *Dhaqso*-na waxba kama beddelo.
- Kuwa **iskood** u fadhiistay ilaalin ma helayaan — sida caadiga ah ayay qorshaha ugu jiraan.
- Dib u dejin waxay u baahan tahay in la qoro `TIRTIR` — khaladaad dhab ah oo keliya.

## Farsamada

Hal fayl: `index.html`. Ma jiro server, ma jiro database, ma jiro isku-xirnaan
qalabyo kale. Tailwind CSS iyo jsPDF ayaa CDN laga soo qaadaa, sidaas darteed
internet ayaa loo baahan yahay markii ugu horreysay.

> **Fiiro gaar ah:** haddii faylka si toos ah loo furo (`file://`), browser-ku
> wuxuu xannibi karaa `localStorage` — taasoo ka dhigan in xiritaanka maalinlaha
> ahi uusan shaqayn. App-ku digniin ayuu muujiyaa haddii ay taasi dhacdo; si loo
> hubiyo, ka fur server maxalli ah ama internet.
