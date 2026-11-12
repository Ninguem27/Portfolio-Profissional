# Reginaldo Lopes Imóveis

[← Voltar ao portfólio](../README.md)

**Categoria:** sistema imobiliário com site público e painel administrativo  
**Atuação:** desenvolvimento Full Stack  
**Tecnologias:** PHP, MySQL, HTML, CSS e JavaScript

## Problema

O corretor precisava apresentar os imóveis aos interessados e gerenciar cadastros, mídias, proprietários e contatos em um único sistema.

## Solução

O projeto combina catálogo público com painel administrativo. A organização das funções permite atualizar os anúncios e acompanhar informações comerciais sem editar as páginas manualmente.

## Funcionalidades do projeto

- Catálogo de imóveis, busca, filtros e páginas individuais.
- Gestão de imóveis, categorias, proprietários e notas internas.
- Organização de fotos e vídeos.
- Controle de publicação, rascunhos, vendidos e lixeira.
- Recebimento de propostas e acompanhamento no painel.
- Agenda de compromissos e fluxo de integração com Google Agenda.
- Configuração de SEO e materiais de ajuda ao administrador.
- Recursos para integração com portais imobiliários.

## Decisões técnicas

| Camada | Responsabilidade |
| --- | --- |
| HTML, CSS e JavaScript | Catálogo, galeria, navegação e interações |
| PHP | Processamento dos formulários e regras do painel |
| MySQL | Persistência de cadastros e relacionamentos |
| Google Calendar API | Sincronização após configuração e autorização OAuth |

## Evolução recente

O pacote de 12/11/2026 inclui revisão do registro de duplicações, documentação do painel e integração da agenda. A conexão automática ao Google depende da configuração OAuth, da autorização do titular e de validação no ambiente de hospedagem.

A revisão descrita no guia do pacote foi estática e parcialmente local; não equivale a homologação com o banco real ou com a conta Google do cliente.

## Desafios

Preservar os dados existentes durante atualizações, distinguir rascunhos de anúncios publicados e organizar recursos administrativos para uso no celular.

## Disponibilidade

[Visitar o site](https://reginaldolopescorretor.com)

O código é mantido em repositório privado. Dados de clientes, credenciais e arquivos operacionais não fazem parte desta apresentação.
