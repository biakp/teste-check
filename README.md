# Personalizações do Tema Dawn - Teste Técnico para Check Commerce

Este repositório contém minha submissão do teste técnico para a posição de **Desenvolvedora Front-end (Shopify)** na Check Commerce. O projeto demonstra personalizações práticas e melhorias no tema **Dawn** do Shopify.

---

## Visão Geral

Este teste demonstra minha capacidade de personalizar temas, implementar funcionalidades responsivas e identificar melhorias de performance em um contexto Shopify.

---

## Branch de Desenvolvimento

Todas as alterações descritas neste teste técnico estão disponíveis no branch **`develop`** deste repositório. Recomenda-se utilizar este branch para revisar ou testar as customizações implementadas.

---

## Tarefas Realizadas

### 1. Suporte a Vídeo na Seção Imagem com Texto

Adicionei funcionalidade para exibir vídeos na seção **Imagem com Texto**, com os seguintes recursos:

- **Seleção do Tipo de Mídia:** Configuração para alternar entre imagem e vídeo
- **Vídeos Nativos do Shopify:** Suporte a vídeos enviados para a biblioteca de mídia do Shopify
- **Autoplay:** Vídeos reproduzem automaticamente quando visíveis na tela
- **Lazy Loading:** Abordagem complementar usando o atributo `preload="none"` e `loading="lazy"` para melhor performance, mesmo que o `loading="lazy"` ainda não seja suportado em todos os navegadores para vídeos, o `preload="none"` é uma alternativa melhor para performance atualmente porém manter os dois garante maior compatibilidade futura
- **Design Responsivo:** O vídeo mantém a proporção correta em todos os dispositivos
- **Opções de Customização:** Controles para loop do vídeo e exibição/ocultação de controles

**Destaques Técnicos:**

- Uso do elemento HTML5 `video` com atributos de acessibilidade adequados
- Mantida a mesma estrutura do container para consistência visual
- CSS adicionado para garantir exibição correta e proporção do vídeo
- Preservadas as animações existentes para imagens

---

### 2. Suporte a Imagem Mobile no Slideshow

Melhorei a seção **Slideshow** para suportar imagens dedicadas para dispositivos móveis em cada slide:

- **Seleção de Imagem Separada:** Adicionado um seletor de imagem mobile no editor de tema
- **Exibição Responsiva:** Alterna automaticamente entre imagens desktop e mobile com base no tamanho da tela
- **Fallback Elegante:** Usa a imagem desktop quando a mobile não é fornecida e vice-versa

**Destaques Técnicos:**

- Implementado usando o elemento HTML5 `<picture>` com `<source>` para seleção de imagem responsiva
- CSS adicionado para garantir exibição correta em todos os dispositivos
- Mantida toda a funcionalidade existente do slideshow enquanto adiciona otimização para mobile

---

### 3. Recomendação de Performance

- **Problema Identificado:** O tema Dawn inclui muitos arquivos (CSS, JS e seções) que provavelmente nunca serão utilizados pela loja, aumentando o tamanho do tema sem necessidade.
- **Solução Proposta:** Remover arquivos e seções não utilizadas para reduzir o payload do tema.
- **Exemplo de Implementação:** Criar um branch de limpeza do tema que exclua arquivos desnecessários.
- **Impacto Estimado:** Redução do tamanho total do tema, melhora no tempo de carregamento e menor consumo de recursos em dispositivos móveis ou redes lentas.

---

## Abordagem de Desenvolvimento

- **HTML-first:** Seguindo a filosofia de JavaScript somente quando necessário
- **Enhancement Progressivo:** Funcionalidade funciona em todos os navegadores, com melhorias onde suportado
- **Design Responsivo:** Testes em múltiplos dispositivos e tamanhos de tela
- **Acessibilidade:** Manutenção de atributos ARIA e suporte à navegação por teclado
- **Qualidade de Código:** Seguindo padrões e boas práticas do Shopify
- **Performance:** Considerando impacto de performance em todas as alterações

---

## Agradecimento

Gostaria de agradecer à equipe da **Check Commerce** pela oportunidade de participar deste processo seletivo e pelo tempo dedicado à avaliação do meu teste técnico.  

Foi uma experiência muito enriquecedora e espero que as personalizações apresentadas demonstrem minha capacidade de contribuir para a melhoria da experiência do usuário e a performance dos projetos Shopify da empresa.  

Agradeço desde já pelo feedback e pela consideração.  

Atenciosamente,  
**Beatriz Knabben**
