---
description: 'Organisaatioasetukset: jonojen hallinta'
---

# Asiakasjonojen hallinta

Jonojen hallinta tapahtuu organisaatioasetusten kautta. Klikkaa organisaation tai kanavan nimeä yläpalkissa ja valitse listalta "Organisaatioasetukset / Organization settings".

## Jono-agenttien hallinta

![](../.gitbook/assets/organization-members.png)

## Jonot

Jonot-välilehdellä voit asettaa ja poistaa agenteilla jononkäsittelyoikeuksia.

![](../.gitbook/assets/organization-queues.png)

Klikkaamalla jonon nimeä pääset muokkaaman kyseisen jonon asetuksia ja aikatauluja.

### Jonon asetukset

{% page-ref page="../asiakasjonot-ja-keskustelut/jonon-asetukset.md" %}

## Tunnisteet \(Tägit\)  <a id="keskustelumerkintojen-hallinta-tagit"></a>

Tunnisteet eli tägit ovat helppo ja nopea tapa agenteille luokitella asiakaskeskusteluja.

Organisaation operaattorit voivat lisätä, muokata ja poistaa tägejä.

![](../.gitbook/assets/organization-tags.png)

1. Klikkaa tagin nimeä muokatakseen nimeä tai poistaaksesi se.
2. Klikkaa maalikuvaketta vaihtaaksesi tagin väri. Värit ovat hyvä tapa erottaa eri kategorioiden tagit.
3. Lisää kategoriaan alimerkintä.
4. Lisää ylimmän luokan merkintä \(kategoria\).

## Sites-konfiguraatiot

Sites-välilehdellä voidaan muokata asiakaspalvelu-chattien ja julkisten ryhmäkeskustelujen tekstejä, tyylejä ja asetuksia.

{% hint style="info" %}
Sites-konfiguraatiot ovat edistyneen käyttäjän ominaisuuksia. Pyydä Ninchatin henkilöstöä tekemään muutokset, mikäli koet sen hankalaksi.
{% endhint %}

![](../.gitbook/assets/organization-sites.png)

### Chatin tekstien muokkaaminen

Avaa konfiguraatio klikkaamalla kynä-ikonia oikeassa laidassa.

Konfiguraatioeditorissa näet chatin asetukset, tekstit ja käännökset. Niitä voi muuttaa siitä haluamakseen. Tekstien seassa saattaa näkyä HTML-elementtejä, kuten _&lt;p&gt;&lt;/p&gt;_ \(kappale\), _&lt;br&gt;_ \(rivinvaihto\).  
Monikielisessä toteutuksessa eri kielille on omat tekstielementtinsä.

#### Yleisimpiä muutettavia tekstejä

| Elementti | Kuvaus |
| :--- | :--- |
| welcome | Chatin alkunäkymän yläosan sisältö |
| motd | Chatin alkunäkymän alaosan sisältö |
| noQueuesText | Opasteteksti chatin ollessa suljettuna \(Yhteydenottolomake korvaa tekstin, mikäli se on asetettu käyttön.\) |
| inQueueText | Opasteteksti jonotusnäkymässä |
| userName | Asiakkaan vakionimi keskutelussa |

Muista tallentaa muutokset.

![](../.gitbook/assets/organization-sites-1.png)

### Chatin ottaminen pois käytöstä

Asiakaspalvelu-chatin voi nopeasti poistaa kokonaan käytöstä disabloimalla site-konfiguraation. Klikkaa editorinäkymässä "Disable-nappia. Konfiguraatio näkyy tämän jälkeen listalla disabloituna.  
Voit palauttaa chatin taas käyttöön klikkaamalla editorissa "Enable"-nappia.

