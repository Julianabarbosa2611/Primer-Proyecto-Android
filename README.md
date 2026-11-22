# Primer-Proyecto-Android
Proyecto en Android que:  Soporte cuatro idiomas.  Utilice la imagen adjunta como fondo generando su archivo nine-patch para que sea redimensionable.  Brinde soporte a múltiples pantallas.
├── app/
│   ├── build.gradle
│   └── src/main/
│       ├── AndroidManifest.xml
│       ├── java/com/example/primerproyecto/MainActivity.java
│       └── res/
│           ├── values/            strings.xml (es - default), colors.xml, themes.xml, dimens.xml (teléfono)
│           ├── values-en/         strings.xml (inglés)
│           ├── values-fr/         strings.xml (francés)
│           ├── values-de/         strings.xml (alemán)
│           ├── values-sw600dp/    dimens.xml (tablets 7")
│           ├── values-sw720dp/    dimens.xml (tablets/pantallas ≥10")
│           ├── layout/            activity_main.xml (portrait / default)
│           ├── layout-land/       activity_main.xml (landscape)
│           ├── drawable/          button_outline.xml
│           ├── drawable-nodpi/    bg_clouds_android.9.png (fondo nine-patch)
│           └── mipmap-*/          ic_launcher.png (íconos de la app)
├── build.gradle
├── settings.gradle
├── gradle.properties
└── .gitignore
