# PCCF - FPB Informàtica d'Oficina

Este repositori conté el **Projecte Curricular de Cicle Formatiu (PCCF)** del cicle de **Formació Professional Bàsica en Informàtica d'Oficina**, elaborat a partir de la plantilla ABP de [PlantillesABP](https://github.com/juatafe/PlantillesABP).

## 📁 Estructura del projecte

- `docs/`: Contingut curricular en format Markdown
- `mkdocs.yml`: Configuració del projecte MkDocs
- `assets/`: Fulls d’estil, logotips i imatges
- `.cache/`: Carpeta generada automàticament (es pot ignorar)

## 🛠️ Requisits

- Python 3.x
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
- Plugins:
  - `mkdocs-mermaid2-plugin`
  - `mkdocs-git-revision-date-localized-plugin`
  - `mkdocs-pdf-export-plugin` (opcional)

## 🚀 Ús

Per visualitzar el contingut localment:

```bash
mkdocs serve
```

Per generar el lloc web:

```bash
mkdocs build
```

Per generar PDF (requereix `pandoc`, `LaTeX` i plantilla Eisvogel):

```bash
./compilar.sh
```

---

> 🧉 Fet amb cafè, constància i una miqueta de desesperació burocràtica.  
> 💻💥 Qualsevol millora o adaptació al teu centre és benvinguda.
