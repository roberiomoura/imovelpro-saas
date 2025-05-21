
# Clone o repositório
git clone https://github.com/SEU_USUARIO/imovelpro-saas.git
cd imovelpro-saas

# Crie as pastas
mkdir -p src/components src/pages src/styles public/assets

# Crie arquivos principais
touch README.md .gitignore package.json

# Adicione tudo e envie para o GitHub
git add .
git commit -m "Estrutura inicial do ImóvelPro SaaS"
git push origin main
