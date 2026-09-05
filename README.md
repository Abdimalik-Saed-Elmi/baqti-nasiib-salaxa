# Baqti Nasiib — Qaybta Fadhiga

Web-app hal fayl ah oo si caddaalad ah u qaybisa **fadhiga maalinta ciyaarta**.
16-ka ciyaartoy waxaa loo qaybiyaa **laba koox oo 8 ah**, koox kastaana waxay
leedahay **baqti nasiib u gaar ah**: 3 way fadhiyaan, 5-na way ciyaarayaan.

*A single-file web app that fairly picks who sits out on matchday. The 16-player
squad is split into two teams of 8; each team runs its own independent lottery
(3 sit, 5 play). UI language: Somali.*

**Tooska ah:** https://abdimalik-saed-elmi.github.io/baqti-nasiib-salaxa/

## Sida loo isticmaalo

1. **Tallaabo 1 — Kooxaha.** Qaybi 16-ka ciyaartoy Koox A iyo Koox B (8 + 8).
   Qaybintu way keydsan tahay; markii dambe waxaad ka beddeli kartaa *Maamul →
   Beddel kooxaha*.
2. **Tallaabo 2 — Kuwa iskood u fadhiistay.** Koox kasta si gaar ah u jawaab.
   Kuwa iskood u fadhiista waa laga jaraa 3-da fadhiga ee kooxdooda.
3. **Tallaabo 3 — Jimcadi hore.** Kuwa baqtigii hore ku dhacay (*jimcadi hore
   fadhiye*): si toos ah ayay u galayaan 5-ta ciyaaraya, qorshahana kama mid aha.
4. **Tallaabo 4 — Xafladda.** Riix *Bilow Baqti Nasiibka*. Koox A ayaa horeeya,
   kadibna Koox B — hal magac mar.
5. **Natiijada** — kaarka la wadaagi karo iyo badhanka *Soo deji PDF*.

## Lambarrada soo-gelitaanka

Koox kasta, kuwa **baqtiga ku dhacay** waxay helayaan lambar (1, 2, 3) sida
tartiibkii loo saaray:

> Haddii ciyaartoy ciyaaraya uu iskiis u fadhiisto, lambarka 1aad ayaa beddelaya
> — baqti cusub looma baahna.

Kuwa **iskood** u fadhiistay lambar ma helayaan (way doorteen inay fadhiistaan,
safka soo-gelitaanka kuma jiraan).

## Xeerarka caddaaladda

- **Hal baqti nasiib maalintii.** Marka la sameeyo, waa la xiray — cusboonaysiintu
  natiijada ma beddesho (`localStorage`).
- Natiijada labada koox waa la xisaabiyaa waana la keydiyaa isla markii la bilaabo;
  muuqaalku waa **muujin uun**, badhanka *Dhaqso*-na waxba kama beddelo.
- Beddelidda kooxuhu **ma furto** baqti nasiibka maanta.
- Dib u dejin waxay u baahan tahay in la qoro `TIRTIR` — khaladaad dhab ah oo
  keliya. Dib u dejintu kooxaha ma tirtirto.
- Hubinta koox kasta: haddii qorshuhu ka yar yahay inta la saarayo, baqtigaas waa
  la joojiyaa oo digniin cad ayaa la muujiyaa.

## Farsamada

Hal fayl: `index.html`. Ma jiro server, ma jiro database. Tailwind CSS iyo jsPDF
ayaa CDN laga soo qaadaa, sidaas darteed internet ayaa loo baahan yahay.

> **Fiiro gaar ah:** haddii faylka si toos ah loo furo (`file://`), browser-ku
> wuxuu xannibi karaa `localStorage` — taasoo ka dhigan in xiritaanka maalinlaha
> ahi uusan shaqayn. Isticmaal linkiga tooska ah ee kor ku xusan.
