---
description: Chattien asetustiedostot
---

# Sivut-konfiguraatiot

## Yleistä <a id="yleista"></a>

Organisaatioasetusten Sivut/Sites-välilehdellä määritellään asiakaspalvelu-chattien ja julkisten ryhmäkeskustelujen asetukset, tekstit ja käännökset sekä tyylit.  
Pääset konfiguraatioihin menemällä organisaatioasetuksiin ja valitsemalla Sivut-välilehden.

{% hint style="info" %}
Sites-konfiguraatiot ovat edistyneen käyttäjän ominaisuuksia. Pyydä Ninchatin henkilöstöä tekemään muutokset, tai apua, mikäli koet sen hankalaksi.
{% endhint %}

![](../.gitbook/assets/organization-sites.png)

## Chatin tekstien muokkaaminen

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
| preAudienceQuestionnaire | Chatin alkukysely |
| postAudienceQuestionnaire | Chatin loppukysely |

Muista tallentaa muutokset.

![](../.gitbook/assets/organization-sites-1.png)

## Chatin ottaminen pois käytöstä <a id="chatin-ottaminen-pois-kaeytosta"></a>

Asiakaspalvelu-chatin voi nopeasti poistaa kokonaan käytöstä disabloimalla site-konfiguraation. Klikkaa editorinäkymässä "Disable-nappia. Konfiguraatio näkyy tämän jälkeen listalla disabloituna.  
Voit palauttaa chatin taas käyttöön klikkaamalla editorissa "Enable"-nappia.

