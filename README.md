# Descrição

Design System é uma documentação dos layouts, das padronizações que seguimos em nossa empresa.
É qualquer componente visual que pode ser compartilhado entre qualquer aplicação da empresa.
Não é uma biblioteca de UI Components ou UI Kits!!

O conceito de DS é incluirmos dentro dele somente elementos visuais nos quais eles podem ser reaproveitados em qualquer aplicação da nossa empresa.

A ideia é que o DS seja:

- Componentes reutilizáveis em diversas aplicações com regras de negócio totalmente diferentes. Ex: reaproveitar um mesmo tipo de botão
- Agnóstico de tecnologia.
- Os componentes visuais quando falamos em DS, são chamados de "Tokens", no qual se refere a elementos básicos e reutilizáveis que definem as características visuais e funcionais de um sistema de design.
- Tokens podem ser fácilmente compartilhados entre todos os projetos.
- Criar um pacote isolado somente para os tokens.

Tokens:

- Cores
- Fontes
- Componentes Visuais

# Components

- [ ] Text
- [ ] Heading
- [ ] Box
- [ ] Button
- [ ] TextInput
- [ ] TextArea
- [ ] Checkbox
- [ ] Avatar
- [ ] MultiStep

# Bibliotecas de terceiros

- TSUP:
  É uma ferramenta para fazermos o processo de conversão de nosso código para um pacote JavaScript que poderá ser
  carregado por outras aplicações. O TSUP consegue converter nosso código para vários formatos diferentes, converte
  pra CommonJS e ECMAScript Modules, para que ele possa ser utilizado por aplicações mais recentes e aplicações mais
  antigas. Também é muito mais performático que utilizar o tsc de forma nativa.
