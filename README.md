```
ALUNOS:
Alex Rafael Oneda, Layne Laís de Castilho Firmino, Guilherme Schweitzer e Rafaela Correa
```

>[!IMPORTANT]
>Proposta .... finalizar.

# :desktop_computer: Interface do Usuário (UI)

## TELA - Login/Cadastro
>[!NOTE]
>
>- **Campos de entrada para o cadastro:**
>  - Nome completo
>  - E-mail
>  - Senha
>  - Confirmar senha
>  - Telefone
>  - Data de nascimento

>[!WARNING]
>
>A parte de login funcionará em torno do cadastro.

## TELA - Principal (Estilo Painel)
>[!NOTE]
>
>- Logo e menu de usuário
>- Resumo visual das próximas doses (próximas 24 horas)
>- Lista de medicamentos cadastrados com indicadores de estoque
>- Barra de pesquisa rápida de medicamentos
>- Botão para adicionar novo medicamento
>- Alertas de lembretes para doses próximas
>- Visualização de calendário simplificada para a semana atual

## TELA - Gerenciamento de Medicamentos (Adicionar, Editar, Remover)
>[!NOTE]
>
>- Formulário conforme tabela `medications`
>- **Campos adicionais:**
>  - Forma farmacêutica
>  - Instruções específicas de administração
>  - Upload de imagem do medicamento
>  - Efeitos colaterais comuns
>  - Estoque inicial

>[!WARNING]
>
>As partes de gerenciamento e remoção vão funcionar em torno dos cadastros efetuados e na mesma tela.

## TELA - Visão Geral do Tratamento
>[!NOTE]
>
>- Lista de todos os medicamentos atuais
>- Detalhes de dosagem e frequência para cada medicamento
>- Opção para filtrar por período

## TELA - Registro de Efeitos Colaterais
>[!NOTE]
>
>- Formulário para registrar efeitos colaterais associados a medicamentos específicos (já cadastrados no painel pessoal do usuário)

<br>

## :hammer_and_wrench: Funcionalidades

>[!TIP]
>- [ ] **Autenticação de usuários**
>    - Registro e login completos
>- [ ] **CRUD completo de medicamentos**
>    - Com detalhes aprimorados
>- [ ] **Visualização detalhada de doses programadas**
>- [ ] **Sistema básico de lembretes no dashboard**
>- [ ] **Pesquisa rápida de medicamentos**
>- [ ] **Registro e acompanhamento de estoque de medicamentos**
>- [ ] **Registro e visualização de efeitos colaterais**

<br>

## :gear: Aspectos Técnicos

>[!IMPORTANT]
>- [ ] Implementação completa do banco de dados
>- [ ] Configuração inicial do projeto (PHP, HTML, TailwindCSS) _(Laravel?)_
>- [ ] Autenticação e autorização básica com sessions em PHP
>- [ ] Implementação de upload e armazenamento de imagens para medicamentos
>- [ ] Criação de queries para busca rápida de medicamentos
