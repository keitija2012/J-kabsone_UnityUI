# J-kabsones_UnityUI – Supervaroņa / tēla kustomizācijas projekts

Unity 2D ieskaites darbs, kurā tiek izmantoti dažādi UI elementi, lai izveidotu interaktīvu tēla apģērbšanas un personalizācijas aplikāciju.

## Projekta mērķis un prasmes
Šis projekts demonstrē:
- Sākuma izvēlni ar scenām pārslēgšanu
- Teksta ievadi (InputField): vārds + dzimšanas gads (tikai cipari)
- Vecuma aprēķinu un rezultāta attēlošanu
- Tēla izvēli (Dropdown)
- Apģērbu kategorijas (Toggle) – bikses, zābaki, cepures, cimdi, amuleti u.c. (katrai ≥3 varianti)
- Drag & Drop funkcionalitāti apģērbu pārvietošanai uz tēla
- Sliders tēla garuma un platuma maiņai
- ScrollView ar dinamisku tēla aprakstu
- Skaņas efektus (pogas klikšķi, fona mūzika, ekipēšanas skaņas)

## Kā palaist projektu
1. Atver Unity Hub vai Unity Editor
2. Importē projektu no mapes, kur tas ir lejupielādēts
3. Atver vienu no ainām:
   - **StartMenu.unity** → sākuma ekrāns (pogas "Sākt" un "Iziet")
   - **Customization.unity** → galvenā apģērbšanas saskarne
4. Spied **Play** pogu

## Tehnoloģijas / izmantotie Unity elementi
- Canvas (Screen Space - Overlay)
- UI komponentes: Button, Text (TMP), InputField, Dropdown, Toggle, Slider, ScrollView
- AudioSource + AudioClip
- EventSystem (drag & drop)
- Scenu pārvaldība (SceneManager)
- Git versiju kontrole (regulāri commiti)

## Projekta struktūra (galvenās mapes)
- **Assets/Scripts** – visi C# skripti
- **Assets/Images** – sprite faili tēliem un apģērbiem
- **Assets/Audio** – skaņas faili
- **Assets/Scenes** – StartMenu.unity un Customization.unity
- **Assets/Prefabs** – drag & drop apģērbu prefabi

## Versiju vēsture
Projekts tiek regulāri commitots GitHub, lai parādītu izstrādes procesu.

## Autors

- Monta Jēkabsone
- Ieskaites darbs






