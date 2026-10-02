# BlockObra

Plataforma SaaS para o Relatório Diário de Obra (RDO). A contratada preenche e assina, a fiscalização analisa e aprova, e cada versão fica registrada de forma imutável e verificável por qualquer pessoa.

**Site:** [blockobra.com.br](https://blockobra.com.br)  
**Situação:** Em produção

## O que faz

- Fluxo formal entre contratada e fiscalização, com separação de funções: quem assina não julga o próprio relatório
- Versões imutáveis encadeadas por hash SHA-256 e trilha de auditoria que não se apaga
- Assinatura eletrônica, incluindo certificado ICP-Brasil
- PDF do RDO com QR Code e página pública de validação de autenticidade
- Clima, mão de obra, equipamentos, serviços, ocorrências e registro fotográfico com GPS
- Cronograma com curva S, orçamento, medições com glosa, estoque, não conformidades e comunicações
- IA de visão que identifica serviços nas fotos e relaciona com a planilha orçamentária
- PWA instalável, com preenchimento offline e sincronização posterior
- Fiscalização por outra organização, com acesso concedido por obra

## Tecnologia

Next.js, NestJS, Prisma, PostgreSQL/PostGIS, Redis, Docker, Caddy

## Sobre este repositório

Este repositório é a página de apresentação do produto. O código-fonte é proprietário e fica em repositório privado.

Desenvolvido por [Kenyo Veloso Chianca](https://github.com/VC202504), engenheiro civil, pela The Bridge Brasil Ltda.
