# Building and Deploying an AI Voice Agent for Education
https://www.youtube.com/watch?v=oE7bVYRFYrU&t=488s&ab_channel=TubeGuruji

This guide walks through all the steps to create and deploy an AI-powered voice assistant, as demonstrated in the video by the TubeGuruji channel.
---

## 🛠️ Services and Tools Used

1. **Next.js**  
   - Website: [https://nextjs.org/](https://nextjs.org/)  
   - Purpose: React framework for server-side rendering and static site generation.

2. **React**  
   - Website: [https://reactjs.org/](https://reactjs.org/)  
   - Purpose: Library for building user interfaces.

3. **Tailwind CSS**  
   - Website: [https://tailwindcss.com/](https://tailwindcss.com/)  
   - Purpose: Utility-first CSS framework for rapid styling.

4. **Convex**  
   - Website: [https://convex.dev/](https://convex.dev/)  
   - Purpose: Backend-as-a-service for database and backend functions.

5. **AssemblyAI**  
   - Website: [https://www.assemblyai.com/](https://www.assemblyai.com/)  
   - Purpose: Audio-to-text transcription API.

---

## 👨‍🍳 Step-by-Step Guide (like a recipe)

### 1. Set Up the Development Environment

🕒 Estimated time: 15 minutes
📦 Requirements:
- Node.js
- Editor de código (como Visual Studio Code)

📋 Instructions:
- Install [Node.js](https://nodejs.org/)
- Install [VS Code](https://code.visualstudio.com/)

---

### 2. Start a Next.js Project

🕒 Estimated time: 5 minutes
📋 Instructions:
```bash
npx create-next-app@latest nome-do-projeto
cd nome-do-projeto
```

- with Tailwind
- with Typescript

### 3. Install Shadcn
🕒 Estimated time: 5 minutes
📋 Instructions:

Oficial guide: https://ui.shadcn.com/docs/installation/next

```bash
npm dlx shadcn@latest init
```

create a simple button
```bash
npx shadcn@latest add button
```

Test a simple button
```js
import { Button } from "@/components/ui/button"

export default function Home() {
  return (
    <div>
      <Button>Click me</Button>
    </div>
  )
}
```

4. Install stack-auth authetication system
https://docs.stack-auth.com/next/overview

🕒 Estimated time: 5 minutes
📦 Requirement:
- Create an account

install
```bash
npx @stackframe/init-stack@latest
```

when you create the project will give keys

add local env
```
NEXT_PUBLIC_STACK_PROJECT_ID=<your-project-id>
NEXT_PUBLIC_STACK_PUBLISHABLE_CLIENT_KEY=<your-publishable-client-key>
STACK_SECRET_SERVER_KEY=<your-secret-server-key>
```



5. Add Convex to the backend
🕒 Estimated time: 5 minutes
📦 Requirement:
- Create an account

📋 Instructions:

Cadastre-se em https://convex.dev/

Create a new project

Follow the guide to install in nextJS
https://docs.convex.dev/quickstart/nextjs

6. add AssemblyAI for voice recognition
🕒 Estimated time: 20 minutos
📦 Requirement:

Conta no AssemblyAI

Chave de API

📋 Instructions:

signup in https://www.assemblyai.com/

Pegue sua chave de API

```bash
npm install assemblyai
```

configure SDK for your project

7. Develop the App

🕒 Estimated time: 2-3 hours

in this part you can start add the screen need it for the app

### Dashboard
![image](https://github.com/user-attachments/assets/06301e92-6ff5-4090-8660-cecde60397e9)

### Ai input dialog
![image](https://github.com/user-attachments/assets/555f1ca7-92e8-484e-ae8b-6b157cab39dd)

### Discussion room
![image](https://github.com/user-attachments/assets/ad8c5e90-77a1-4dcf-b2fd-a245c3ac4502)


📋 Instructions:

Build the components with tailwind css , shadcn and React
use the logic of convex for the database

Integrate AssemblyAI for the transcription of voice


7. Publish the App

🕒 Tempo estimado: 50 minutos
📦 Necessário:

Conta no Vercel (ou Netlify, etc.)

📋 Instruções:

Conecte seu repositório no Vercel

Configure variáveis de ambiente

Implante e teste a aplicação ao vivo

⏱️ Tempo Total Estimado: 4 a 5 horas
✅ Parabéns! Ao seguir este guia, você terá um assistente de voz com IA funcional, voltado para uso educacional, rodando na web. 🎉
