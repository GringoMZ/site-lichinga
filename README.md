cd site_lichinga_signed
npm install

import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

export default defineConfig({
  plugins: [react()],
  base: "/site-lichinga/",   // <-- nome do seu repositório no GitHub
})
npm run build
git init
git remote add origin https://github.com/SEU-USUARIO/site-lichinga.git
git add .
git commit -m "primeira versão do site de Lichinga"
git push -u origin main
