# 🌸 Ciclo Certo — Site Oficial & Política de Privacidade

Site institucional e documentação legal do aplicativo **Ciclo Certo: Lembrete** (`com.ciclocerto.app`).

Pronto para publicação via **GitHub Pages** no repositório:
👉 `https://github.com/alefdias/CicloCerto.git`

---

## 📋 URL para cadastrar no Google Play Console

Após ativar o GitHub Pages, use uma das seguintes URLs no campo **"Política de Privacidade"** do Google Play Console:

- **URL Recomendada:**  
  `https://alefdias.github.io/CicloCerto/privacidade.html`
- **URL Alternativa / Espelho:**  
  `https://alefdias.github.io/CicloCerto/privacy.html`
- **Página Inicial:**  
  `https://alefdias.github.io/CicloCerto/`

---

## 🚀 Como Publicar no seu Repositório GitHub

Execute os seguintes comandos dentro da pasta `Ciclocertoweb`:

```bash
cd /home/alef/Documentos/Velix-Med/Ciclocertoweb

# 1. Inicializar o repositório git (caso ainda não esteja inicializado)
git init -b main

# 2. Adicionar todos os arquivos
git add .

# 3. Criar o commit inicial
git commit -m "feat: site oficial Ciclo Certo com Politica de Privacidade para Play Store"

# 4. Vincular ao seu repositório dedicado
git remote add origin https://github.com/alefdias/CicloCerto.git

# 5. Enviar para o GitHub
git push -u origin main --force
```

---

## ⚙️ Ativar o GitHub Pages no Repositório

1. Abra o repositório no navegador: [github.com/alefdias/CicloCerto](https://github.com/alefdias/CicloCerto)
2. Vá em **Settings** (Configurações) > **Pages** (no menu lateral esquerdo).
3. Na seção **Build and deployment**:
   - **Source:** Selecione `Deploy from a branch`
   - **Branch:** Selecione `main` / pasta `/ (root)`
4. Clique em **Save**.
5. Aguarde cerca de 1 a 2 minutos. Seu site estará no ar em:  
   `https://alefdias.github.io/CicloCerto/`

---

## 📂 Arquivos Inclusos

- `index.html`: Landing page moderna com apresentação do app, mockups e destaque para a política de privacidade.
- `privacidade.html`: Política de Privacidade detalhada e em conformidade com Google Play Console e LGPD.
- `privacy.html`: Espelho/alias da política para evitar qualquer erro de digitação de URL.
- `termos.html`: Termos de Uso com isenção de responsabilidade médica (*Health Disclaimer*).
- `style.css`: Design responsivo com efeitos de vidro (*glassmorphism*), paleta moderna e tipografia profissional.
- `assets/`: Ícone oficial (512x512), banner e screenshots da interface.
- `.nojekyll`: Garante que o GitHub Pages sirva todos os arquivos estáticos sem pré-processamento.
