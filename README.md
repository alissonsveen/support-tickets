# 🚀 API de Tickets (Node.js)

Essa API permite a criação, consulta, atualização e exclusão de tickets em um sistema de gerenciamento de tickets.

## 📝 Funcionalidades

- **Criar Ticket** ✍️
- **Obter Tickets** 📋
- **Atualizar Ticket** 🔄
- **Excluir Ticket** ❌

## 🔧 Tecnologias Utilizadas
- Node.js 💻
  
## 🛠️ Endpoints

### 1. **Criar Ticket**  
- **Método**: `POST`  
- **URL**: `/tickets`  
- **Body**:
```json
{
  "equipment": "Computador",
  "description": "Descrição do problema",
  "user_name": "John doe"
}
