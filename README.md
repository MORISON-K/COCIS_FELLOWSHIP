# COCIS Fellowship Website

## 🛠 Tech Stack

### Design
| Tool | Purpose |
|------|---------|
| Figma | UI/UX Design & Prototyping |
| Stitch | Design Handoff |

### Frontend
| Tool | Purpose |
|------|---------|
| React + Vite | UI Framework & Build Tool |
| TypeScript | Type-safe JavaScript |
| Tailwind CSS | Utility-first Styling |

### Backend
| Tool | Purpose |
|------|---------|
| Django | Backend Logic |
| PostgreSQL | Relational Database |

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- Python (v3.10+)
- PostgreSQL

### Frontend Setup

```bash
# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Backend Setup

```bash
# Navigate to the backend directory
cd backend

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

---

## 📁 Project Structure

```
cocis-fellowship/
├── frontend/          # React + Vite + TypeScript app
│   ├── src/
│   ├── public/
│   └── ...
├── backend/           # Django app
│   ├── manage.py
│   ├── requirements.txt
│   └── ...
└── README.md
```

---

## 🤝 Contributing

1. Clone the repository
2. Create a branch (`git checkout -b "branch_name"`)
3. Commit your changes (`git commit -m 'Add a descriptive message here'`)
4. Push to the branch (`git push origin branch_name `)
5. Open a Pull Request for your changes to reviewed and approved

