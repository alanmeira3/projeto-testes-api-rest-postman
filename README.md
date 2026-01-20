# Projeto de Testes Automatizados de API REST com Postman

Este projeto demonstra a criação e automação de testes de uma API REST utilizando o Postman e o Collection Runner.

## 🎯 Objetivo
Simular um fluxo completo de operações CRUD em uma API REST pública (JSONPlaceholder), aplicando validações automáticas de status codes e respostas.

## 🛠️ Tecnologias Utilizadas
- Postman
- Collection Runner
- JavaScript (Assertions)
- API pública JSONPlaceholder

## 🔄 Fluxo Implementado
1. POST – Criar um novo post  
2. GET – Buscar um post específico  
3. PUT – Atualizar um post existente  
4. DELETE – Remover um post  

Todos os endpoints são executados automaticamente via Collection Runner.

## ✅ Validações Aplicadas
- Verificação de status HTTP (200, 201, 204)
- Validação de campos retornados em JSON
- Testes automatizados com assertions

## ▶️ Como Executar

1. Importar a collection no Postman  
2. Abrir a collection  
3. Clicar em **Run Collection**  
4. Executar todos os endpoints em sequência  

## 📌 Observação
A API utilizada é pública e simula as operações, não persistindo dados reais no servidor.

---

Projeto desenvolvido para fins de estudo e portfólio em testes de APIs e automação básica.
