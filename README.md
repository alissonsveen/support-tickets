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

### **Criar Ticket**  
- **Método**: `POST`  
- **URL**: `/tickets`  
- **Body**:
```json
{
  "equipment": "Computador",
  "description": "Descrição do problema",
  "user_name": "John doe"
}
```
### **Obter Tickets**
- **Método**: `GET`  
- **URL**: `/tickets`  
- **Body**:
```json

{
    "id": "89cad69e-ef4d-481b-a67c-65a01e75338d",
    "equipment": "Computador",
    "description": "Descrição do problema",
    "user_name": "John doe",
    "status": "open",
    "created_at": "2025-02-18T18:22:11.269Z",
    "updated_at": "2025-02-18T18:22:11.269Z"
}
