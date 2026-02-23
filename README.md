# introducao-ao-typescript-tipagem-de-variaveis-funcoes-e-tipos-customizados-aula-19-02-2026

Concluí com sucesso o exercício de TypeScript conforme solicitado. Abaixo estão os detalhes do que foi realizado:
  
  Configuração do Ambiente: Instalei o TypeScript globalmente e criei a pasta do projeto exercicio-typescript.
  Configuração do Projeto: Inicializei o projeto com tsc --init e configurei o arquivo tsconfig.json com as opções target: ES6, strict: true e outDir: ./dist.
  Desenvolvimento: Criei o arquivo index.ts contendo a definição do tipo Produto, o array de produtos, a função de formatação exibirProduto e o loop de exibição.
  Compilação e Execução: Compilei o código usando o comando tsc, que gerou o arquivo index.js na pasta dist/, e executei o resultado com node dist/index.js.

Resultado da Execução no Terminal:

              === Catálogo de Produtos ===
[Eletrônicos]: # "iPhone 15 - R$ 5.999,00 ✅ disponível"
[Eletrônicos]: # "Cabo HDMI - R$ 39,90 ❌ indisponível"
[Esportes]: # "Tênis Running Pro - R$ 349,90 ✅ disponível"
[Acessórios]: # "Mochila Urbana - R$ 189,90 ❌ indisponível"
[Eletrônicos]: # "Fone Bluetooth - R$ 229,90 ✅ disponível"
