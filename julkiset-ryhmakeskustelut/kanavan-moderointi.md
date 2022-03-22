---
description: Ryhmäkanavien moderointityökalut
---

# Kanavan moderointi

## Yleistä

Kanavaa voidaan ohjata ja moderoida seuraavista paikoista: Keskustelutyökalut, Kanavavalikko, Jäsenlistan käyttäjävalikko, Kanavan asetukset.

Moderointityökalut näkyvät kun agentille on kyseisellä kanavalla annettu moderointioikeudet ![](../.gitbook/assets/moderator.png). Kanavan operaattoriagentti voi jakaa muille agenteille moderointioikeuksia. Oikeudet ovat kanavakohtaisia.

{% hint style="info" %}
Kun sinulle on annettu moderointioikeudet, päivitä sivu, jotta muutos astuu voimaan.
{% endhint %}

{% hint style="info" %}
### Älä pidä moderaattorioikeuksia turhaan käytössä <a href="#ala-pida-moderaattorioikeuksia-turhaan-kaytossa" id="ala-pida-moderaattorioikeuksia-turhaan-kaytossa"></a>

Moderaattorioikeuksia ei kannata pitää turhaan päällä, varsinkaan yksityisillä tiimikanavilla. Näin moderaattori ei esim. vahingossa piilota viestejä tai poista käyttäjiä kanavalta.
{% endhint %}

## Moderointityökalut

![Moderaattorin työkalut ja valinnat](../.gitbook/assets/channel-embed-moderation.png)

### Piilotetut viestit

Keskusteluista on moderaattorin työkaluilla mahdollista piilottaa viestejä, esim. häiritsevät tai turhat viestit. Katso ohjeet alta. Jotta näkisit piilotetut viestit itse, sinun tulee omissa käyttäjäasetuksissa asettaa piilotetut viestit näkyviksi. Ohje:&#x20;

{% content-ref url="ryhmakeskustelun-jarjestaminen.md" %}
[ryhmakeskustelun-jarjestaminen.md](ryhmakeskustelun-jarjestaminen.md)
{% endcontent-ref %}

### Kanavan asetukset

#### Kuka voi kirjoittaa kanavalle

Kanavan asetusten kautta voit määrittää, miten vieraat voivat kirjoittaa kanavalle. Voit esim. vähentää häiriökäyttäytymistä hiljentämällä uudet vieraat automaattisesti, tai piilottamalla uusien vieraiden viestit automaattisesti.

Katso lisätietoa Kanavan asetukset -sivun kohdassa "Turvallisuusasetukset - kuka voi kirjoittaa kanavalle":

{% content-ref url="../tiimikanavat/kanavan-asetukset.md" %}
[kanavan-asetukset.md](../tiimikanavat/kanavan-asetukset.md)
{% endcontent-ref %}

Lisää kanavan määrittelyjä alempana kohdassa "Kanavavalikko".

### Keskustelutyökalut

Moderointityökalut tulevat esille kun hiiren osoittimen vie kommentin päälle.

![Moderaattorin kommenttityökalut](<../.gitbook/assets/moderator-comment-tools (1).png>)

| Kommenttityökalu                                                                                                                                                            | Toiminta                                                                                                                           |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| ![](../.gitbook/assets/mod1.png) **Piilota viesti / Hide message**                                                                                                          | Piilota kyseinen viesti muilta käyttäjiltä                                                                                         |
| ![](../.gitbook/assets/unhide-message.png)**Näytä viesti / Show message**                                                                                                   | Näytä piilotettu viesti                                                                                                            |
| ![](../.gitbook/assets/mod2.png) **Vaienna käyttäjä / Silence user**                                                                                                        | Käyttäjä hiljennetään toistaiseksi                                                                                                 |
| <p><img src="../.gitbook/assets/mod3.png" alt=""> <strong>Vaienna käyttäjä x ajaksi /</strong> <br><strong>Silence this user for time being</strong></p>                    | <p>Käyttäjä hiljennetään valituksi ajaksi <br>(tämän jälkeen hän saa taas kirjoittaa)</p>                                          |
| <p><img src="../.gitbook/assets/mod4.png" alt=""> <strong>Piilota kaikki käyttäjän viestit /</strong> <br><strong>Hide all messages from this user</strong></p>             | Kaikki käyttäjän viestit piilotetaan muilta vierailta                                                                              |
| <p><img src="../.gitbook/assets/mod5.png" alt=""> <strong>Näytä/piilota käyttäjän uudet viestit /</strong> <br><strong>Toggle hide new messages from this user</strong></p> | <p>Käyttäjän uudet viestit piilotetaan/näytetään vakiona</p><p>(moderaattori voi käsin piilottaa/näyttää yksittäisiä viestejä)</p> |

### Käyttäjävalikko

Klikkaa haluttua käyttäjää jäsenlistalla nähdäksesi käyttäjävalikko.&#x20;

| Käyttäjävalikko                                | Toiminta                                                                                                                           |
| ---------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **Vaienna / Silence**                          | Käyttäjä hiljennetään toistaiseksi                                                                                                 |
| **Piilota kaikki viestit / Hide all messages** | Kaikki käyttäjän viestit piilotetaan muilta vierailta                                                                              |
| **Piilota uudet viestit / Hide new messages**  | <p>Käyttäjän uudet viestit piilotetaan/näytetään vakiona</p><p>(moderaattori voi käsin piilottaa/näyttää yksittäisiä viestejä)</p> |
| **Poista kanavalta / Remove from channel**     | Käyttäjä poistetaan kokonaan keskustelusta.                                                                                        |

### Kanavavalikko

Klikkaa kanavan nimeä yläpalkissa nähdäksesi kanavavalikko.

| Valinta                                                                    | Toiminta                                                                                                             |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Vaienna kaikki / Silence all**                                           | Kukaan käyttäjistä ei voi enää kirjoittaa uusia viestejä.                                                            |
| **Epävaienna kaikki / Unsilence all**                                      | Anna kaikille käyttäjille lupa kirjoittaa viestejä.                                                                  |
| **Ota automaattinen viestien piilotus käyttöön / Enable autohide for all** | Kaikkien uusien käyttäjien viestit piilotetaan automaattisesti. Moderaattori voi paljastaa viestit käsin yksitellen. |
| **Poista automaattinen viestien piilotus / Disable autohide for all**      | Uusien käyttäjien viestit näytetään automaattisesti.                                                                 |
| **Sulje kanava / Close channel**                                           | Kanava ja keskustelu suljetaan                                                                                       |
