# Fine-Tuning de LLM para DSL

Este repositório contém estudos sobre fine-tuning de um Large Language Model (LLM) para compreender e gerar código em uma linguagem de programação dedicada (DSL). O objetivo é melhorar a capacidade do modelo de interpretar e produzir código nesta DSL, tornando-o mais eficiente e preciso.

## Formato do Dataset
Os dados estão no formato JSONL (JSON Lines), onde cada linha representa um exemplo de entrada e saída esperado pelo modelo.

Exemplo:

```json
{"prompt": "Como definir uma variável na DSL?", "completion": "variavel x = 10"}
```

## Aplicações

- **Aprendizado**: Auxiliar desenvolvedores a compreender e usar a DSL.
- **Autocompletar**: Melhorar editores de código com sugestões inteligentes.
- **Automatização**: Gerar scripts automaticamente a partir de descrições em linguagem natural.


## Dataset

https://huggingface.co/datasets/AugustoSavi/bfc-test

## Contribuição
Se deseja contribuir com melhorias no modelo ou no dataset, fique à vontade para abrir uma issue ou enviar um pull request. Toda contribuição é bem-vinda!
