# Up to Date Damesmode — Shopify-thema (handleiding)

Dit is een volledig **Shopify Online Store 2.0-thema** met exact dezelfde uitstraling als de website-blauwdruk
(zelfde kleuren, lettertypes en opmaak — en volledig responsive op mobiel, iPad en laptop). Het is gekoppeld aan
Shopify's eigen producten, winkelmand, checkout en klantaccounts.

> ✨ **Nieuw in v5.3 (tess v-layout):** zachtroze aankondigingsbalk, vaste lichte header met verlanglijst-hartje,
> een **mega-menu met promo-afbeeldingen**, een **split-hero** (twee foto's + grote titel), een **"Seen on"**-Instagramstrook
> met @-namen, een **"Onze winkels"**-sectie met plaats-tags, en **subcategorie-tabs** op de collectie-/sale-pagina.
> Zie **§7** hieronder om ze te vullen.

> 📦 **Er staat al een upload-klaar bestand klaar:** `up-to-date-damesmode-shopify-theme-v5.3.zip` (in de hoofdmap van het project).
> Dat is het enige bestand dat je nodig hebt om te uploaden.

---

## 1. Wat zit erin?
- **layout/** – het raamwerk van elke pagina (`theme.liquid`)
- **sections/** – alle bouwblokken: header, footer, hero, producten, collectie, contact, winkelmand, enz.
- **snippets/** – herbruikbare stukjes (o.a. de productkaart)
- **templates/** – welke secties op welke pagina komen (home, product, collectie, pagina, winkelmand, zoeken, 404)
- **templates/customers/** – inloggen, registreren, account, bestellingen, adressen
- **assets/** – `base.css` (de vormgeving) en `global.js` (menu, winkelmand-lade, zoeken, sliders, maat-adviseur)
- **config/** + **locales/** – thema-instellingen en Nederlandse teksten

---

## 2. Uploaden in Shopify (5 minuten)
1. Log in op je **Shopify-admin**.
2. Ga naar **Online Store → Thema's**.
3. Klik bij *Themabibliotheek* op **Toevoegen → Zip-bestand uploaden**.
4. Kies **`up-to-date-damesmode-shopify-theme.zip`** en upload.
5. Klik op **Voorbeeld** om te bekijken. Tevreden? Klik op **Publiceren**.

> ⚠️ **Belangrijk:** upload altijd de **kant-en-klare zip**. Maak je zelf een nieuwe zip, zorg dan dat de mappen
> (`assets`, `config`, `layout`, `locales`, `sections`, `snippets`, `templates`) **in de root van de zip** staan —
> niet in een extra map eromheen. Anders weigert Shopify het thema.

---

## 3. Eerste instellingen (in de Thema-editor → "Aanpassen")
**Kleuren en lettertypes hoef je niet in te stellen** — die zitten al in het ontwerp.

Wel even doen:
- **Logo & favicon:** Thema-instellingen → Algemeen (of upload je logo bij de header-sectie).
- **Menu's** (Online Store → Navigatie):
  - Maak een **hoofdmenu** met de naam/handle **`main-menu`** met: Home, Collectie, **Producten** (met sublinks naar je collecties → dit wordt automatisch de uitklap-dropdown), Over ons, Contact.
  - Maak **footer-menu's** (bv. "Klantenservice", "Shop") en koppel ze in de footer-sectie.
- **Sociale links & bedrijfsgegevens:** staan al ingevuld (Instagram/TikTok/Facebook, e-mail info@uptodatedamesmode.nl, adres, KVK) — pas aan waar nodig in Thema-instellingen.

---

## 4. Je inhoud koppelen
- **Producten & collecties:** voeg je producten toe (Producten → Toevoegen) met foto's, prijs, varianten (maat/kleur)
  en stop ze in **collecties** (bv. Jurken, Schoenen). De product- en collectiepagina's vullen zich dan automatisch.
- **Pagina's** (Online Store → Pagina's): maak pagina's aan voor **Over ons, Algemene voorwaarden, Privacybeleid,
  Cookies, Maattabel, Verzending & retour, Veelgestelde vragen** en plak de teksten uit de blauwdruk erin.
  Koppel ze daarna aan je menu/footer.
- **Contactpagina:** maak een pagina "Contact" en kies rechts bij *Themasjabloon* het sjabloon **`contact`**
  (dan krijg je het contactformulier + gegevens + kaart).
- **Foto's:** vervang de stijlvolle placeholders door je eigen foto's — overal waar nog geen afbeelding is,
  toont het thema automatisch een nette placeholder.

---

## 5. Afrondpunten ná het uploaden (klein, in Shopify)
Deze dingen kun je in Shopify perfectioneren (het thema werkt al, dit is finetuning):
- **Maat/kleur-swatches → varianten:** de variantkeuze werkt via een keuzelijst in het productformulier; de mooie
  swatch-/maatknoppen exact aan varianten koppelen is een kleine JS-afrondstap (of via een gratis swatch-app).
- **Winkelmand-lade (AJAX):** de winkelmand werkt via de winkelmand-pagina; live "toevoegen zonder herladen" in de
  zijlade is een optionele uitbreiding.
- **Instagram-feed:** koppel je echte posts met een gratis app/widget (bv. Instafeed, Behold).
- **Verlanglijst:** gebruik een gratis wishlist-app (bv. Wishlist Plus) en koppel de verlanglijst-knop.
- **Betaalmethoden (iDEAL e.d.):** zet **Shopify Payments** aan (Instellingen → Betalingen).

---

## 6. Ga-live checklist
- [ ] Thema geüpload en gepubliceerd
- [ ] Hoofdmenu `main-menu` + footer-menu's ingesteld
- [ ] Logo + favicon geüpload
- [ ] Producten + collecties toegevoegd (met foto's en varianten)
- [ ] Pagina's (Over ons, voorwaarden, privacy, cookies, maattabel, verzending, FAQ) aangemaakt en gekoppeld
- [ ] Contactpagina met sjabloon `contact`
- [ ] Betaalmethoden (Shopify Payments / iDEAL) actief
- [ ] Verzendkosten & -regio's ingesteld
- [ ] Eigen domein (uptodatedamesmode.nl) gekoppeld
- [ ] Testbestelling gedaan

Veel succes met de lancering! 🖤

---

## 7. De nieuwe tess v-onderdelen vullen (v5.3)
Alle onderdelen tonen meteen nette voorbeelden; hieronder vervang je die door je eigen inhoud
(**Online Store → Thema's → Aanpassen**).

- **Zachtroze aankondigingsbalk** — sectie *Aankondigingsbalk*. Laat de kleuren leeg voor de roze
  standaard, of kies je eigen achtergrond-/tekstkleur. Berichten voeg je toe als blokken (ze roteren vanzelf).
- **Mega-menu met promo-foto's** — de uitklapmenu's komen uit je **hoofdmenu** (Content → Menu's):
  - Een menu-item met **subitems** wordt automatisch een mega-menu.
  - Sleep je onder een subitem nóg een niveau (sub-sub-items), dan krijg je **meerdere kolommen met koppen**
    naast elkaar (zoals "Friday Denim" + "Jumpsuits").
  - **Promo-afbeeldingen rechts:** sectie *Koptekst* → **Blok toevoegen → "Mega-menu promo"**. Vul bij
    *"Bij welk menu-item?"* de exacte titel van het hoofd-menu-item in (bijv. `friday denim`) en kies 1–2 foto's
    met bijschrift. Meerdere menu-items? Voeg per item een blok toe.
- **Split-hero (twee foto's + grote titel)** — sectie *Split-hero*: kies een linker- en rechterfoto (elk met
  eigen link), zet de grote titel (bijv. "Festival"), en kies hoogte + tekstpositie.
- **"Seen on"-Instagramstrook** — sectie *Seen on (Instagram)*: voeg per foto een blok toe met afbeelding,
  **@-naam** en link. De pijltjes/slider werken vanzelf.
- **"Onze winkels"** — sectie *Onze winkels*: voeg per plaats een blok toe (plaatsnaam + optionele link,
  desgewenst "uitlichten" voor een roze tag).
- **Subcategorie-tabs op de collectie-/sale-pagina** — maak een menu (Content → Menu's) met links naar je
  subcollecties (bijv. *Alle sale*, *Jurken & rokjes sale*, *Tops & blouses sale*). Koppel dat menu daarna in de
  **Collectiepagina**-sectie bij *"Subcategorie-tabs (menu)"*. De tab van de collectie die je bekijkt is automatisch actief.

> 💡 De **hero**- en **TikTok**-secties uit v5.2 blijven in het thema aanwezig; de homepage gebruikt nu de
> nieuwe split-hero en "Seen on"-strook.
