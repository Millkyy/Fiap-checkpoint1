# API de Pedidos - Checkpoint SOA

## 👩‍👧‍👧 Integrantes
Aline Zeppelini - RM97966
Camilly Ishida - RM551474
Julia Galvão - RM550201

## 📌 Descrição
Este projeto é uma API REST desenvolvida em **Spring Boot** para gestão de pedidos. A API permite criar, listar, buscar, atualizar e deletar pedidos.

A API utiliza **Spring Data JPA** para interagir com o banco de dados **H2 Database (em memória)**.

---

## 🛠️ Tecnologias Utilizadas
- **Java 17**
- **Spring Boot 3**
- **Spring Data JPA**
- **H2 Database**
- **Lombok**
- **Maven**

  ![image](https://github.com/user-attachments/assets/2a3ad025-ef35-400e-b401-9a076f6bf387)


---

## 🚀 Como Executar o Projeto

### **1️⃣ Clonar o Repositório**
```sh
git clone https://github.com/Millkyy/Fiap-checkpoint1.git
cd checkpoint1
```

### **2️⃣ Configurar e Executar a API**

1. Certifique-se de ter o **Java 17** e **Maven** instalados.
2. No terminal, dentro do diretório do projeto, execute:
   ```sh
   mvn spring-boot:run
   ```
3. A API será iniciada em **http://localhost:8080**.

### **3️⃣ Acessar o Banco de Dados H2** (Opcional)
Acesse **http://localhost:8080/h2-console** e use as credenciais:
- **JDBC URL:** `jdbc:h2:file:./data/testdb`
- **Usuário:** `sa`
- **Senha:** *(deixe em branco)*

---

## 📡 Endpoints da API

### **1️⃣ Criar um Pedido**

![image](https://github.com/user-attachments/assets/46d98be2-e808-447c-9385-72ce89f0ff5d)
---

### **2️⃣ Listar Todos os Pedidos**

![image](https://github.com/user-attachments/assets/638ca2b3-c09b-42fe-9f8c-842faca6218b)
---

### **3️⃣ Buscar um Pedido por ID**
![image](https://github.com/user-attachments/assets/1ba92a64-82c1-422a-9662-de59d7e1bf0f)
![image](https://github.com/user-attachments/assets/57c727e5-dd3c-4ebe-a7f4-097cc5441227)
---

### **4️⃣ Atualizar um Pedido**
![image](https://github.com/user-attachments/assets/dab556cc-609a-4b97-9485-eb2b1506c5c3)
---

### **5️⃣ Deletar um Pedido**
![image](https://github.com/user-attachments/assets/d3422939-26be-4714-9003-84c90c290e86)
![image](https://github.com/user-attachments/assets/b373e2b2-1512-4e25-a0ae-2d3cc258e485)
---

### **Resultado Final**
![image](https://github.com/user-attachments/assets/84c65b89-bd0f-4be3-877d-8461151513de)


