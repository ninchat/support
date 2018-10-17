# Ryhmäkeskustelun upottaminen web-sivustolle

Julkisen ryhmäkeskustelun sijoittaminen onnistuu web-sivustolle, mobiilisivustolle ja -aplikaatioon, blogiin tai Facebook-sivulle.

## Chatin upotuskoodi \(embed-koodi\)

Upottamista varten tarvitset ns. upotuskoodin, jonka saat Ninchatin henkilökunnalta, kun chat on valmiina. Muokkaamme ja valmistelemme chatin valmiiksi haluamallanne tavalla; teidän tulee vain sijoittaa upotuskoodi sivustolle.

Julkinen ryhmäkeskustelu sijoitetaan yleensä osaksi web-sivun sisältöä, sen sekaan esimerkiksi div-elementtiin. Tarvitset upottamista varten 1\) raamielementin \(container\) oikealla tunniste-ID:llä 2\) upotus-script-tägin. Upotuskoodi on yhden rivin mittainen Javascript-tägi \(toimitamme teille oman koodinne\). 

Container-elementin tyyli, sijainti ja koko on täysin teidän päätettävissänne. Oheisessa esimerkissä lyhyt esimerkkityyli \(style\) ja esimerkki-upotuskoodi.

```markup
<div id="ninchat-groupchat-container" style="width: 100%; height: 500px; border: solid 1px #000;"></div>
...
<script src="http://ninchat.com/[...]/ninchat-public-init.js" charset="UTF-8"></script>
```

### Upotuskoodin sijoittaminen

Container-elementti sijoitetaan haluttuun kohtaan ja tyylitellään halutulla tavalla. Avustamme tyylittelyssä tarvittaessa.  
Embed-script-tägin suosittelemme sijoittamaan web-sivun body-elementin loppuun. Esim:

```markup
        <section id="groupchat" class="page-section">
           <!-- Ninchat-ryhmäkeskusteluelementti -->
           <div id="ninchat-groupchat-container"></div>
        </section>
        ...
        <!-- Ninchat-upotus-script -->
        <script src="http://ninchat.com/[...]/ninchat-init.js" charset="UTF-8"></script>
    </body>
</html>
```

{% hint style="info" %}
Mikäli sivustolla käytetään sekä yksityistä asiakaspalvelu-chattia että julkista ryhmäkeskustelua, ne tulee käynnistää samalla upotus-script-tagilla. Samalla sivulla ei voi olla useaa upotuskoodia, muuten chattien toiminta menee sekaisin.
{% endhint %}

