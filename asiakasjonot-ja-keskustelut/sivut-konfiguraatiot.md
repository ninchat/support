---
description: Chattien asetustiedostot
---

# Sivut-konfiguraatiot

## Yleistä <a href="yleista" id="yleista"></a>

Organisaatioasetusten _Sivut/Sites_-välilehdellä määritellään asiakaspalvelu-chattien ja julkisten ryhmäkeskustelujen asetukset, tekstit ja käännökset sekä tyylit.\
Pääset konfiguraatioihin menemällä organisaatioasetuksiin ja valitsemalla Sivut-välilehden.

{% hint style="info" %}
Sites-konfiguraatiot ovat edistyneen käyttäjän ominaisuus. Pyydä Ninchatin henkilöstöä tekemään muutokset, tai kysy apua, mikäli koet sen hankalaksi.
{% endhint %}

![](../.gitbook/assets/organization-sites.png)

## Chatin tekstien muokkaaminen

Avaa konfiguraatio klikkaamalla ![](../.gitbook/assets/pen-edit-icon.png)kynä-ikonia oikeassa laidassa.

Konfiguraatioeditorissa näet chatin asetukset, tekstit ja käännökset. Niitä voi muuttaa siitä haluamakseen. Tekstien seassa saattaa näkyä HTML-elementtejä. Monikielisessä toteutuksessa eri kielille on omat tekstielementtinsä.

#### Yleisimpiä muutettavia tekstejä

| Elementti                 | Kuvaus                                                                                                         |
| ------------------------- | -------------------------------------------------------------------------------------------------------------- |
| welcome                   | Chatin alkunäkymän yläosan sisältö                                                                             |
| motd                      | Chatin alkunäkymän alaosan sisältö                                                                             |
| noQueuesText              | <p>Näytettävä sisältö chatin ollessa suljettuna.</p><p>(Mikäli käytössä ei ole yhteydenottolomaketta, tms)</p> |
| inQueueText               | Jonotusnäkymän opasteteksti                                                                                    |
| userName                  | Asiakkaan vakionimi keskutelussa                                                                               |
| translations              | Yleiset tekstimääritykset eli käännökset käytetylle kielelle                                                   |
| preAudienceQuestionnaire  | Chatin alkukysely (tai offline-yhteydenottolomake)                                                             |
| postAudienceQuestionnaire | Chatin loppukysely                                                                                             |
| window - titlebar - title | Chat-ikkunan otsikko                                                                                           |

#### Yleisiä käytettyjä HTML-elementtejä <a href="yleisia-kaytettyja-html-elementteja" id="yleisia-kaytettyja-html-elementteja"></a>

| HTML-tagi                                                                       | kuvaus                     |
| ------------------------------------------------------------------------------- | -------------------------- |
| \<br>                                                                           | Rivinvaihto                |
| \<p>tekstiä\</p>                                                                | Kappale                    |
| \<h2>Otsikko\</h2>                                                              | Otsikko ( h1, h2, h3, h4 ) |
|  \<a href="https://osoite.fi" target="\_blank" title="kuvaus">Linkkiteksti\</a> | Linkki                     |

Esimerkki: Kappale jossa tekstiä, rivinvaihto ja linkki

```markup
<p>Täältä löydät ohjeet:<br><a href="https://osoite.com" target="_blank" title="Linkki ohjeisiin">Ohjeisivusto</a></p>
```

{% hint style="info" %}
Muista tallentaa muutokset. 
{% endhint %}

![](../.gitbook/assets/organization-sites-1.png)

## Chatin ottaminen pois käytöstä <a href="chatin-ottaminen-pois-kaeytosta" id="chatin-ottaminen-pois-kaeytosta"></a>

Asiakaspalvelu-chatin voi nopeasti poistaa kokonaan käytöstä disabloimalla site-konfiguraatio. Klikkaa editorinäkymässä _Poista käytöstä/Disable_-nappia. Konfiguraatio näkyy tämän jälkeen listalla disabloituna.\
Voit palauttaa chatin taas käyttöön klikkaamalla editorissa "Enable"-nappia.

{% hint style="warning" %}
Älä poista konfiguraatiota käytöstä ellet varmasti tiedä, mitä teet.
{% endhint %}
