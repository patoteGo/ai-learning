# Construindo e Implantando um Agente de Voz com IA para Educação
https://www.youtube.com/watch?v=oE7bVYRFYrU&t=488s&ab_channel=TubeGuruji

Este guia apresenta todas as etapas para criar e implantar um assistente de voz com inteligência artificial, conforme demonstrado no vídeo do canal TubeGuruji.

---

## 🛠️ Serviços e Ferramentas Utilizadas

1. **Next.js**  
   - Site: [https://nextjs.org/](https://nextjs.org/)  
   - Função: Framework React para renderização no lado do servidor e geração de sites estáticos.

2. **React**  
   - Site: [https://reactjs.org/](https://reactjs.org/)  
   - Função: Biblioteca para construção de interfaces de usuário.

3. **Tailwind CSS**  
   - Site: [https://tailwindcss.com/](https://tailwindcss.com/)  
   - Função: Framework CSS utilitário para estilização rápida.

4. **Convex**  
   - Site: [https://convex.dev/](https://convex.dev/)  
   - Função: Backend-as-a-service para banco de dados e funções de backend.

5. **AssemblyAI**  
   - Site: [https://www.assemblyai.com/](https://www.assemblyai.com/)  
   - Função: API de transcrição de áudio em texto.

---

## 👨‍🍳 Passo a Passo (como uma receita de cozinha)

### 1. Configurar o Ambiente de Desenvolvimento

🕒 Tempo estimado: 15 minutos  
📦 Necessário:
- Node.js
- Editor de código (como Visual Studio Code)

📋 Instruções:
- Instale o [Node.js](https://nodejs.org/)
- Instale o [VS Code](https://code.visualstudio.com/)

---

### 2. Iniciar um Projeto Next.js

🕒 Tempo estimado: 10 minutos  
📋 Instruções:
```bash
npx create-next-app@latest nome-do-projeto
cd nome-do-projeto
```

### 3.
3. Instalar e Configurar o Tailwind CSS
🕒 Tempo estimado: 15 minutos
📋 Instruções:

Siga o guia oficial: https://tailwindcss.com/docs/guides/nextjs

4. Integrar o Convex para Funções de Backend
🕒 Tempo estimado: 20 minutos
📦 Necessário:

Conta no Convex

📋 Instruções:

Cadastre-se em https://convex.dev/

Crie um novo projeto

Siga o guia para integração com Next.js

5. Integrar o AssemblyAI para Reconhecimento de Voz
🕒 Tempo estimado: 20 minutos
📦 Necessário:

Conta no AssemblyAI

Chave de API

📋 Instruções:

Cadastre-se em https://www.assemblyai.com/

Pegue sua chave de API

bash
Copy
Edit
npm install assemblyai
Configure o SDK no seu projeto

6. Desenvolver a Aplicação
🕒 Tempo estimado: 2-3 horas
📦 Necessário:

Protótipos ou design (opcional)

📋 Instruções:

Construa os componentes de UI com React + Tailwind CSS

Utilize Convex para lógica e banco de dados

Integre AssemblyAI para transcrição de voz

Teste localmente com:

bash
Copy
Edit
npm run dev
7. Implantar a Aplicação
🕒 Tempo estimado: 30 minutos
📦 Necessário:

Conta no Vercel (ou Netlify, etc.)

📋 Instruções:

Conecte seu repositório no Vercel

Configure variáveis de ambiente

Implante e teste a aplicação ao vivo

⏱️ Tempo Total Estimado: 4 a 5 horas
✅ Parabéns! Ao seguir este guia, você terá um assistente de voz com IA funcional, voltado para uso educacional, rodando na web. 🎉
