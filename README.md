# Ramais SMI

Este projeto exibe uma lista de ramais de uma empresa, permitindo a pesquisa e filtragem de ramais por nome, setor e máquina.

## Estrutura do Projeto

### Arquivos
- **data.json**: Contém os dados dos ramais, incluindo nome, ramal, setor e máquina.
- **main.css**: Contém os estilos CSS para a página.
- **main.html**: Contém a estrutura HTML da página.
- **main.js**: Contém o código JavaScript para manipulação da página, incluindo a filtragem dos ramais.

## Funcionalidades
- Exibição de uma lista de ramais.
- Pesquisa e filtragem de ramais por nome, setor e máquina.
- Paginação dos resultados.

## Estrutura dos Dados
O arquivo `data.json` contém uma lista de objetos com a seguinte estrutura:

```json
[
  {
    "nome": "João Silva",
    "ramal": "1234",
    "setor": "TI",
    "maquina": "PC-001"
  },
  {
    "nome": "Maria Oliveira",
    "ramal": "5678",
    "setor": "Financeiro",
    "maquina": "PC-002"
  }
]
```

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
