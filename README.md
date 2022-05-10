## PARTE 1 - CONFIGURANDO SERVIDOR

**A sua tarefa consiste em configurar um servidor baseado na nuvem e instalar e configurar alguns componentes básicos.**

1. Configurar um servidor AWS (recomenda-se o freetier) executando uma versão Ubuntu LTS.
2. Instalar e configurar qualquer software que você recomendaria em uma configuração de servidor padrão sob as perspectivas de segurança, desempenho, backup e monitorização.
3. Instalar e configurar o nginx para servir uma página web HTML estática.
4. Utilizar ferramentas de automatização como Ansible, Terraform ou AWS Cloudformation.

## PARTE 2 - SCRIPT

<p align="justify">Utilizando uma linguagem de script à sua escolha, construa um projeto (servido através do nginx) que possa relatar estatísticas operacionais básicas sob a forma de um objeto JSON.</p>

- As estatísticas devem incluir (como mínimo):
  - Carga actual da CPU, tempo de espera e utilização de memória (opcionalmente reportado como slab, cache, RSS, etc.)
  - Se existem actualizações pendentes (opcionalmente, reportando actualizações de segurança independentemente)
  - Utilização actual do disco e desempenho de leitura/escrita

<p align="justify">O resultado final pode incluir quaisquer outras estatísticas que considere importantes para efeitos de monitorização do servidor. Você pode considerar a possibilidade de construir o script em cima do projeto dstat.</p>

<p align="justify">O seu código deve ser entregue a um repositório Git que demonstram uma compreensão de conceitos tais como ramificação de branchs e merges requests.</p>

## PARTE 3 - CD


<p align="justify">Desenhar e construir uma pipeline para apoiar a entrega contínua da aplicação de monitorização construída na Parte 2 no servidor configurado na Parte 1. Descrever a pipeline utilizando um diagrama de fluxo e explicar o objetivo e o processo de seleção usado em cada uma das ferramentas e técnicas específicas que compõem a sua pipeline.</p>

## O QUE DEVE CONTER NO README?

- Deve conter o título do projeto
- Uma descrição sobre o projeto em frase
- Deve conter uma lista com linguagem, framework e/ou tecnologias usadas
- Como instalar e usar o projeto (instruções)
- Não esqueça o .gitignore
