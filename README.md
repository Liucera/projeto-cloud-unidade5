#  API REST Containerizada - Unidade 5

Este projeto demonstra a implementação de uma infraestrutura moderna utilizando containers para hospedar uma API Node.js.

##  Descrição
O projeto utiliza o modelo **CaaS (Container as a Service)** para garantir que a aplicação seja executada de forma idêntica em qualquer ambiente.

##  Tecnologias
- **Node.js**: Backend da aplicação.
- **Docker**: Containerização e isolamento.
- **WSL2 (Ubuntu)**: Ambiente Linux rodando no Windows.

##  Como executar

### 1. Construir a imagem:
```bash
docker build -t minha-api-unidade5 .
docker run -d -p 8080:3000 --name api-executando minha-api-unidade5
##  Informações do Container em Execução
Com base na validação local, estas são as especificações da instância:

* **ID do Container**: `49ca0b8c8e3`
* **Imagem**: `minha-api-unidade5`
* **Portas**: Mapeamento `8080:3000` (Host -> Container)
* **Uso de Memória**: `16.14 MB` (Docker Stats)
* **Status**: Up / Operational
