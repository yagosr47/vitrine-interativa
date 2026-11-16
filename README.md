# Vitrine Interativa

Template demonstrativo para negócios locais, desenvolvido com React, TypeScript, Tailwind CSS e Vite.

## Executar

```sh
npm install
npm run dev
```

## Compilar

```sh
npm run build
```

## Personalizar

Os quatro estabelecimentos, suas cores, textos, imagens e produtos estão em `src/presets.ts`.
O número de WhatsApp é fictício e pode ser substituído na função `wa` em `src/main.tsx`. Todos os nomes, preços, endereços e avaliações são ilustrativos.

As imagens usam URLs do Unsplash e precisam de conexão à internet. Uploads de teste ficam apenas no estado do React usando object URLs; não há banco de dados nem armazenamento local. Resetar alterações restaura as imagens dos quatro temas. As URLs temporárias são liberadas ao substituir imagens, resetar ou desmontar a aplicação.
