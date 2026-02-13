# 🚗 Tabela FIPE - API Consumer com Spring Boot

Aplicação Java desenvolvida com **Spring Boot** que consome a API pública da Tabela FIPE para consulta de valores de veículos (Carros, Motos e Caminhões).

O sistema permite ao usuário selecionar o tipo de veículo via terminal e realiza requisições HTTP para obter dados diretamente de uma API externa.

---

## 🛠 Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Maven
- API REST
- HTTP Client
- JSON

---

## 📌 Funcionalidades

- Seleção do tipo de veículo:
  - 🚗 Carros  
  - 🏍️ Motos  
  - 🚛 Caminhões  

- Consumo da API pública FIPE:
https://parallelum.com.br/fipe/api/v1


- Listagem de marcas disponíveis
- Organização do projeto em camadas (principal + service)

---

## 🏗 Estrutura do Projeto

br.com.alura.TabelaFipe
│
├── principal
│ └── Principal.java
│
├── service
│ └── ConsumoApi.java
│
└── TabelaFipeApplication.java


- `Principal` → Responsável pela interação com o usuário
- `ConsumoApi` → Responsável por realizar as requisições HTTP
- `TabelaFipeApplication` → Classe principal que inicializa a aplicação via `CommandLineRunner`

---

## ▶ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
Acesse a pasta do projeto:

cd nome-do-projeto
Execute com Maven:

./mvnw spring-boot:run
Ou rode diretamente pela sua IDE.
```

💡 Conceitos Aplicados
Consumo de API REST

Manipulação de JSON

Organização em camadas

Uso do CommandLineRunner

Boas práticas de estruturação de projetos Java

📚 Objetivo do Projeto
Este projeto foi desenvolvido com foco em:

Praticar integração com APIs externas

Estruturar aplicações Java utilizando Spring Boot

Aprimorar habilidades em desenvolvimento backend

Consolidar conceitos de HTTP e consumo de serviços REST

👨‍💻 Autor
Yago Pereira
Estudante de Ciência da Computação
Foco em Backend com Java e Spring Boot
