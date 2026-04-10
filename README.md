# atv-pratica01 — Programação para Dispositivos Móveis

## Descrição
Aplicativo de controle de despesas em React Native com Expo, desenvolvido seguindo as instruções das Aulas 07 (Navegação) e 08 (Itens de Interface e Funções).

## Estrutura do Projeto

```
atv-pratica01/
├── App.js                          # Configuração da navegação principal
├── screens/
│   ├── DespesasRecentes.js         # Tela: despesas dos últimos 7 dias
│   ├── TodasDespesas.js            # Tela: todas as despesas
│   └── GerenciarDespesa.js         # Tela: adicionar/editar despesa
├── components/
│   ├── IconButton.js               # Botão com ícone Ionicons
│   └── despesa/
│       ├── DespesaItem.js          # Item individual da lista
│       ├── DespesaLista.js         # FlatList de despesas
│       ├── DespesaSaida.js         # Agrupa Sumário + Lista
│       └── DespesaSumario.js       # Exibe período e soma total
└── README.md
```


