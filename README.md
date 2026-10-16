# Operation Trainer — Landing (redirección a Google Play)

Página estática bilingüe (ES/EN) para poner en la bio de Instagram. Enlaza a:
https://play.google.com/store/apps/details?id=com.myshkin.OperationTrainer

## Desplegar en Vercel
`npx vercel --prod` desde esta carpeta. Sin build: todo es estático.

## Cambiar el link de Google Play
La constante `PLAY_URL` en el `<script>` del final de `index.html`.

## Idioma
Se elige solo: `?lang=en` / `?lang=es` en la URL > preferencia guardada > idioma del navegador > español.
El switch Español/English está arriba a la derecha. Los textos viven en el objeto `T` del `<script>`.

## Capturas
`img/*.jpg` son las 6 capturas de la ficha de Play Store (en inglés). Si haces capturas
nuevas, reemplaza los archivos con el mismo nombre.

## Redirección automática
`AUTO_REDIRECT = true` hace que la página salte sola a Google Play tras `AUTO_REDIRECT_DELAY` ms.


--link:
https://operation-trainer.vercel.app/