# OCR TO CSV SPECIFICATION
## 1. OBJETIVO
El sistema debe procesar imàgenes utilizando OCR para extraer texto y exportar resultados a archivos CSV.

------

# 2. Alcance MVP
El MVP debe:
- Leer imágenes desde una carpeta local
- Detectar texto usando OCR
- Exportar resultados a CSV
- Procesar múltiples imágenes automáticamente
- Manejar errores sin detener el proceso


------

# 3. Entradas

## Carpeta de Entrada
'''text

'''

## Project Structucture

image-to-csv_specs/
│
├── specs/
│   │
│   ├── README.md
│   │
│   ├── ocr_to_csv/
│   │   │
│   │   ├── functional/
│   │   │   ├── ocr_to_csv.spec.md
│   │   │   ├── use_cases.md
│   │   │   ├── business_rules.md
│   │   │   └── glossary.md
│   │   │
│   │   ├── technical/
│   │   │   ├── architecture.md
│   │   │   ├── components.md
│   │   │   ├── dependencies.md
│   │   │   └── decisions.md
│   │   │
│   │   ├── tests/
│   │   │   ├── acceptance_criteria.md
│   │   │   ├── edge_cases.md
│   │   │   └── test_scenarios.md
│   │   │
│   │   └── roadmap/
│   │       ├── mvp.md
│   │       ├── v2.md
│   │       └── technical_debt.md
│
├── tasks/
│   │
│   ├── backlog/
│   │   ├── TASK-001-create-project-structure.md
│   │   ├── TASK-002-implement-easyocr-service.md
│   │   └── TASK-003-export-csv.md
│   │
│   ├── in_progress/
│   │
│   ├── review/
│   │
│   ├── done/
│   │
│   └── templates/
│       ├── task.template.md
│       └── bug.template.md
│
├── app/
│   ├── domain/
│   ├── application/
│   ├── infrastructure/
│   ├── interfaces/
│   └── main.py
│
├── tests/
│
├── docs/
│
├── scripts/
│
├── requirements.txt
├── README.md
└── .gitignore