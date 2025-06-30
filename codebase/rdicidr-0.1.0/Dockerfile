FROM node:18-alpine

WORKDIR /app

# Copia apenas os artefatos já prontos do build (ajuste conforme sua pipeline)
COPY . .

# Exponha a porta se necessário (exemplo: 3000)
# EXPOSE 3000

# Ajuste o comando de inicialização conforme seu projeto
CMD ["node", "src/index.js"]