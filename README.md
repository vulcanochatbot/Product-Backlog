# Product Backlog — Projeto Vulcano

## Visão geral

O backlog do projeto **Vulcano** organiza, prioriza e detalha o trabalho necessário para construir o MVP da plataforma.

O **Vulcano** é uma plataforma web voltada para **vagas e oportunidades na construção civil no Brasil**, conectando **candidatos/profissionais** a **empresas/construtoras** por meio de um sistema simples, funcional e com suporte inicial de um **chatbot contextual**.

Este backlog foi estruturado para apoiar o desenvolvimento real do produto, com foco em um **MVP viável**, evitando complexidade desnecessária e separando claramente o que entra na primeira versão do que fica como evolução futura.

---

## Product Goal

Criar uma plataforma web simples e funcional que conecte profissionais da construção civil a empresas/construtoras, permitindo:

- cadastro de candidatos
- cadastro de empresas
- publicação de vagas
- candidatura em vagas
- gerenciamento básico
- atendimento inicial por chatbot com IA contextual

---

## Critério de priorização

Os itens do backlog estão organizados com base em prioridade de entrega:

- **Must**: essencial para o MVP funcionar
- **Should**: importante após o núcleo principal
- **Could**: melhoria ou evolução
- **Post-MVP**: fora da primeira entrega

---

## Escopo do MVP

### Entra no MVP

- cadastro e login de candidato
- cadastro e login de empresa
- criação e visualização de vagas
- candidatura em vaga
- gerenciamento básico
- chatbot Vulcan integrado ao site
- banco de dados real
- responsividade
- fluxo funcional ponta a ponta

### Fica fora do MVP inicial

- integração com WhatsApp
- IA local com LM Studio em produção
- notificações avançadas
- upload de currículo/documentos
- analytics avançado
- pagamento/assinatura SaaS
- recomendação inteligente de vagas/candidatos

---

## Estrutura do backlog

Cada item do backlog segue a seguinte lógica:

- **ID**
- **Épico**
- **Item**
- **Tipo**
- **Prioridade**
- **Release**

---

## Épicos do projeto

### 1. Fundação do sistema
Responsável pela base estrutural do projeto, incluindo organização do sistema, backend, banco de dados e autenticação.

### 2. Site público e navegação
Responsável pela experiência inicial do usuário no site, landing page, navegação e páginas institucionais.

### 3. Área do candidato
Responsável pelo fluxo do profissional dentro da plataforma, incluindo cadastro, perfil, visualização de vagas e candidaturas.

### 4. Área da empresa/construtora
Responsável pelo fluxo da empresa, incluindo cadastro, perfil, publicação e gestão de vagas.

### 5. Chatbot Vulcan com IA contextual
Responsável pelo suporte conversacional do sistema, limitado ao contexto da plataforma.

### 6. Administração do sistema
Responsável pelo controle administrativo básico da plataforma.

### 7. Qualidade, segurança e experiência
Responsável por validações, segurança, tratamento de erros, responsividade e testes.

### 8. Entrega, demonstração e continuidade
Responsável pela preparação da apresentação, documentação e evolução futura do produto.

---

## Backlog completo

| ID | Épico | Item | Tipo | Prioridade | Release |
|---|---|---|---|---|---|
| PB01 | Fundação do sistema | Definir estrutura base do projeto web | Técnico | Must | MVP |
| PB02 | Fundação do sistema | Configurar ambiente e variáveis | Técnico | Must | MVP |
| PB03 | Fundação do sistema | Modelar banco de dados real | Técnico | Must | MVP |
| PB04 | Fundação do sistema | Remover dependência de dados mockados | Técnico | Must | MVP |
| PB05 | Fundação do sistema | Criar API base organizada | Técnico | Must | MVP |
| PB06 | Fundação do sistema | Implementar autenticação básica | Técnico | Must | MVP |
| PB07 | Site público e navegação | Ajustar landing page do Vulcano | Funcionalidade | Must | MVP |
| PB08 | Site público e navegação | Organizar navegação principal | Funcionalidade | Must | MVP |
| PB09 | Site público e navegação | Criar seção “Como funciona” | Funcionalidade | Should | MVP |
| PB10 | Site público e navegação | Garantir responsividade básica | Qualidade | Must | MVP |
| PB11 | Área do candidato | Cadastro de candidato | Funcionalidade | Must | MVP |
| PB12 | Área do candidato | Login e logout de candidato | Funcionalidade | Must | MVP |
| PB13 | Área do candidato | Criar perfil profissional | Funcionalidade | Must | MVP |
| PB14 | Área do candidato | Editar perfil profissional | Funcionalidade | Must | MVP |
| PB15 | Área do candidato | Visualizar lista de vagas | Funcionalidade | Must | MVP |
| PB16 | Área do candidato | Ver detalhes da vaga | Funcionalidade | Must | MVP |
| PB17 | Área do candidato | Filtrar vagas | Funcionalidade | Should | MVP 1.1 |
| PB18 | Área do candidato | Candidatar-se a uma vaga | Funcionalidade | Must | MVP |
| PB19 | Área do candidato | Visualizar histórico de candidaturas | Funcionalidade | Should | MVP 1.1 |
| PB20 | Área do candidato | Recuperação de senha | Funcionalidade | Should | MVP 1.1 |
| PB21 | Área da empresa/construtora | Cadastro de empresa | Funcionalidade | Must | MVP |
| PB22 | Área da empresa/construtora | Login e logout de empresa | Funcionalidade | Must | MVP |
| PB23 | Área da empresa/construtora | Criar perfil da empresa | Funcionalidade | Must | MVP |
| PB24 | Área da empresa/construtora | Publicar nova vaga | Funcionalidade | Must | MVP |
| PB25 | Área da empresa/construtora | Editar, pausar ou encerrar vaga | Funcionalidade | Must | MVP |
| PB26 | Área da empresa/construtora | Visualizar vagas publicadas pela empresa | Funcionalidade | Must | MVP |
| PB27 | Área da empresa/construtora | Visualizar candidatos por vaga | Funcionalidade | Must | MVP |
| PB28 | Área da empresa/construtora | Alterar status da candidatura | Funcionalidade | Should | MVP 1.1 |
| PB29 | Chatbot Vulcan com IA contextual | Integrar chatbot ao sistema final | Funcionalidade | Must | MVP |
| PB30 | Chatbot Vulcan com IA contextual | Definir prompt/sistema do Vulcan | IA | Must | MVP |
| PB31 | Chatbot Vulcan com IA contextual | Responder dúvidas sobre cadastro, perfil e candidaturas | IA | Must | MVP |
| PB32 | Chatbot Vulcan com IA contextual | Responder dúvidas sobre fluxo da empresa | IA | Must | MVP |
| PB33 | Chatbot Vulcan com IA contextual | Implementar fallback para perguntas fora de contexto | IA | Must | MVP |
| PB34 | Chatbot Vulcan com IA contextual | Manter histórico de conversa | Funcionalidade | Should | MVP |
| PB35 | Chatbot Vulcan com IA contextual | Validar estabilidade do microfone/áudio | Qualidade | Could | Pós-MVP |
| PB36 | Chatbot Vulcan com IA contextual | Criar FAQ inicial do Vulcano | Conteúdo/IA | Should | MVP 1.1 |
| PB37 | Administração do sistema | Criar acesso administrativo básico | Funcionalidade | Must | MVP |
| PB38 | Administração do sistema | Listar candidatos cadastrados | Funcionalidade | Should | MVP 1.1 |
| PB39 | Administração do sistema | Listar empresas cadastradas | Funcionalidade | Should | MVP 1.1 |
| PB40 | Administração do sistema | Listar vagas publicadas | Funcionalidade | Must | MVP |
| PB41 | Administração do sistema | Moderar ou desativar vaga | Funcionalidade | Should | MVP 1.1 |
| PB42 | Administração do sistema | Dashboard simples com números do sistema | Funcionalidade | Could | Pós-MVP |
| PB43 | Qualidade, segurança e experiência | Validar campos obrigatórios | Qualidade | Must | MVP |
| PB44 | Qualidade, segurança e experiência | Exibir mensagens de erro e sucesso claras | UX | Must | MVP |
| PB45 | Qualidade, segurança e experiência | Proteger rotas privadas | Segurança | Must | MVP |
| PB46 | Qualidade, segurança e experiência | Tratar erros entre frontend e backend | Qualidade | Must | MVP |
| PB47 | Qualidade, segurança e experiência | Melhorar linguagem da interface | UX | Should | MVP 1.1 |
| PB48 | Qualidade, segurança e experiência | Testar fluxos críticos do MVP | Qualidade | Must | MVP |
| PB49 | Qualidade, segurança e experiência | Ajustar layout para diferentes telas | Qualidade | Must | MVP |
| PB50 | Qualidade, segurança e experiência | Garantir carregamento aceitável | Qualidade | Should | MVP 1.1 |
| PB51 | Entrega, demonstração e continuidade | Preparar ambiente de demonstração | Entrega | Must | MVP |
| PB52 | Entrega, demonstração e continuidade | Criar roteiro de demonstração | Entrega | Must | MVP |
| PB53 | Entrega, demonstração e continuidade | Documentar instalação e execução | Técnico | Must | MVP |
| PB54 | Entrega, demonstração e continuidade | Documentar arquitetura simples | Técnico | Should | MVP 1.1 |
| PB55 | Entrega, demonstração e continuidade | Coletar feedbacks e melhorias futuras | Produto | Should | Pós-MVP |
| PB56 | Pós-MVP | Integração com WhatsApp | Evolução | Post-MVP | Pós-MVP |
| PB57 | Pós-MVP | IA local via LM Studio | Evolução | Post-MVP | Pós-MVP |
| PB58 | Pós-MVP | Usar notebook/PC como servidor | Evolução | Post-MVP | Pós-MVP |
| PB59 | Pós-MVP | Upload de currículo/documentos | Evolução | Post-MVP | Pós-MVP |
| PB60 | Pós-MVP | Notificações por e-mail/WhatsApp | Evolução | Post-MVP | Pós-MVP |
| PB61 | Pós-MVP | Sistema SaaS com planos e cobrança | Evolução | Post-MVP | Pós-MVP |
| PB62 | Pós-MVP | Recomendação inteligente de vagas/candidatos | Evolução | Post-MVP | Pós-MVP |

---

## Roadmap inicial por sprint

### Sprint 1
Base estrutural do sistema, ambiente, banco, autenticação inicial, landing page, navegação principal, responsividade e cadastro/login inicial de candidatos e empresas.

### Sprint 2
Perfis de candidato e empresa, fluxo principal de vagas e candidaturas, publicação e gerenciamento de vagas e primeiras validações de interface.

### Sprint 3
Integração do chatbot, definição do comportamento contextual do Vulcan, fallback para fora de escopo, testes principais, ajustes visuais e preparação da demonstração.

### Sprint 4
Filtros, histórico, recuperação de senha, status de candidatura, FAQ inicial, listagens administrativas complementares, documentação e refinamentos.

---

## Observação final

Este backlog foi construído para manter o projeto **realista, funcional e evolutivo**, priorizando aquilo que é necessário para a entrega de um MVP web consistente antes de expandir para integrações e recursos mais avançados.
