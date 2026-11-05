# nexo.support — O suporte certo, na hora certa.

Projeto Full Stack demonstrativo, com interface própria para o segmento **support**.

## Stack
HTML5, CSS3 (Scroll-Driven Animations, layouts responsivos), JavaScript ES Modules, Node.js (HTTP nativo), JSON local.

## Executar
```bash
npm test
npm start
```
Acesse http://localhost:3000. Configure `PORT` para mudar a porta.

## Funcionalidades
- Operações CRUD com persistência em arquivo JSON e validação no servidor.
- Busca, formulários em diálogo nativo, métricas calculadas a partir dos registros.
- Tema claro/escuro salvo no navegador, parallax e animações progressivas (com redução de movimento).
- Layout específico do produto e seções editoriais com fotografias externas.
- Indicadores por tipo de registro.

## Limitações
Projeto de portfólio: sem autenticação, multiusuários, pagamentos reais ou banco de dados de produção. Fotografias remotas precisam de conexão à internet. Estatísticas exibidas são calculadas a partir dos dados salvos e começam zeradas. A checagem de conflito de agenda na interface não é garantia de exclusividade sob concorrência no servidor.

## Fotos e licença
Imagens remotas hospedadas no Unsplash (https://unsplash.com/license). Conferir direitos de pessoas, marcas e condições atuais antes de uso comercial. URLs: https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=1600&q=85, https://images.unsplash.com/photo-1531482615713-2afd69097998?auto=format&fit=crop&w=1100&q=85.
