# Asiakaspalvelu-chatin upottaminen web-sivustolle

Asiakaspalvelun sijoittaminen onnistuu web-sivustolle, mobiilisivustolle ja -aplikaatioon, blogiin tai Facebook-sivulle.

## Chatin upotuskoodi \(embed-koodi\)

Upottamista varten tarvitset ns. upotuskoodin, jonka saat Ninchatin henkilökunnalta, kun chat on valmiina. Muokkaamme ja valmistelemme chatin valmiiksi haluamallanne tavalla; teidän tulee vain sijoittaa upotuskoodi sivustolle.

Upotuskoodi on seuraavankaltainen, yhden rivin mittainen Javascript-tägi \(toimitamme teille oman koodinne\):

```markup
<script src="http://ninchat.com/[...]/ninchat-init.js" charset="UTF-8"></script>
```

### Upotuskoodin sijoittaminen

Suosittelemme sijoittamaan script-tägin web-sivun body-elementin loppuun. Esim:

```markup
        ...
        <script src="http://ninchat.com/[...]/ninchat-init.js" charset="UTF-8"></script>
    </body>
</html>
```

Upotuskoodi tulee sijoittaa jokaiselle sivulle, jolla chatin halutaan toimivan. Käytännössä script-tägi kannattaa sijoittaa sivuston header- tai footer-osioon, joka kulkee mukana jokaisella sivulla.

### Ninchatin lisääminen Wordpress-sivustolle

Ninchatin embed-koodin lisäminen Wordpress-sivustolle onnistuu muokkaamalla sivuston HTML-lähdekoodia.

1. Sivuston hallintanäkymässä siirry "Appearance"-osioon.
2. Klikkaa kohtaa "Editor", joka avaa muokkausnäkymän.
3. Selaa ja klikkaa "Theme Files" -listalta esim. "Theme footer \(footer.php\)" -sivu.
4. Liitä Ninchatin upotuskoodi haluamaasi kohtaan \(mielellään lähellä body-elementin loppua, kuitenkin sen sisäpuolelle\).

![Ninchatin lis&#xE4;&#xE4;minen Wordpress-sivustolle](../.gitbook/assets/wordpress-ninchat-ohje.png.jpg)

