# 🛠️ Repositorio de Plantillas MechBot 2.0x
[![Django CI](https://github.com/MechBot-2x/mechbot-templates/actions/workflows/django.yml/badge.svg)](https://github.com/MechBot-2x/mechbot-templates/actions/workflows/django.yml)
[![MechBot Supercharged CI](https://github.com/MechBot-2x/mechbot-templates/actions/workflows/CI.yml/badge.svg)](https://github.com/MechBot-2x/mechbot-templates/actions/workflows/CI.yml)
![GitHub](https://img.shields.io/badge/Estado-Producción-brightgreen)
![GitHub last commit](https://img.shields.io/github/last-commit/mechmind-dwv/mechbot-templates)
[![GitHub](https://img.shields.io/badge/Ver_en_GitHub-181717?style=for-the-badge&logo=github)](https://github.com/mechbot-templates/marketing)
 
Repositorio centralizado de plantillas para el proyecto MechBot 2.0x. Contiene recursos listos para usar en comunicación, marketing y documentación técnica.

### Características destacadas:

1. **Enfoque en usabilidad**: Instrucciones claras en español
2. **Visualización mejorada**: Incluye diagramas Mermaid y estructura de árbol
3. **Componentes técnicos**: Requisitos y comandos específicos
4. **Branding consistente**: Mantiene identidad de MechBot
5. **Soporte para colaboración**: Guía de contribución detallada

## 📌 Características Principales

- ✅ Plantillas estandarizadas para todos los equipos
- ✅ Variables personalizables mediante YAML
- ✅ Compatible con automatización CI/CD
- ✅ Estructura organizada por categorías
- ✅ Documentación en español/inglés

## 🗂 Estructura del Repositorio

```
mechbot-templates/
├── comunicacion/          # Email, presentaciones, guiones
├── marketing/            # Redes sociales, anuncios
├── tecnica/              # Documentación API, manuales
├── reportes/             # Plantillas analíticas
├── variables/            # Archivos de configuración
│   └── globales.yaml     # Variables compartidas
└── herramientas/         # Scripts de automatización
```

## 🚀 Primeros Pasos

### Requisitos
- Git 2.30+
- Python 3.8+ (para scripts de automatización)
- Librerías: `Jinja2`, `PyYAML`

### Instalación
```bash
git clone https://github.com/mechmind-dwv/mechbot-templates.git
cd mechbot-templates
pip install -r herramientas/requirements.txt
```

### Uso Básico
1. Edita las variables en `variables/globales.yaml`
2. Genera plantillas:
```bash
python herramientas/generador.py -t comunicacion/onboarding
```

## 🛠 Flujo de Trabajo Recomendado

```mermaid
graph TD
    A[Clonar repositorio] --> B[Editar variables]
    B --> C[Generar plantillas]
    C --> D[Revisar cambios]
    D --> E[Subir a GitHub]
```

## 🤝 Cómo Contribuir

1. Haz fork del repositorio
2. Crea una rama (`git checkout -b mejora/descripcion`)
3. Haz commit de tus cambios (`git commit -m 'Añade X plantilla'`)
4. Haz push a la rama (`git push origin mejora/descripcion`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo licencia [MIT](LICENSE).

---

## 📬 Contacto

Equipo de Ingeniería MechBot  
📧 ia.mechmind@gmail.com  
🔗 [Sitio Oficial](https://mechbot.com)

[![Logo MechBot](https://via.placeholder.com/100x30?text=MechBot+Logo)](https://mechbot.com)
