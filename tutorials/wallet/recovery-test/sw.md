---
name: Recovery test 
description: Jinsi ya kujaribu nakala zako ili kuhakikisha kuwa haupotezi bitcoins zako?
---
![cover](assets/cover.webp)


Wakati wa kuunda Bitcoin Wallet, unaombwa kuandika maneno ya mnemonic, ambayo kwa kawaida huwa 12 au 24. Maneno haya hukuruhusu kurejesha ufikiaji wa bitcoins zako endapo kifaa chako kitapotea, kuharibika au kuibiwa.

Kabla ya kuanza kutumia Bitcoin Wallet yako mpya, ni muhimu sana kuthibitisha uhalali wa maneno haya ya mnemonic. Njia salama na bora ya kufanya hivyo ni kwa kufanya dry recovery test.

Jaribio hili linahusisha kuiga urejeshaji wa Wallet kabla ya kuweka bitcoins zozote ndani yake. Mradi Wallet bado haina chochote, tunaigiza hali ambapo kifaa kinachohifadhi funguo zetu kinapotea, na kilichosalia ni maneno yetu ya mnemonic ili kujaribu kurejesha bitcoins zetu.


![RECOVERY TEST](assets/notext/01.webp)


## Kusudi ni nini?

Mchakato huu wa majaribio hukuruhusu kuthibitisha kuwa nakala rudufu ya maneno yako ya mnemonic—iwe imehifadhiwa kwenye karatasi au chuma—inafanya kazi ipasavyo. Kutofaulu katika jaribio hili la urejeshaji (recovery test) kunaashiria hitilafu katika uhifadhi wa maneno, na hivyo kuweka bitcoins zako hatarini.
Kwa upande mwingine, iwapo recovery test itafanikiwa, inathibitisha kuwa maneno yako ya mnemonic yanatumika vizuri, na unaweza kuendelea kupokea bitcoins kwenye Wallet hii ukiwa na amani ya akili.


Kufanya mtihani wa urejeshaji wa kavu (dry recovery test) kuna faida mbili. Sio tu kwamba hukuwezesha kuangalia usahihi wa maneno yako ya mnemonic, bali pia hukupa fursa ya kujitambulisha na mchakato wa kurejesha Wallet. Kwa njia hii, utagundua matatizo yanayoweza kutokea kabla hali halisi haijatokea kwako.
Siku ambayo utahitaji kurejesha Wallet yako, utakuwa na mkazo mdogo, kwani tayari utakuwa unaujua mchakato, hivyo kupunguza hatari ya makosa. Ndiyo maana ni muhimu kutopuuza hatua hii ya kupima, na kuchukua muda unaohitajika kuifanya kwa usahihi.


## Recovery test ni nini?


Mchakato wa mtihani ni rahisi sana:


- Baada ya kuunda Bitcoin Wallet yako mpya, na kabla ya kuweka satoshi yako ya kwanza, andika maelezo ya ushahidi kama vile xpub, anwani ya kwanza ya kupokea, au hata alama ya kidole ya ufunguo mkuu;
- Kisha, futa kwa makusudi Wallet tupu, kwa mfano kwa kuweka upya Hardware Wallet yako kwenye mipangilio ya kiwanda;
- Halafu, iga urejeshaji wa Wallet yako kwa kutumia tu nakala za karatasi za maneno yako ya mnemonic na passphrase yako ikiwa unatumia moja;
- Hatimaye, angalia ikiwa maelezo ya ushahidi yanalingana na yale ya Wallet iliyorejeshwa. Ikiwa maelezo yanalingana, unaweza kuwa na uhakika wa kuaminika kwa hifadhi yako ya kimwili, na kisha unaweza kutuma bitcoins zako za kwanza kwa Wallet hii.


Kuwa mwangalifu, wakati wa jaribio la urejeshi, **ni lazima utumie kifaa kilekile kilichokusudiwa kwa Wallet** yako ya mwisho, ili usiongeze sehemu ya mashambulizi ya Wallet yako. Kwa mfano, ukiunda Wallet kwenye Trezor Safe 5, hakikisha kuwa umefanya jaribio la urejeshi kwenye Trezor Safe 5 hiyohiyo. 

Ni muhimu usiweke kifungu chako cha urejeshi kwenye programu nyingine yoyote, kwa kuwa hii inaweza kuhatarisha usalama unaotolewa na Hardware Wallet yako, hata kama Wallet bado haina kitu.


## Jinsi ya kufanya mtihani wa kurejesha?


Katika somo hili, nitaelezea jinsi ya kufanya mtihani wa kurejesha (recovery test) kwenye Bitcoin Software Wallet, kwa kutumia Sparrow Wallet (kwa Hot Wallet). Hata hivyo, mchakato unabakia sawa kwa aina nyingine yoyote ya kifaa. Tena, **ikiwa unatumia Hardware Wallet, usifanye mtihani wa kurejesha kwenye Sparrow Wallet** (angalia sehemu iliyotangulia).

Nimeunda hivi punde mpya Hot Wallet kwenye Sparrow Wallet. Kwa sasa, bado sijatuma bitcoins yoyote kwake. Ni tupu.


![RECOVERY TEST](assets/notext/02.webp)

Nimezingatia kwa uangalifu kifungu changu cha maneno 12 cha Mnemonic kwenye kipande cha karatasi. Na kwa kuwa ninataka kuimarisha usalama wa Wallet hii, pia nimeweka BIP39 passphrase ambayo nimehifadhi kwenye kipande kingine cha karatasi:


```txt
1. shield
2. brass
3. sentence
4. cube
5. marble
6. glad
7. satoshi
8. door
9. project
10. panic
11. prepare
12. general
```

```text
Passphrase: YfaicGzXH9t5C#g&47Kzbc$JL
```

***Ni wazi, hupaswi kamwe kushiriki maneno yako ya Mnemonic na passphrase yako kwenye mtandao, tofauti na ninachofanya katika mafunzo haya. Mfano huu wa Wallet hautatumika na utafutwa mwishoni mwa mafunzo.***


Sasa nitaandika kwenye rasimu kipande cha ushahidi kutoka kwenye Wallet yangu. Unaweza kuchagua vipande tofauti vya maelezo, kama vile anwani ya kwanza ya kupokea, xpub, au alama ya kidole ya ufunguo mkuu (fingerprint). Kibinafsi, ninapendekeza kuanza kwa kuchagua anwani ya kwanza ya kupokea. Hii hukuruhusu kuthibitisha kuwa unaweza kufuatilia njia kamili ya kwanza ya utokaji (derivation path) inayoongoza kwenye anwani hiyo.


Kwenye Sparrow, bofya kichupo cha "*Anwani*".


![RECOVERY TEST](assets/notext/03.webp)


Kisha, andika kwenye karatasi mara ya kwanza kupokea Address ya Wallet yako. kwa mfano wangu, Address ni:


```txt
tb1qxv56mma5x5r7uhdkn0ldvcx6m0gj6f3kre0gwd
```

Baada ya kutambua habari, nenda kwenye menyu ya "Faili", kisha chagua "Futa Wallet". Ninakukumbusha tena kwamba Bitcoin Wallet yako lazima iwe tupu kabla ya kuendelea na hatua hii.


![RECOVERY TEST](assets/notext/04.webp)


Ikiwa Wallet yako ni tupu, thibitisha kufutwa kwa Wallet yako.


![RECOVERY TEST](assets/notext/05.webp)


Sasa unahitaji kurudia mchakato wa uundaji wa Wallet, lakini kwa kutumia nakala zetu za karatasi. Bofya kwenye menyu ya "*Faili*" kisha kwenye "*Mpya Wallet*".


![RECOVERY TEST](assets/notext/06.webp)


Weka jina la Wallet yako tena.


![RECOVERY TEST](assets/notext/07.webp)


Katika menyu ya "*Aina ya Hati*", unahitaji kuchagua aina ya hati sawa na Wallet uliyofuta hapo awali.


![RECOVERY TEST](assets/notext/08.webp)


Kisha bofya kitufe cha "Unda au Ingiza Software Wallet Mpya".


![RECOVERY TEST](assets/notext/09.webp)


Chagua nambari sahihi ya maneno kwa seed yako.


![RECOVERY TEST](assets/notext/10.webp)


Weka maneno yako ya Mnemonic kwenye programu. Ikiwa ujumbe wa "Cheki Batili" utaonekana, hii inaashiria kuwa hifadhi rudufu ya maneno hayo si sahihi. Hivyo, itakubidi uanze upya mchakato wa kuunda Wallet yako, kwa kuwa jaribio la urejeshaji halikufaulu.


![RECOVERY TEST](assets/notext/11.webp)


Ikiwa unayo passphrase, kama ilivyo kwangu, weka pia.


![RECOVERY TEST](assets/notext/12.webp)


Bofya kwenye "*Unda Duka la Vitufe*", kisha kwenye "*Ingiza Duka la Vitufe*".


![RECOVERY TEST](assets/notext/13.webp)


Na hatimaye, bofya kitufe cha "* Tumia *".


![RECOVERY TEST](assets/notext/14.webp)


Sasa unaweza kurudi kwenye kichupo cha "*Anwani*".


![RECOVERY TEST](assets/notext/15.webp)


Hatimaye, thibitisha kwamba address ya kwanza ya kupokea inalingana na ile uliyoibainisha kama ushahidi kwenye rasimu yako.


![RECOVERY TEST](assets/notext/16.webp)


Ikiwa address za kupokea zinalingana, jaribio lako la urejeshi limefaulu na unaweza kutumia Bitcoin Wallet yako mpya. Ikiwa hazilingani, hii inaweza kuonyesha ama hitilafu katika uchaguzi wa aina ya hati, ambayo husababisha njia ya utokaji kuwa isiyo sahihi, au tatizo katika kuhifadhi nakala ya maneno yako ya Mnemonic au passphrase yako. Katika hali zote mbili, ninapendekeza sana kuanza upya na kuunda Bitcoin Wallet mpya ili kuepuka hatari yoyote. Wakati huu, jihadharini kukumbuka kifungu cha Mnemonic bila makosa.


Hongera, sasa uko tayari kufanya mtihani wa urejeshaji na kuthibitisha kuwa unaweza kufikia Bitcoin zako kikamilifu! Ninapendekeza ujaribu mchakato huu kila unapounda Wallet mpya ya Bitcoin. Ikiwa mafunzo haya yamekuwa ya manufaa kwako, ningeshukuru ukiacha dole gumba hapa chini. Jisikie huru kushiriki nakala hii kwenye mitandao yako ya kijamii. Asante sana!
