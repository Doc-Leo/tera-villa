# tera-villa

play ground

### Dependencies
A Node.js + TypeScript + Express project.

```bash
npm install
npm run dev
npm start



tera-villa/
│── .gitignore
│── package.json
│── tsconfig.json
│── nodemon.json
│── README.md
│
├── src/
│   ├── public/            # Static files (served directly)
│   │   ├── index.html
│   │   ├── css/
│   │   │   └── styles.css
│   │   ├── js/
│   │   │   └── app.js
│   │   └── assets/        # images, icons, etc.
│   │
│   ├── server/            # Backend code (TypeScript)
│   │   ├── index.ts       # Entry point (creates Express app)
│   │   ├── routes/        # API routes
│   │   │   └── home.ts
│   │   ├── controllers/   # Route logic
│   │   │   └── homeController.ts
│   │   ├── middleware/
│   │   ├── services/
│   │   └── utils/         # Helpers/utilities
│   │       └── config/    # Config files
│   │           └── appConfig.ts
│   │
│   └── dist/              # Compiled JavaScript (after tsc)
│
└── public/
    └── server/
