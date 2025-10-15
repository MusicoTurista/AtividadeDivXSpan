## O que aprendemos
1. As LLMs são uma ótima fonte de auxílio no desenvolvimento de sites e aplicações.
2. Algumas LLMs apresentam focos diferentes umas das outras — o modelo **Sonnet 4.5** gera códigos mais robustos e extensos, enquanto o **GPT-5** preza pela clareza e simplicidade.
3. O uso de LLMs é de grande ajuda para o estudo de temas diversos, podendo trazer explicações, exemplos, analogias e exercícios de fixação.
4. É importante validar o código gerado, pois as LLMs podem cometer pequenos erros de sintaxe ou semântica no HTML.
5. O aprendizado prático, ao comparar saídas de diferentes modelos, reforça a compreensão dos conceitos de HTML, CSS e estrutura de páginas web.

## Diferenças entre LLMs

**GPT-5**
- Produz código limpo e bem estruturado, com indentação consistente e explicações curtas e diretas.
- Mantém o foco em boas práticas de HTML5 e CSS básico.
- Prefere soluções simples e fáceis de entender, o que facilita o aprendizado.

**Sonnet 4.5**
- Gera códigos mais longos e com detalhes avançados, incluindo comentários técnicos e estruturas adicionais.
- Tende a aplicar mais estilizações e atributos visuais.
- Às vezes insere elementos extras (como <main> ou <section>) mesmo quando o exercício pede apenas o essencial.

## Erros comuns e correções

1. Uso de `width` e `margin-top` em elementos <span> (inline).  
   Correção: trocar por <div> ou aplicar `display: inline-block` para permitir controle de tamanho e margens.

2. Esquecer o <!DOCTYPE html> no início do documento.  
   Correção: adicionar a declaração para garantir a compatibilidade com o HTML5.

3. Tags aninhadas incorretamente, como <p><div></div></p>.  
   Correção: reorganizar as tags para respeitar a hierarquia HTML.

4. Falta de fechamento de tags <head> ou <body>.  
   Correção: revisar o código gerado e adicionar os encerramentos adequados.