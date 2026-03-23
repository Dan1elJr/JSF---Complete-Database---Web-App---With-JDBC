# Student Tracker App 📚

Aplicação em **JavaServer Faces (JSF)** para cadastro e gerenciamento de estudantes.

## ✨ Funcionalidades

* Listagem de estudantes (nome, sobrenome e e-mail).
* Inclusão de novos estudantes.
* Atualização de dados de um estudante existente.
* Exclusão de estudantes com confirmação de segurança.

## 🛠️ Tecnologias utilizadas

* **Java EE / Jakarta EE**
* **JSF 2.x** (`javax.faces`)
* **XHTML** para as páginas de interface
* **CSS** para estilização
* **JDBC + MySQL** para persistência dos dados
* Servidor de aplicação (Tomcat)


## ▶️ Como executar

1. Clone o repositório.
2. Configure um servidor compatível com JSF (ex: Apache Tomcat).
3. Crie o banco de dados no MySQL:

   ```sql
   CREATE DATABASE student_tracker;
   USE student_tracker;

   CREATE TABLE student (
     id INT PRIMARY KEY AUTO_INCREMENT,
     first_name VARCHAR(50) NOT NULL,
     last_name VARCHAR(50) NOT NULL,
     email VARCHAR(100) NOT NULL
   );
   ```
4. Ajuste as credenciais de conexão JDBC no projeto (usuário, senha, URL do banco).
5. Compile e implante o projeto no servidor.
6. Acesse no navegador:

   ```
   http://localhost:8080/student-tracker/
   ```



