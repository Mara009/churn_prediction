# churn

Proyecto para análisis y modelado de churn.

## Estructura

- `src/` - código fuente del proyecto
- `notebooks/` - notebooks exploratorios y experimentos
- `models/` - artefactos de modelos (pesos, pickles)
- `.venv/` - entorno virtual (no incluir en VCS)
- `requirements.txt` - dependencias del proyecto

## Setup (Windows)

1. Crear el entorno virtual:

```powershell
python -m venv .venv
```

2. Activar el entorno (PowerShell):

```powershell
# Permite ejecutar el script solo en esta sesión
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
& ".\.venv\Scripts\Activate.ps1"
```

O en `cmd.exe`:

```cmd
.venv\Scripts\activate.bat
```

3. Instalar dependencias:

```bash
pip install -r requirements.txt
```

## Ejecutar ejemplo rápido

Con el entorno activado:

```powershell
python prueba.py
```

## Buenas prácticas

- Añadir `.venv/` a `.gitignore`.
- Mantener `requirements.txt` actualizado con `pip freeze > requirements.txt` cuando sea necesario.
- Guardar resultados de modelos en `models/`.

---

Si quieres, puedo:
- mover `prueba.py` a `src/` ahora,
- crear `.gitignore` con `.venv/` y otros ignores comunes,
- o añadir un `__init__.py` en `src/`.
