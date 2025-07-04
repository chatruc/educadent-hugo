# Educadent.cl - Sitio Web con Hugo CMS

Este es el repositorio del sitio web de Educadent.cl, construido con Hugo y Decap CMS para la gestión de contenido.

## Características

- **Hugo**: Generador de sitios estáticos rápido y eficiente
- **Decap CMS**: Sistema de gestión de contenido headless
- **Diseño Responsivo**: Compatible con dispositivos móviles y de escritorio
- **Gestión de Eventos**: Sistema completo para publicar y gestionar eventos odontológicos

## Estructura del Proyecto

```
educadent-hugo/
├── content/           # Contenido en Markdown
│   ├── eventos/       # Eventos odontológicos
│   └── _index.md      # Página principal
├── layouts/           # Plantillas HTML
├── static/            # Archivos estáticos
│   └── admin/         # Configuración del CMS
├── hugo.toml          # Configuración de Hugo
└── netlify.toml       # Configuración de despliegue
```

## Desarrollo Local

### Prerrequisitos

- Hugo Extended (v0.128.2 o superior)
- Git

### Instalación

1. Clona el repositorio:
```bash
git clone <URL_DEL_REPOSITORIO>
cd educadent-hugo
```

2. Ejecuta el servidor de desarrollo:
```bash
hugo server --buildDrafts
```

3. Visita `http://localhost:1313` para ver el sitio

### Panel de Administración

El panel de administración está disponible en `/admin/` y permite gestionar:

- Eventos odontológicos
- Páginas principales del sitio
- Contenido en general

## Despliegue

El sitio está configurado para desplegarse automáticamente en Netlify cuando se realizan cambios en la rama `main`.

### Configuración de Netlify

1. Conecta este repositorio con Netlify
2. Configura las siguientes variables de entorno:
   - `HUGO_VERSION`: 0.128.2
   - `HUGO_ENV`: production

3. El comando de construcción y directorio de publicación están configurados en `netlify.toml`

## Gestión de Contenido

### Crear un Nuevo Evento

1. Ve a `/admin/` en el sitio desplegado
2. Autentícate con tu cuenta de Git
3. Selecciona "Eventos" > "Nuevo Evento"
4. Completa la información del evento
5. Guarda los cambios

### Editar Páginas

Las páginas principales se pueden editar desde el panel de administración en la sección "Páginas".

## Tecnologías Utilizadas

- **Hugo**: v0.128.2 (Extended)
- **Decap CMS**: v3.0.0
- **HTML/CSS**: Diseño personalizado responsivo
- **JavaScript**: Funcionalidades del CMS
- **Netlify**: Hosting y despliegue continuo

## Soporte

Para soporte técnico o preguntas sobre el sitio, contacta al equipo de desarrollo.

## Licencia

Este proyecto es propiedad de Educadent.cl. Todos los derechos reservados.

