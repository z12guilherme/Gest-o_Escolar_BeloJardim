# 🎯 Gestão de Atípicos

## ✨ Descrição
**Gestão de Atípicos** é um sistema moderno para **gerenciamento de estudantes, professores e responsáveis**, construído com **React + Vite + TypeScript**.  
Ele possui dashboards dinâmicos, interface responsiva e integração completa com **Supabase** para autenticação e armazenamento de dados.

O sistema é ideal para escolas e instituições que precisam de **controle eficiente de usuários e estudantes**, com funcionalidades seguras e uma experiência intuitiva.

---

## 🚀 Funcionalidades

- 👨‍🏫 Cadastro e gerenciamento de **professores, responsáveis e estudantes**  
- 📊 Dashboards com estatísticas e relatórios em tempo real  
- 🔒 Controle de acesso baseado em **roles (gestor, professor, responsável)**  
- 🗄️ Integração com **Supabase** para backend e autenticação  
- 🎨 Interface moderna com **Tailwind CSS**  
- ✅ Consultas e operações seguras usando **RLS (Row Level Security)**  

---

## 🛠 Tecnologias Utilizadas

- **Frontend**: React, Vite, TypeScript, Tailwind CSS  
- **Backend/Database**: Supabase (PostgreSQL)  
- **UI Components**: shadcn/ui, lucide-react  
- **Gerenciamento de estado e dados**: React Query, Sonner (toasts)

---

## ⚙️ Pré-requisitos

- Node.js >= 18  
- NPM ou Yarn  
- Conta no Supabase para backend e autenticação  

---

## 💻 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
Instale as dependências:

bash
Copiar código
npm install
# ou
yarn install
Configure as variáveis de ambiente na raiz do projeto (.env):

env
Copiar código
VITE_SUPABASE_URL=YOUR_SUPABASE_URL
VITE_SUPABASE_ANON_KEY=YOUR_ANON_KEY
VITE_SUPABASE_PUBLISHABLE_KEY=YOUR_PUBLISHABLE_KEY
Atenção: Nunca use a service_role key no frontend.

Rode o projeto localmente:

bash
Copiar código
npm run dev
# ou
yarn dev
O site estará disponível em http://localhost:5173.

📦 Build para Produção
bash
Copiar código
npm run build
# ou
yarn build
Os arquivos gerados ficam na pasta dist, prontos para deploy.

🌐 Deploy
Pode ser hospedado em Netlify, Vercel ou qualquer servidor de arquivos estáticos.

Lembre-se de configurar as variáveis de ambiente no painel da plataforma.

🤝 Contribuição
Pull requests são bem-vindos!
Para mudanças grandes, abra uma issue primeiro para discutirmos.

📄 Licença
MIT License

yaml
Copiar código

---

Se você quiser, eu posso criar também uma **versão resumida de descrição** para o GitHub (aquela frase curta que aparece no topo do repositório), bem chamativa para atrair visitantes.  

Quer que eu faça isso também?
