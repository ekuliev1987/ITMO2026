# Python Libraries

Список необходимых библиотек Python.

## Основные библиотеки

```bash
# Deep Learning
torch>=2.0.0
torchvision>=0.15.0
keras>=3.0.0

# NLP и LLM
transformers>=4.35.0
datasets>=2.14.0
accelerate>=0.24.0
peft>=0.6.0

# RAG и Agents
langchain>=0.0.350
chromadb>=0.4.0
faiss-cpu>=1.7.0

# Диффузионные модели
diffusers>=0.24.0

# Работа с данными
numpy>=1.24.0
pandas>=2.0.0
scikit-learn>=1.3.0

# Визуализация
matplotlib>=3.7.0
seaborn>=0.12.0
plotly>=5.17.0

# Deployment
fastapi>=0.104.0
uvicorn>=0.24.0
python-multipart>=0.0.6
pydantic>=2.0.0
docker>=6.1.0

# Мониторинг
prometheus-client>=0.19.0
redis>=5.0.0
```

## Установка

```bash
pip install -r requirements.txt
```

## Альтернативы

- **GPU:** `torch` с CUDA поддержкой
- **Windows:** использовать WSL2 или Docker
