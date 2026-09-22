# Documentación UD1 Lenguajes de Marcas

## Introducción a Lenguajes de Marcas

### Definición

Un lenguaje de marcas organiza información mediante una sintaxis basada en marcas o etiquetas.

### Clasificación de Lenguajes de Marcas

|Tipo|Uso|Ejemplos|
|----|---|--------|
|Presentación|Dar formato a documentos|HTML, CSS|
|Intercambio de Información|Almacenar información de forma ordenada|XML, RSS|
|Documentación|Documentar proyectos|Markdown, WikiTex|

## Instalación y configuración del entorno

1. Instalamos [VS Code](https://code.visualstudio.com/)
2. Instalamos plugins
   - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
    - [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)
    - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
    - [HTML CSS support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
3. Instalamos git
```bash
sudo apt install git
```

4. Configurar repositorio git (en la carpeta principal del proyecto)
```bash
git init
git add .
git commit -m "Comentario descriptivo"
```

5. Conectar con github
```bash
git remote add origin https://github.com/pablolagoprieto/LM.Pablo.git
git branch -M main
git push -u origin main
```

## Descripción de plugins

  |Nombre|Uso|Imagen|
  |---|---|---|
  |Markdown All in One|Visualizar los markdown formateados|![](https://yzhang.gallerycdn.vsassets.io/extensions/yzhang/markdown-all-in-one/3.6.3/1741534224980/Microsoft.VisualStudio.Services.Icons.Default)|
  |XML|Facilitar sintaxis y autocompletado de XML|![](https://redhat.gallerycdn.vsassets.io/extensions/redhat/vscode-xml/0.29.2026091508/1789462552068/Microsoft.VisualStudio.Services.Icons.Default)|
  |Live Preview|Visualizar los HTML formateados|![](https://ms-vscode.gallerycdn.vsassets.io/extensions/ms-vscode/live-server/0.5.2026091601/1789550624683/Microsoft.VisualStudio.Services.Icons.Default)|
  |HTML CSS support|Facilitar la sintaxis y el autocompleatado de CSS|![](https://ecmel.gallerycdn.vsassets.io/extensions/ecmel/vscode-html-css/2.0.14/1770897391434/Microsoft.VisualStudio.Services.Icons.Default)|
