# CRUD

![Screenshot 2024-09-05 093547](https://github.com/user-attachments/assets/d4558d31-b7ea-46dd-ac39-6fcfac2d5477)

**Um projeto Spring Boot contendo um CRUD completo de web services REST para 
acessar um recurso de clientes, contendo as cinco operações básicas:**
- Busca paginada de recursos 
- Busca de recurso por id 
- Inserir novo recurso 
- Atualizar recurso 
- Deletar recurso

## CHECKLIST: 
1. Busca por id retorna cliente existente - Ok
2. Busca por id retorna 404 para cliente inexistente - Ok
3. Busca paginada retorna listagem paginada corretamente - Ok
4. Inserção de cliente insere cliente com dados válidos - Ok
5. Inserção de cliente retorna 422 e mensagens customizadas com dados inválidos - Ok 
6. Atualização de cliente atualiza cliente com dados válidos - Ok
7. Atualização de cliente retorna 404 para cliente inexistente - Ok
8. Atualização de cliente retorna 422 e mensagens customizadas com dados inválidos - Ok 
9. Deleção de cliente deleta cliente existente - Ok
10. Deleção de cliente retorna 404 para cliente inexistente - Ok

## Conceitos Utilizados
- O que é uma API REST
- Recursos, URL, parâmetros de consulta e de rota
- Padrões de URL, verbos HTTP, códigos de resposta
- Padrão camadas
- Acessando API
- Repository
- Criando DTO e estruturando camadas
- Busca paginada
- Inserção com POST
- Customizando resposta com ResponseEntity
- Atualização com PUT
- Deleção com DELETE
- Criando exceções de serviço customizadas
- Tratando exceção com resposta customizada
- Validação com Bean Validation
- Customizando a resposta da validação

## Tecnologias utilizadas
- Spring Web
- Spring Data JPA
- Banco de Dados em Memória-H2
- Jakarta Bean Validation
