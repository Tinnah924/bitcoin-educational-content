---
name: Payjoin - Sparrow Wallet
description: Jinsi ya kufanya muamala wa Payjoin kwenye Sparrow Wallet?
---

![picha ya kifuniko cha kozi ya Payjoin kwenye Sparrow Wallet](assets/cover.webp)

_**ONYO:** Kufuatia kukamatwa kwa waanzilishi wa Samourai Wallet na kukamatwa kwa seva zao tarehe 24 Aprili, Payjoins Stowaway kwenye Samourai Wallet sasa hufanya kazi tu kwa kubadilishana PSBT kwa mikono kati ya pande zinazohusika, mradi watumiaji wote wawili wakiwa wameunganishwa kwenye Dojo zao. Kuhusu Sparrow, Payjoins kupitia BIP78 bado zinafanya kazi. Hata hivyo, zana hizi zinaweza kuzinduliwa tena katika wiki zijazo. Wakati huo, unaweza kila mara kusoma makala hii kuelewa utendakazi wa kinadharia wa Payjoins._

_Tunafuatilia kwa karibu maendeleo ya kesi hii pamoja na maendeleo yanayohusiana na zana hizi. Uhakikishe tutasasisha mafunzo haya kadiri taarifa mpya zitakavyopatikana._  

_Mafunzo haya yametolewa kwa madhumuni ya kielimu na taarifa tu. Hatuzapendekezi wala kuhamasisha matumizi ya zana hizi kwa madhumuni ya uhalifu. Ni jukumu la kila mtumiaji kutii sheria katika mamlaka yao._  

---

> *Lazimisha wachambuzi wa blockchain kufikiria upya kila kitu wanachodhani wanakijua.*  

Payjoin ni muundo maalum wa muamala wa Bitcoin unaoongeza faragha ya mtumiaji wakati wa matumizi kwa kushirikiana na mpokeaji malipo. Kuna utekelezaji kadhaa unaorahisisha usanidi na automatisation ya Payjoin. Miongoni mwa utekelezaji hizi, maarufu zaidi ni Stowaway iliyotengenezwa na timu ya Samourai Wallet. Mafunzo haya yanakusudia kukuongoza katika mchakato wa kufanya muamala wa Stowaway Payjoin ukitumia programu ya Sparrow Wallet.  

## Jinsi Stowaway inavyofanya kazi?  

Kama ilivyotajwa hapo awali, Samourai Wallet inatoa zana ya Payjoin iitwayo "Stowaway." Inaweza kupatikana kupitia programu ya Sparrow Wallet kwenye PC au programu ya Samourai Wallet kwenye Android. Ili kutekeleza Payjoin, mpokeaji, ambaye pia ni mshirika, lazima atumie programu inayoendana na Stowaway, yaani Sparrow au Samourai Wallet. Programu hizi mbili zinaweza kushirikiana, kuruhusu muamala wa Stowaway kati ya Sparrow Wallet na Samourai Wallet, na kinyume chake.

Stowaway hutegemea aina ya miamala ambayo Samourai inawaita "Cahoots." Cahoot ni muamala shirikishi kati ya watumiaji wengi unaohitaji exchange ya habari off-chain. Hivi sasa, Samourai inatoa zana mbili za Cahoots: Stowaway (Payjoins) na StonewallX2 (ambazotutachunguza katika makala zijazo).

Miamala ya Cahoots inahusisha kubadilishana kwa PSBT zilizotiwa saini kati ya watumiaji. Mchakato huu unaweza kuwa mrefu na mzito, hasa unapofanywa kwa mbali. Hata hivyo, bado unaweza kufanywa kwa mikono na mtumiaji mwingine, jambo linalorahisisha ikiwa washirika wako wako karibu. Kwa vitendo, hii inahusisha kubadilishana kwa mikono QR codes tano ili kuchanganuliwa mfululizo.

Inapofanywa kwa mbali, mchakato huu unakuwa tata mno. Kufanya hivyo, Samourai imeunda protocol ya mawasiliano iliyosimbwa kupitia Tor, inayoitwa "Soroban." Kupitia Soroban, exchanges zinazohitajika kwa Payjoin zinafanywa kiotomatiki nyuma ya interface rafiki kwa mtumiaji. Hii ndiyo njia ya pili tutakayojifunza katika makala hii.

Exchanges hizi zilizofichwa zinahitaji kuanzishwa kwa connection na authentication kati ya washiriki wa Cahoots. Mawasiliano ya Soroban yanategemea Paynyms za watumiaji. Ikiwa huna ujuzi wa Paynyms, nakualika uangalie makala hii kwa maelezo zaidi: [BIP47 - PAYNYM](https://planb.network/tutorials/privacy/on-chain/paynym-bip47-a492a70b-50eb-4f95-a766-bae2c5535093) 

Kuifafanua kwa ufupi, Paynym ni unique identifier iliyounganishwa na wallet yako inayoruhusu functionalities mbalimbali, kama vile encrypted messaging. Paynym huwasilishwa kama identifier na mchoro unaowakilisha roboti. Hapa ni mfano wangu kwenye Testnet: ![Paynym Sparrow](assets/en/1.webp)

**Kwa muhtasari:**

- _Payjoin_ = Muundo maalum wa muamala shirikishi;  
- _Stowaway_ = Utekelezaji wa Payjoin unapatikana kwenye Samourai na Sparrow Wallet;  
- _Cahoots_ = Jina linalotolewa na Samourai kwa aina zao zote za muamala shirikishi, ikijumuisha Payjoin Stowaway;  
- _Soroban_ = Protocol ya mawasiliano iliyosimbwa kupitia Tor, ikiruhusu ushirikiano na watumiaji wengine katika muktadha wa muamala wa Cahoots;  
- _Paynym_ = Unique identifier ya wallet inayoruhusu mawasiliano na mtumiaji mwingine kupitia Soroban, ili kutekeleza muamala wa Cahoots.

[**-> Jifunze zaidi kuhusu Payjoin transactions na matumizi yake**](https://planb.network/tutorials/privacy/on-chain/payjoin-848b6a23-deb2-4c5f-a27e-93e2f842140f) 

## Jinsi ya kuanzisha connection kati ya Paynyms?

Ili kutekeleza muamala wa mbali wa Cahoots, hasa PayJoin (Stowaway) kupitia Samourai au Sparrow, ni lazima "Follow" mtumiaji unayetamani kushirikiana naye, ukitumia Paynym yao. Katika kesi ya Stowaway, hii ina maana ya kufuata mtu unayemtumia bitcoins.

**Huu ni utaratibu wa kuanzisha connection hii:**

Kwanza, unahitaji kupata Paynym identifier ya mpokeaji. Hii inaweza kufanywa kupitia jina la utani `+...` au payment code `PM...`. Katika Sparrow wallet ya mpokeaji, chagua tab ya `Tools`, kisha bonyeza `Show PayNym`.  
![Show Paynym](assets/notext/2.webp)

Kwako upande, fungua Sparrow Wallet yako na upitie menyu ya `Show PayNym`. Ikiwa hii ni mara yako ya kwanza, bonyeza `Retrieve PayNym`.  
![Retrieve Paynym](assets/notext/3.webp)

Ifuatayo, ingiza Paynym identifier ya mshirika wako kwenye kisanduku cha `Find Contact`, kisha bonyeza `Add Contact`.  
![Add Contact](assets/notext/4.webp)

Programu itakuonyesha kitufe cha `Link Contact`. Sio lazima kubofya kitufe hiki kwa mafunzo haya.

Mara Paynym ya mpokeaji inapofuatwa na Paynym yako, rudia hatua kinyume ili mpokeaji pia akufuate. Kisha unaweza kufanya Payjoin.

## Jinsi ya kufanya Payjoin kwenye Sparrow Wallet?

Ikiwa umekamilisha hatua hizi za awali, uko tayari kufanya muamala wa Payjoin! Ili kufanya hivyo, fuata video tutorial yetu:  
![Payjoin Tutorial - Sparrow Wallet](https://youtu.be/ZQxKod3e0Mg) 

**Rasilimali za nje:**

- https://docs.samourai.io/en/spend-tools#stowaway   
- https://sparrowwallet.com/docs/spending-privately.html
