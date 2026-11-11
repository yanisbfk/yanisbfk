## Yanis Boufroukh

Étudiant à CESI. Je développe des applications que j'utilise au quotidien —
simples, rapides, qui règlent un problème précis et qui tournent vraiment.

### Projets

**[FitnessBoii](https://github.com/yanisbfk/fitnessboii)** — Suivi de musculation.
Programmes calés sur tes jours d'entraînement, séance guidée un exercice à la fois
(dernière performance pré-remplie, minuteur de repos), et le suivi de progression :
records, séries de semaines, assiduité. Installable sur téléphone et PC, utilisable
hors ligne à la salle.

`React` · `TypeScript` · `Firebase` · `Netlify` · PWA

**[TrackBoii](https://github.com/yanisbfk/trackboii)** — Suivi calorique par photo.
Tu photographies ton plat, l'IA estime les calories et les macros ; les repas
habituels s'ajoutent en un tap. Application installable,
[à essayer ici](https://trackboii.netlify.app).

`React` · `Firebase` · `Gemini API` · `Netlify` · PWA

**[YanzVoice](https://github.com/yanisbfk/YanzVoice)** — Dictée vocale pour Windows.
Tu parles, le texte se colle automatiquement dans l'application active. Transcription
par Groq Whisper, audio encodé en Opus pour tenir sur une connexion faible.

`Python` · `PyQt6` · `Groq API`

### Comment je travaille

Des interfaces sobres et du code qui va droit au but. Sur les deux applications
web, les règles de sécurité Firestore sont testées sur émulateur — pas seulement
écrites — et les tests tournent à chaque commit. Les trois projets ont une
intégration continue qui casse la build si quelque chose ne passe plus.
