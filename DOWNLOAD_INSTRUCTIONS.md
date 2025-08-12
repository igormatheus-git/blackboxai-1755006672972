# 📥 MindFlow - Instruções de Download e Instalação

## 📦 Arquivo Disponível para Download

**Arquivo:** `mindflow-app.zip` (179KB)  
**Criado em:** 12 de agosto de 2025  
**Conteúdo:** Projeto completo do aplicativo MindFlow

## 📋 O que está incluído no ZIP:

### 🗂️ Estrutura do Projeto
```
mindflow-app/
├── src/
│   ├── app/                    # Páginas Next.js
│   │   ├── api/               # Endpoints da API
│   │   ├── assessment/        # Página de avaliação
│   │   ├── challenges/        # Página de desafios
│   │   ├── emotional-map/     # Página do mapa emocional
│   │   ├── reflection/        # Página de reflexões
│   │   ├── social-simulator/  # Página do simulador social
│   │   ├── sos/              # Página SOS
│   │   ├── globals.css       # Estilos globais
│   │   ├── layout.tsx        # Layout principal
│   │   └── page.tsx          # Página inicial
│   ├── components/ui/         # Componentes shadcn/ui
│   ├── context/              # Context API
│   ├── hooks/                # Hooks customizados
│   ├── lib/                  # Utilitários e simuladores
│   ├── navigation/           # Componentes de navegação
│   └── screens/              # Telas principais
├── public/                   # Arquivos públicos
├── package.json             # Dependências
├── README.md               # Documentação completa
├── TODO.md                 # Status do projeto
└── Arquivos de configuração
```

### 🚀 Funcionalidades Incluídas
- ✅ **7 Telas Principais** totalmente funcionais
- ✅ **APIs Simuladas** para IA e dados do usuário
- ✅ **Sistema de Gamificação** completo
- ✅ **Simulador Social com IA** funcional
- ✅ **Técnicas SOS** para emergências
- ✅ **Design Responsivo** mobile-first
- ✅ **Documentação Completa**

## 🛠️ Como Instalar e Executar

### 1. **Extrair o Arquivo**
```bash
unzip mindflow-app.zip
cd mindflow-app
```

### 2. **Instalar Dependências**
```bash
npm install
# ou
yarn install
# ou
pnpm install
```

### 3. **Executar o Projeto**
```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
```

### 4. **Acessar a Aplicação**
Abra seu navegador em: **http://localhost:3000**

## 📱 Testando as Funcionalidades

### 🏠 **Tela Inicial**
- Dashboard emocional com dados simulados
- Sinais vitais de wearables
- Progresso e gamificação

### 📊 **Autoavaliação**
- Questionário com 6 perguntas
- Sliders interativos
- Salvamento automático

### 🎯 **Desafios Diários**
- Sistema de pontos
- Categorias variadas
- Instruções detalhadas

### 📈 **Mapa Emocional**
- Gráficos de histórico
- Análise de tendências
- Estatísticas detalhadas

### 🧘 **Reflexões Guiadas**
- Exercícios estruturados
- Timer integrado
- Salvamento de reflexões

### 🤖 **Simulador Social**
- Cenários realistas
- IA conversacional
- Feedback personalizado

### 🆘 **Modo SOS**
- Técnicas de emergência
- Recursos de apoio
- Interface calmante

## 🧪 Testando as APIs

### Teste da IA:
```bash
curl -X POST http://localhost:3000/api/simulation/ai \
  -H "Content-Type: application/json" \
  -d '{"message": "Estou me sentindo ansioso"}'
```

### Teste de Dados:
```bash
curl -X POST http://localhost:3000/api/userData \
  -H "Content-Type: application/json" \
  -d '{"mood": 7, "energy": 6, "stress": 4}'
```

## 📋 Requisitos do Sistema

- **Node.js** 18+ 
- **npm/yarn/pnpm** 
- **Navegador moderno** (Chrome, Firefox, Safari, Edge)

## 🎨 Características do Design

- **Paleta suave:** Azuis, verdes e beiges
- **Tipografia:** Inter (Google Fonts)
- **Mobile-first:** Otimizado para dispositivos móveis
- **Acessível:** Seguindo padrões de acessibilidade
- **Minimalista:** Interface limpa sem ícones externos

## 📞 Suporte

Se encontrar algum problema:
1. Verifique se todas as dependências foram instaladas
2. Certifique-se de que está usando Node.js 18+
3. Consulte o README.md para documentação completa
4. Verifique os logs do terminal para erros específicos

## 🎉 Projeto Completo!

O MindFlow está **100% funcional** e pronto para uso. Todas as funcionalidades foram testadas e estão operacionais. Aproveite explorando este aplicativo inovador de independência emocional!

---
**MindFlow** - Desenvolvendo independência emocional através da tecnologia 🧠💙
