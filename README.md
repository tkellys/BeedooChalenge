# Formulário de Inscrição do Beedoo

## Visão Geral
- Este repositório contém User Story e documentação para o desenvolvimento do formulário de inscrição do Beedoo. O objetivo é permitir que usuários com acesso cadastre novos cursos na plataforma de forma intuitiva e segura.
- Aqui também encontrará os links para acessar os casos de testes em Gherkin, os bugs e vulnerabilidades encontradas e as evidências dos testes manuais realizados na plataforma.

## User Story

### Título: Formulário Cadastro de Cursos do Beedoo

**Como** um usuário com permissões de cadastro do Beedoo,  
**Eu quero** preencher o formulário,  
**Para que** eu possa criar um novo curso na plataforma;

### Decisões Tomadas

1. **Campos Obrigatórios**: 
   - **Nome do curso**, **Descrição do curso**, **Instrutor**, **Data de início**, **Data de fim**, **Numero de vagas** e **Tipo de curso**. Estes são os dados mínimos necessários para cadastrar um novo curso na plataforma .

2. **Validações e Critérios de Aceite**:
  - **Nome do curso**: Campo alfanúmerico com no mínimo 5 caracteres e no máximo 255 caracteres
  - **Descrição do curso**: Campo alfanúmerico com no mínimo 5 caracteres e no máximo 255 caracteres
  - **Instrutor**: Campo alfanúmerico com no mínimo 5 caracteres e no máximo 255 caracteres
  - **Data de início**: Campo com máscara de calendário
  - **Data de fim**: Campo com máscara de calendário
  - **Números de vagas**: Campo apenas numérico e deve permitir apenas números inteiros positivos
  - **Tipo de curso**: Dropdown com opções de Presencial ou Online

3. **Mensagens de Erro**:
  - Não preenchimento dos campos obrigatórios devem retornar mensagem de erro abaixo do input do campo:
    **Este campo é obrigatório**

4. **Desabilitar ação do Botão "Cadastrar Curso"**, até que os campos estejam devidamente preenchidos.
   - Implementado para garantir que o formulário só possa ser enviado quando todos os campos estiverem corretamente preenchidos, melhorando a qualidade dos dados enviados.

5. **Redirecionamento Pós-Cadastro**:
   - Redirecionamento para página de listagem dos cursos, confirmando que o novo curso cadastrado esta presente na lista.

6. **Testes**:
   - Testes foram incluídos para verificar a funcionalidade e validação do formulário, garantindo que ele atenda aos requisitos estabelecidos.
   - Garantir que o formulário funcione como esperado e que todos os requisitos sejam atendidos é crucial para a entrega de um produto de qualidade.

## Links Importantes
   - Casos de testes:
   - Relatório de bugs e vulnerabilidades:
   - Evidências:

