# 📅 Agendador de Horários

API REST desenvolvida em **Java com Spring Boot** para gerenciamento de agendamentos de horários.  
Projeto focado em organização de agenda, boas práticas de arquitetura e base para sistemas de reservas.

---

## 🚀 Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- Hibernate
- Banco de dados H2 (em memória)
- Gradle
- Maven Wrapper (Gradle Wrapper)

---

## 📂 Estrutura do Projeto

```text
src/
 └── main/
     ├── java/
     │   └── com/javanauta/agendador_horarios/
     │       ├── controller/
     │       │   └── AgendamentoController.java
     │       ├── infrastructure/
     │       │   ├── entity/
     │       │   │   └── Agendamento.java
     │       │   └── repository/
     │       │       └── AgendamentoRepository.java
     │       ├── services/
     │       │   └── AgendamentoService.java
     │       └── AgendadorHorariosApplication.java
     └── resources/
         └── application.properties
```
🧠 Arquitetura

O projeto segue uma arquitetura em camadas, separando responsabilidades:

Controller → Camada de entrada (REST API)

Service → Regras de negócio

Repository → Acesso a dados

Entity → Modelagem do domínio

Essa separação facilita manutenção, testes e escalabilidade.

🔧 Funcionalidades

Criar agendamentos

Listar agendamentos

Buscar agendamento por ID

Atualizar agendamento

Remover agendamento

(Endpoints REST seguindo boas práticas)

▶️ Como Executar o Projeto
Pré-requisitos

Java 17 ou superior

Git
Passos
```# Clonar o repositório
git clone https://github.com/YggorMartins/Agendador-Horarios.git

# Entrar no diretório
cd Agendador-Horarios

# Executar o projeto
./gradlew bootRun
```

No Windows:

```gradlew.bat bootRun```

🌐 Acesso à Aplicação

API: http://localhost:8080

Console H2: http://localhost:8080/h2-console

Configurações do H2 estão em application.properties.

🧪 Testes

O projeto possui estrutura para testes com Spring Boot:

```./gradlew test```

📌 Próximas Melhorias (Roadmap)

Validações com Bean Validation

DTOs para entrada e saída de dados

Tratamento global de exceções

Integração com banco PostgreSQL ou MySQL

Autenticação com Spring Security

Documentação com Swagger / OpenAPI

👨‍💻 Autor

Yggor Martins
Desenvolvedor Backend / Fullstack
GitHub: @YggorMartins

📄 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para usar, estudar e evoluir 🚀
