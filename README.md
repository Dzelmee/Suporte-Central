# nexo.support — Central de suporte

Neste projeto, trabalhei com um problema comum em atendimento: quando as solicitações ficam espalhadas, acompanhar o que já foi registrado se torna difícil. A proposta do nexo.support é reunir esse fluxo em uma interface simples de consultar.

## Funcionalidades

- Criar, localizar, editar e excluir registros de atendimento.
- Validar os dados no servidor antes de salvar.
- Consultar indicadores gerados a partir dos registros existentes.
- Usar a interface no celular ou no desktop, com tema claro/escuro e suporte a movimento reduzido.

## Como executar

```bash
npm test
npm start
```

O servidor inicia em `http://localhost:3000`. Para usar outra porta, configure `PORT`.

## Tecnologias e armazenamento

Usei HTML, CSS e JavaScript com ES Modules no front-end. O servidor é feito em Node.js, usando o módulo HTTP nativo. Os registros ficam em um arquivo JSON local.

## Limitações

Esta é uma aplicação de demonstração, não um serviço pronto para produção. Ainda não há autenticação, permissões por usuário nem banco de dados de produção. O armazenamento em JSON também não foi pensado para várias instâncias simultâneas.

## Imagens

Fotografias utilizadas do [Unsplash](https://unsplash.com/license):
- https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=1600&q=85
- https://images.unsplash.com/photo-1531482615713-2afd69097998?auto=format&fit=crop&w=1100&q=85
