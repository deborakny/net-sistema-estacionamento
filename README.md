# DIO - Trilha .NET

## Contexto

Sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar as operações de adicionar veículo, remover veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Classe Estacionamento

### Variáveis

- **precoInicial**: Preço cobrado para deixar seu veículo estacionado.

- **precoPorHora**: Preço cobrado por hora de permanência do veículo estacionado.

- **veiculos**: Representa uma coleção de veículos estacionados. Contém apenas a placa do veículo.

### Métodos

- **AdicionarVeiculo**: Recebe a placa digitada pelo usuário e a guarda na lista de **veículos**.

- **RemoverVeiculo**: Verifica se um determinado veículo está estacionado, caso positivo, solicita a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** +  **precoPorHora** * **hora**, exibindo o resultado para o usuário. Ao final, o veículo é removido da lista.

- **ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não tenha nenhum, é exibida a mensagem "Não há veículos estacionados".

## Menu interativo:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar
