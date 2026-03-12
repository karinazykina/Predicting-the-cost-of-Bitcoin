

## Установка

**Для Ubuntu / Debian:**
```bash
# Обязательные системные зависимости
sudo apt update
sudo apt install -y graphviz libgraphviz-dev pkg-config python3-dev

# Дальше в виртуальном окружении
python -m venv .venv
source .venv/bin/activate
pip install pygraphviz
pip install -r requirements.txt
```
