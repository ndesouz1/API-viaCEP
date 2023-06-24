<h1>API REST - Consulta CEP</h1>



Essa aplicação foi desenvolvida utilizando **Java Spring e Spring Boot**.

API é a sigla em inglês para Application Programming Interface, ouinterface de programação de aplicações. As interfaces de programação de aplicativos (APIs) são conjuntos de ferramentas, definições e protocolos para a criação de aplicações de software. APIs conectam soluções e serviços, sem a necessidade de saber como esses elementos foram implementados.
Para saber mais sobre APIs: https://www.redhat.com/pt-br/topics/api/what-are-application-programming-interfaces


<h2 id="pre-requisites">💻 Requisitos</h2>
Para rodar esse projeto você precisa ter o Java instalado na sua máquina.

<h2 id="how-to-use"> 🚀 Instalando o projeto</h2>

Primeiro você deve clonar o repositório,

```bash
# Clone o repositório
$ git clone https://github.com/ndesouz1/API-viaCEP.git

# Rode a classe principal do projeto
PrimeiraApiSpringBootApplication

#Istale o Insomnia e faça uma requisição de um CEP na porta 8080:
GET localhost:8080/consulta-cep/18030322
```