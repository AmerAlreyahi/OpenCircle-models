# OpenCircle models (archived)

> **This repository is archived. The models now live in [OptimaMT](https://huggingface.co/OptimaMT).**
>
> - **Models:** [huggingface.co/OptimaMT](https://huggingface.co/OptimaMT), one repository per language pair (49 pairs).
> - **Code, measurements and report:** [github.com/AmerAlreyahi/OptimaMT](https://github.com/AmerAlreyahi/OptimaMT).
>
> The releases below stay online for good: installed OpenCircle versions download their translation models and
> preview clips from them, each file pinned by its SHA-256. Nothing here will change.

Offline translation models that [OpenCircle](https://github.com/AmerAlreyahi/OpenCircle) downloads on demand.
OpenCircle checks every file against a SHA-256 fingerprint built into the app; a file that doesn't match is refused.

These files are ONNX conversions (int8-quantised, Xenova/transformers.js layout) of Helsinki-NLP's OPUS-MT models,
made by OpenCircle with `scripts/convert-mt-models.py` in the OpenCircle repository from the pinned source revisions
listed in each release's `manifest.json`.

## Credits and licence

OPUS-MT models by Helsinki-NLP (University of Helsinki), https://huggingface.co/Helsinki-NLP — licensed CC BY 4.0
(https://creativecommons.org/licenses/by/4.0/). Changes: converted to ONNX and quantised.

Tiedemann, J. and Thottingal, S. (2020). OPUS-MT — Building open translation services for the World.
Proceedings of EAMT 2020.

The model files are not covered by OpenCircle's MIT licence; they keep their own licence above.

## Preview clips (release previews-1)

Short AV1 screen recordings that OpenCircle's Settings downloads only when the user presses "Play preview". They are the
project owner's edited recordings. They are NOT covered by OpenCircle's MIT licence; each keeps the terms of what it shows:

```
Preview clips
-------------
The short recordings at the top of Settings pages (a still of each bundled in
the app, assets/previews; the full clips downloaded when a preview is played)
are the owner's approved edits. They show third-party material under
its own terms; the app's MIT licence does not relicense it. CC0 credits are
courtesy credits. OpenCircle's code remains MIT; the media exceptions below
(Unsplash License for the COFFEE photo, CC BY-SA 4.0 for the translation
preview) apply only to the named clips. The credits identify sources; they do not clear unrelated
search-result thumbnails, third-party interfaces or data-provider terms shown
in the clips.

- Succulent photograph (circle-1): José Gabriel Jara Porras, WordPress Photo
  Directory, CC0 1.0. Cropped and shown in an edited OpenCircle screen
  recording. https://wordpress.org/photos/photo/4569e13887/
  https://creativecommons.org/publicdomain/zero/1.0/
- Lotus photograph (circle-2): Shubham Patil, WordPress Photo Directory, CC0
  1.0. Cropped and shown in an edited OpenCircle screen recording.
  https://wordpress.org/photos/photo/4766ac73e9/
- Kingfisher photograph (circle-3): sebascordero15, WordPress Photo Directory,
  CC0 1.0. Cropped and shown in an edited OpenCircle screen recording.
  https://wordpress.org/photos/photo/11669e53a4/
- COFFEE photograph (text): Tim Mossholder on Unsplash, photo jozE5L60Aj4,
  used under the Unsplash License. Shown in an edited OpenCircle screen
  recording. No endorsement implied. MEDIA EXCEPTION: the photo in this clip
  stays under the Unsplash License (not MIT, not CC0).
  https://unsplash.com/photos/a-sign-on-a-brick-wall-that-says-coffee-jozE5L60Aj4
  https://unsplash.com/license
- Wikipedia translation (translate; applies only while assets/previews/translate.webp
  is bundled: not in builds where that clip is held): Based on "Plante d'intérieur" by
  Wikipedia contributors, CC BY-SA 4.0. Machine translation into English,
  German, Arabic and Spanish shown by OpenCircle; framing, timing edits and
  active-state graphics added for the preview. MEDIA EXCEPTION: this preview
  animation (assets/previews/translate.webp) and its poster are licensed under
  CC BY-SA 4.0, including the adapter's contributions; this does not change
  the app code's MIT licence. Underlying public-domain material remains public
  domain; third-party names and trademarks keep their separate rights. The
  exact recorded Wikipedia revision has not been established.
  Article: https://fr.wikipedia.org/wiki/Plante_d%27int%C3%A9rieur
  History: https://fr.wikipedia.org/w/index.php?title=Plante_d%27int%C3%A9rieur&action=history
  Licence: https://creativecommons.org/licenses/by-sa/4.0/ (legal code:
  LICENSES/CC-BY-SA-4.0.txt)
  Embedded photograph "Her, IFA 2018, Berlin (P1070094).jpg" (c) Matti Blume,
  CC BY-SA 4.0:
  https://fr.wikipedia.org/wiki/Fichier:Her,_IFA_2018,_Berlin_(P1070094).jpg
  Embedded painting by Carl Larsson, "Flowers on the Windowsill", public
  domain:
  https://commons.wikimedia.org/wiki/File:Blomsterf%C3%B6nstret_av_Carl_Larsson_1894.jpg
- Solar photovoltaic panel prices (ai-chat, ai-browser; the same chart): Our
  World in Data; IRENA (2025) and other sources, processed by Our World in
  Data, as credited in the recording. OWID visualization: CC BY 4.0. Cropped
  and time-edited screen recordings with OpenCircle active-state graphics.
  https://ourworldindata.org/grapher/solar-pv-prices
  https://creativecommons.org/licenses/by/4.0/
- Tourism (snip-long): Bastian Herre and Veronika Samborska (2023), "Tourism",
  Our World in Data, CC BY 4.0 for OWID-produced article and visualizations.
  Cropped, time-edited screen recording. The chart "Arrivals of tourists from
  abroad" credits UN Tourism (2025); other chart and provider notices in the
  recording are kept. https://ourworldindata.org/tourism
  https://ourworldindata.org/grapher/international-tourist-trips
  https://ourworldindata.org/faqs
- OpenCircle is an independent project and is not affiliated with, sponsored
  by, or endorsed by Google. Google and its product names and logos are
  trademarks of their respective owners. Depicted third-party services and
  content are shown for demonstration only.
```

### Translate clips (translate-1..4, added to previews-1)

- translate-1: "Sintel" (c) Blender Foundation, https://durian.blender.org/ , CC BY 3.0
  (https://creativecommons.org/licenses/by/3.0/), shown playing on YouTube in the user's browser; framed, trimmed and
  zoomed; subtitle translated by OpenCircle. OpenCircle is not affiliated with, sponsored by, or endorsed by Google or
  YouTube; Google, YouTube and their product names and logos are trademarks of their respective owners.
- translate-2..4: the game screens are original images made for OpenCircle's previews; they show no real game.
