# unikalia-fotos

Host de imágenes de producto para los listings de Amazon de UNIKALIA.
Las URLs se pegan en los ficheros de Amazon (main_product_image_locator / other_product_image_locator_N).

## Convención de nombres

    <CARPETA_FAMILIA>/<SKU>-MAIN.jpg      -> imagen principal (fondo blanco puro)
    <CARPETA_FAMILIA>/<SKU>-PT01.jpg      -> secundaria 1
    <CARPETA_FAMILIA>/<SKU>-PT02.jpg      -> secundaria 2
    ...                                   -> hasta PT07

Ejemplo de URL final:

    https://raw.githubusercontent.com/Unikaliashop/unikalia-fotos/main/PK_TOTEG_BOT/PK_TOTEG_BOT_01-MAIN.jpg

## Requisitos de imagen (Amazon)

- MAIN: fondo blanco RGB 255,255,255 · producto >=85% del encuadre · lado largo >=1600 px · JPG/PNG · sin texto ni logos.
- PT01-07: lifestyle, infografías, medidas, mockups. Texto permitido.
