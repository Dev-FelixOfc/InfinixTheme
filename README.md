##. CREDITOS:

> MayTheme (github.com/SoySapo6/MayTheme)
Dejenle una estrella de parte mía.

</details>

## Instalación

Siga estos pasos para la implementación del tema en su entorno de producción.

### 1. Clonar el Repositorio

Acceda al directorio de temas de su instalación CtrlPanel y clone los archivos fuente.

```bash
cd /var/www/ctrlpanel/themes
git clone https://github.com/Dev-FelixOfc/InfinixTheme.git
cp -r /var/www/ctrlpanel/themes/InfinixTheme/InfinixTheme /var/www/ctrlpanel/public/themes
```

> **NOTA:** Si decides actualizar el tema ejecuta ```cd /var/www/ctrlpanel/themes/InfinixTheme; git pull && rm -rf /var/www/ctrlpanel/public/themes/InfinixTheme && cp -r /var/www/ctrlpanel/themes/InfinixTheme/InfinixTheme /var/www/ctrlpanel/public/themes```

### 2. Activación

1.  Ingrese a su panel de administración.
2.  Navegue a **Configuraciones** > **General**.
3.  Bajas hasta encontrarte con "Theme", seleccione **InfinixTheme**.
4.  Guarde los cambios.