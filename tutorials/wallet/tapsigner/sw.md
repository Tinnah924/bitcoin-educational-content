---
name: Tapsigner
description: Kuweka na kutumia Tapsigner na Nunchuk
---
![cover](assets/cover.webp)

Hardware wallet ni kifaa cha kielektroniki kinachotumika kusimamia na kulinda private keys za Bitcoin wallet. Tofauti na software wallets (au hot wallets) ambazo huwekwa kwenye kompyuta za matumizi ya kawaida zinazojiunganisha na mtandao, hardware wallet inaruhusu private keys kutengwa kabisa, na hivyo kupunguza hatari za wizi au udukuzi.

Lengo kuu la hardware wallet ni kupunguza kazi za kifaa ili kupunguza sehemu ambazo mshambuliaji anaweza kutumia. Kifaa chenye kazi chache kinakuwa na maeneo machache yanayoweza kushambuliwa, yaani, uwezekano mdogo wa udhaifu unaoweza kuruhusu mshambuliaji kupata bitcoins.

Inashauriwa kutumia hardware wallet kulinda bitcoins zako, hasa kama unashikilia kiasi kikubwa, iwe ni thamani kamili au sehemu kubwa ya mali zako zote.

Hardware wallet hutumika pamoja na software ya kusimamia wallet kwenye kompyuta au simu. Software hii inasimamia utengenezaji wa muamala, lakini saini ya cryptographic inayohitajika kuthibitisha muamala huo inafanyika tu ndani ya hardware wallet. Hii inamaanisha private keys hazijawahi kufichuliwa kwenye mazingira ambayo yanaweza kuwa na udhaifu.

Hardware wallet inampa mtumiaji ulinzi mara mbili: kwanza, inalinda bitcoins zako dhidi ya mashambulizi ya mbali kwa kuweka private keys nje ya mtandao, na pili, kwa kawaida zinatoa ulinzi bora zaidi dhidi ya kujaribu kutoa keys kimwili. Vigezo hivi viwili vya usalama ndivyo vinavyotumika kupima na kulinganisha aina mbalimbali za hardware wallet zilizopo sokoni.

Katika mafunzo haya, nitakuonyesha moja ya suluhu hizi: Tapsigner kutoka Coinkite.

## Utangulizi wa Tapsigner

Tapsigner ni hardware wallet iliyoundwa katika umbo la kadi ya NFC na kampuni ya Coinkite, pia maarufu kwa kutengeneza Coldcard.

![TAPSIGNER NUNCHUK](assets/notext/01.webp)

Tapsigner inahifadhi jozi ya master private key na chain code kulingana na BIP32, ili kutoa mti wa cryptographic keys. Keys hizi zinaweza kutumika kusaini miamala kwa kugusisha Tapsigner kwenye simu au msomaji wa kadi ya NFC.
Kadi hii ya NFC inauzwa kwa $19.99, bei nafuu sana ukilinganisha na hardware wallet zingine sokoni. Hata hivyo, kutokana na muundo wake, Tapsigner haina chaguo nyingi kama vifaa vingine. Haina betri, kamera wala sehemu ya micro SD, kwani ni kadi tu. Kwa maoni yangu, upungufu wake mkubwa ni kutokuwa na skrini kwenye hardware wallet, jambo linaloweza kuongeza udhaifu kwa mashambulizi ya mbali. Hii inamlazimisha mtumiaji kusaini bila kuona, akitegemea kile anachoona kwenye skrini ya kompyuta yake.

Licha ya mapungufu yake, Tapsigner inaweza kuvutia kutokana na bei yake ndogo. Wallet hii inaweza kutumika kuongeza usalama kwenye spending wallet sambamba na savings wallet iliyolindwa na hardware wallet yenye skrini. Pia ni suluhu nzuri kwa wanaoshikilia kiasi kidogo cha bitcoins na hawataki kutumia fedha nyingi kununua kifaa cha gharama zaidi. Zaidi ya hayo, matumizi ya Tapsigner kwenye multisig, au kwenye wallet za timelock siku zijazo, inaweza kuwa na manufaa.

## Jinsi ya kununua Tapsigner?

Tapsigner inapatikana [kwenye tovuti rasmi ya Coinkite](https://store.coinkite.com/store/category/tapsigner). Ukiihitaji dukani, unaweza kupata [orodha ya wauzaji rasmi](https://coinkite.com/resellers) kwenye tovuti.

Utahitaji pia simu yenye NFC, au kifaa cha USB cha kusoma kadi za NFC katika frequency ya 13.56 MHz.

## Jinsi ya kuanzisha Tapsigner na Nunchuk?

Ukishapokea Tapsigner yako, hatua ya kwanza ni kukagua kifurushi kuona kama hakijafunguliwa. Ikiwa kifurushi kimeharibika, huenda kimeingiliwa na huenda kadi si halisi. CoinKite itatuma Tapsigner yako ikiwa na kasha linalozuia mawimbi ya redio. Hakikisha upo kwenye kifurushi chako.

![TAPSIGNER NUNCHUK](assets/notext/02.webp)

Ili kusimamia wallet, tutatumia **Nunchuk Wallet** kwenye simu. Hakikisha simu yako ina NFC, kisha pakua Nunchuk kupitia [Google Play Store](https://play.google.com/store/apps/details?id=io.nunchuk.android), [App Store](https://apps.apple.com/us/app/nunchuk-bitcoin-wallet/id1563190073) au moja kwa moja kwa [.apk file](https://github.com/nunchuk-io/nunchuk-android/releases).

![TAPSIGNER NUNCHUK](assets/notext/03.webp)

Kama unatumia Nunchuk kwa mara ya kwanza, app itakuomba kuunda akaunti. Kwa mafunzo haya, si lazima kuunda akaunti. Chagua "*Continue as guest*" ili uendelee bila akaunti.

![TAPSIGNER NUNCHUK](assets/notext/04.webp)

Kisha bonyeza "*Unassisted wallet*".

![TAPSIGNER NUNCHUK](assets/notext/05.webp)

Kisha bonyeza "*I'll explore on my own*".

![TAPSIGNER NUNCHUK](assets/notext/06.webp)

Ukiwa ndani ya Nunchuk, bonyeza kitufe cha "*+*" karibu na tab ya "*Keys*".

![TAPSIGNER NUNCHUK](assets/notext/07.webp)

Chagua "*Add NFC key*".

![TAPSIGNER NUNCHUK](assets/notext/08.webp)

Halafu chagua "*Add TAPSIGNER*".

![TAPSIGNER NUNCHUK](assets/notext/09.webp)

Bonyeza "*Continue*" kisha weka Tapsigner yako kwenye simu.

![TAPSIGNER NUNCHUK](assets/notext/10.webp)

Kama Tapsigner yako ni mpya, Nunchuk itakupa chaguo la kuiweka tayari. Bonyeza "*Yes*".

![TAPSIGNER NUNCHUK](assets/notext/11.webp)

Sasa utatakiwa kuchagua namna ya kutengeneza master chain code.

Tapsigner hutumia BIP32. Hii ina maana utengenezaji wa cryptographic keys unaolinda bitcoins zako hautumii mnemonic phrase kama BIP39 wallets, bali moja kwa moja master private key na master chain code. Vipengele hivi viwili hupitishwa kwenye HMAC ili kutoa keys nyingine kwa mpangilio wa hierarchical.

Master private key inatengenezwa moja kwa moja na TRNG (*True Random Number Generator*) ndani ya Tapsigner yako. Master chain code, upande mwingine, lazima itolewe kutoka nje. Hapa unaweza kuchagua: acha Nunchuk itengeneze yenyewe kwa kubonyeza "*Automatic*", au tengeneza mwenyewe kwa kuchagua "*Advanced*" na kuiandika kwenye sehemu husika.

![TAPSIGNER NUNCHUK](assets/notext/12.webp)

Kisha, chagua PIN code. Eneo la "*Starting PIN*" andika PIN iliyo nyuma ya Tapsigner yako.

![TAPSIGNER NUNCHUK](assets/notext/13.webp)

Chagua PIN code ya kulinda upatikanaji wa Tapsigner yako. PIN hii haina nafasi kwenye urejeshaji wa wallet. Kazi yake ni kufungua Tapsigner yako ili kusaini miamala. Hakikisha umehifadhi PIN hii ili usiisahau. Bonyeza "*Continue*" uendelee.

![TAPSIGNER NUNCHUK](assets/notext/14.webp)
Weka Tapsigner nyuma ya simu yako ili kuiweka tayari.

![TAPSIGNER NUNCHUK](assets/notext/15.webp)

Nunchuk itatengeneza recovery file ya wallet yako, ambayo hukuwezesha kurudisha bitcoins zako endapo utapoteza kadi ya NFC. File hili limefichwa kwa backup code iliyoandikwa nyuma ya Tapsigner. Ili kurudisha bitcoins zako, utahitaji file hili na code ya kufungua. Ni muhimu kufanya nakala ya code hii kwa karatasi, kwani ukipoteza kadi, hutapata tena code hii kwani ipo kwenye kadi tu. Hakikisha pia umehifadhi backup kadhaa za recovery file yako.

![TAPSIGNER NUNCHUK](assets/notext/16.webp)

Chagua jina la wallet yako.

![TAPSIGNER NUNCHUK](assets/notext/17.webp)

Wallet yako sasa imeanzishwa. Ili kuthibitisha uhalisia wa Tapsigner yako, unaweza wakati wowote kubonyeza kitufe cha "*Run health check*".

![TAPSIGNER NUNCHUK](assets/notext/18.webp)

Ingiza PIN yako.

![TAPSIGNER NUNCHUK](assets/notext/19.webp)

Weka kadi yako nyuma ya simu tena.

![TAPSIGNER NUNCHUK](assets/notext/20.webp)

## Jinsi ya kuunda wallet kwenye Tapsigner?

Rudi kwenye ukurasa wa mwanzo wa Nunchuk, utaona Tapsigner yako iko kwenye orodha ya vifaa vya kusaini.

![TAPSIGNER NUNCHUK](assets/notext/21.webp)

Sasa utatakiwa kutengeneza keys za Bitcoin wallet yako. Kufanya hivyo, bonyeza kitufe cha "*+*" upande wa kulia wa tab ya "*Wallets*".

![TAPSIGNER NUNCHUK](assets/notext/22.webp)

Bonyeza "*Create new wallet*".

![TAPSIGNER NUNCHUK](assets/notext/23.webp)

Chagua "*Create a new wallet using existing keys*".

![TAPSIGNER NUNCHUK](assets/notext/24.webp)

Chagua jina la wallet yako na bonyeza "*Continue*".

![TAPSIGNER NUNCHUK](assets/notext/25.webp)

Chagua Tapsigner yako kama kifaa cha kusaini, kisha bonyeza "*Continue*".

![TAPSIGNER NUNCHUK](assets/notext/26.webp)

Ukiridhika na kila kitu, thibitisha utengenezaji.

![TAPSIGNER NUNCHUK](assets/notext/27.webp)

Unaweza kuhifadhi configuration file ya wallet yako. File hili lina public keys tu, hivyo hata mtu akilipata hawezi kuiba bitcoins zako. Lakini anaweza kufuatilia miamala yako yote. File hili ni hatari tu kwa faragha yako. Wakati mwingine, ni muhimu kwa ajili ya kurudisha wallet yako.

![TAPSIGNER NUNCHUK](assets/notext/28.webp)

Wallet yako imeundwa kikamilifu!

![TAPSIGNER NUNCHUK](assets/notext/29.webp)

Usipotumia Tapsigner yako, hakikisha umeihifadhi kwenye kasha la Coinkite linalozuia mawimbi ili kulinda dhidi ya usomaji bila ruhusa.

## Jinsi ya kupokea bitcoins kwenye Tapsigner?

Kupokea bitcoins, bonyeza wallet yako.

![TAPSIGNER NUNCHUK](assets/notext/30.webp)

Kisha tumia address iliyotolewa kupokea bitcoins. Kama umewahi kupokea bitcoins kabla kwenye wallet hii, utatakiwa kubonyeza kitufe cha "*Receive*" ili kutoa address mpya ya kupokea.

![TAPSIGNER NUNCHUK](assets/notext/31.webp)

Muamala wa mtumaji ukishatolewa, utaonekana kwenye wallet yako.

![TAPSIGNER NUNCHUK](assets/notext/32.webp)

Bonyeza "*View coins*".

![TAPSIGNER NUNCHUK](assets/notext/33.webp)

Chagua UTXO mpya.

![TAPSIGNER NUNCHUK](assets/notext/34.webp)

Bonyeza "*+*" karibu na "*Tags*" kuongeza lebo kwenye UTXO yako. Ni utaratibu mzuri kwani inakusaidia kukumbuka asili ya coins zako na kuboresha faragha unapofanya matumizi.

![TAPSIGNER NUNCHUK](assets/notext/35.webp)

Chagua tag iliyopo au tengeneza mpya, kisha bonyeza "*Save*". Unaweza pia tengeneza "*collections*" kupanga coins zako vizuri zaidi.

![TAPSIGNER NUNCHUK](assets/notext/36.webp)

## Jinsi ya kutuma bitcoins na Tapsigner?

Baada ya kuwa na bitcoins kwenye wallet yako, unaweza pia kuzituma. Bonyeza wallet unayotaka kutumia.

![TAPSIGNER NUNCHUK](assets/notext/37.webp)

Bonyeza kitufe cha "*Send*".

![TAPSIGNER NUNCHUK](assets/notext/38.webp)

Chagua kiasi cha kutuma, kisha bonyeza "*Continue*".

![TAPSIGNER NUNCHUK](assets/notext/39.webp)

Ongeza "*note*" kwenye muamala wako ili kukumbuka madhumuni yake.

![TAPSIGNER NUNCHUK](assets/notext/40.webp)

Kisha, ingiza address ya mpokeaji kwenye sehemu husika.

![TAPSIGNER NUNCHUK](assets/notext/41.webp)

Unaweza pia kuskani address yenye QR code kwa kubonyeza icon iliyo juu kulia ya skrini.

![TAPSIGNER NUNCHUK](assets/notext/42.webp)

Bonyeza kitufe cha "*Create Transaction*".

![TAPSIGNER NUNCHUK](assets/notext/43.webp)

Kagua taarifa za muamala wako, kisha bonyeza kitufe cha "*Sign*" karibu na Tapsigner yako.

![TAPSIGNER NUNCHUK](assets/notext/44.webp)

Ingiza PIN yako ili kufungua.

![TAPSIGNER NUNCHUK](assets/notext/45.webp)

Weka Tapsigner nyuma ya simu.

![TAPSIGNER NUNCHUK](assets/notext/46.webp)

Muamala wako sasa umesainiwa. Hakikisha kila kitu kiko sawa, kisha bonyeza "*Broadcast Transaction*" kuituma kwenye mtandao wa Bitcoin.

![TAPSIGNER NUNCHUK](assets/notext/47.webp)

Muamala wako unasubiri uthibitisho.

![TAPSIGNER NUNCHUK](assets/notext/48.webp)

## Jinsi ya kurejesha wallet ukiipoteza Tapsigner?

Ukipoteza Tapsigner yako, unaweza kurudisha wallet ukitumia code iliyoandikwa nyuma ya kadi. Ni muhimu kuihifadhi code hii mbali na Tapsigner yako, kwa sababu ukipoteza kadi, utapoteza pia code hiyo. Utahitaji pia backup iliyofichwa ya wallet.

Kwa urejeshaji, tutatumia Nunchuk, lakini kumbuka utakuwa unaweka fedha zako kwenye hot wallet kwa muda. Kama Tapsigner yako ilikuwa inalinda kiasi kikubwa, fikiria kutumia Coldcard mpya kufanya urejeshaji huo huo.

Fungua Nunchuk na bonyeza kitufe cha "*+*" karibu na tab ya "*Keys*".

![TAPSIGNER NUNCHUK](assets/notext/49.webp)

Chagua "*Add NFC key*".

![TAPSIGNER NUNCHUK](assets/notext/50.webp)

Chagua "*Recover TAPSIGNER key from backup*".

![TAPSIGNER NUNCHUK](assets/notext/51.webp)

Utaelekezwa kwenye file explorer ya kifaa chako. Tafuta na chagua file ya backup iliyofichwa ya wallet yako. Kwa kawaida jina la file linaanza na `backup...`.

![TAPSIGNER NUNCHUK](assets/notext/52.webp)

Ingiza nenosiri la kufungua backup file. Nenosiri hili ni lile uliandika nyuma ya Tapsigner yako.

![TAPSIGNER NUNCHUK](assets/notext/53.webp)

Chagua jina la wallet yako mpya ya kurejesha.

![TAPSIGNER NUNCHUK](assets/notext/54.webp)

Umerudisha bitcoins zako. Wallet yako sasa inasimamiwa kama hot wallet inayoonekana kwenye tab ya "*Keys*" ndani ya Nunchuk. Sasa utatakiwa kutengeneza set mpya ya cryptographic keys kwenye sehemu ya "*Wallets*" kwa kuunganisha key hii. Fuata hatua kama kwenye sehemu ya "*Jinsi ya kuunda wallet kwenye Tapsigner?*".

![TAPSIGNER NUNCHUK](assets/notext/55.webp)

Ukishapoteza Tapsigner yako, nakushauri mara moja uhamishe bitcoins zako kwenye wallet nyingine unayomiliki, bora zaidi ikiwa inalindwa na hardware wallet. Kweli, Tapsigner uliyoipoteza inaweza kuwa mikononi mwa mtu asiyeaminika. Ni muhimu kufuta wallet uliyoirejesha na kuacha kuitumia.

Hongera, sasa umejifunza kutumia Tapsigner! Kama umefaidika na mafunzo haya, tafadhali tupatie alama ya kidole gumba hapa chini. Usisite kushiriki makala hii kwenye mitandao yako ya kijamii. Asante sana!
