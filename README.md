# Revised-Project-Structure-with-AI

vehicle-tracking-system/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── services/
│   │   ├── tracking.py
│   │   ├── alerts.py
│   │   └── ai_model.py  # New AI module
│   ├── models/
│   │   └── database.py
│   ├── config.py
│   ├── utils/
│   │   └── validation.py
│   └── data/
│       └── training_data.csv  # Sample historical data
│
├── frontend/
│   ├── index.html
│   ├── static/
│   │   ├── css/
│   │   │   └── styles.css
│   │   └── js/
│   │       └── script.js
│
├── database/
│   └── init_db.py
│
├── README.md
└── .gitignore
