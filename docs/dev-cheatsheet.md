# LogicAfterMidnight Developer Cheat Sheet

*A quick reference for working on the Midnight Data Lab*

---

# 🧠 Project Structure

```
midnight-data-lab
│
├── data/          # datasets and database files
├── notebooks/     # Jupyter notebooks for exploration
├── python/        # Python scripts
├── sql/           # SQL practice and queries
├── docs/          # project documentation
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# 🐍 Python Environment

Activate the project environment:

```
cd ~/midnight-data-lab
source .venv/bin/activate
```

Deactivate when finished:

```
deactivate
```

Install packages:

```
pip install package_name
```

Save environment:

```
pip freeze > requirements.txt
```

---

# 🧪 Run Python Scripts

Example:

```
python python/analysis.py
```

Example test script:

```python
import pandas as pd

print("Pandas working")
```

---

# 📊 Jupyter Notebook

Launch notebooks:

```
jupyter notebook
```

Open browser and navigate to the `notebooks/` folder.

---

# 🗄 SQL Practice

Example SQLite workflow:

```
sqlite3 data/mydatabase.db
```

List tables:

```
.tables
```

Run query:

```sql
SELECT * FROM table_name;
```

Exit SQLite:

```
.quit
```

---

# 🌐 Git Workflow

Check changes:

```
git status
```

Add files:

```
git add .
```

Create commit:

```
git commit -m "describe update"
```

Push to GitHub:

```
git push
```

Typical workflow:

```
git add .
git commit -m "update message"
git push
```

---

# 🔒 GitHub Privacy Email

Use GitHub anonymous commit email:

```
git config --global user.email "YOURID+USERNAME@users.noreply.github.com"
```

Fix previous commit if needed:

```
git commit --amend --reset-author
```

---

# 🧰 Useful Git Commands

View commit history:

```
git log
```

Undo staged files:

```
git reset
```

Undo last commit (before push):

```
git reset --soft HEAD~1
```

---

# 🧠 Data Analysis Workflow

Typical pipeline:

1. Collect data
2. Store in database
3. Query with SQL
4. Analyze with Python + pandas
5. Visualize with graphs

Example stack:

```
SQLite → SQL → Python → Pandas → Visualization
```

---

# 🌙 Midnight Lab Motto

```
Clean inputs.
Clean outputs.
Clean mind.
```

LogicAfterMidnight
