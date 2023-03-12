# Aprendizado federado no Azure ML

Federated Learning (FL) é uma estrutura em que se treina um único modelo ML em conjuntos de dados distintos que não podem ser coletados em um único local central. Isso permite que empresas e instituições cumpram os regulamentos relacionados à localização e acesso de dados, permitindo inovação e personalização.

Este repositório fornece alguns exemplos de código para executar um pipeline de aprendizado federado na plataforma Azure Machine Learning.

:warning: A execução de um pipeline de aprendizado federado completo levanta **questões de segurança que você precisa abordar** antes de usar este repositório para fins de produção. Considere este repositório apenas como uma amostra.


## Índice

- [Getting started](#zap-getting-started)
- [Documentation](#documentation)
- [Support](#need-support)
- [Contributing](#contributing)

### :zap: Começando

Sem tempo para ler? Acesse diretamente o [**início rápido**](./docs/quickstart.md) para provisionar uma demonstração em minutos em sua própria assinatura.

### Exemplos do mundo real

Verifique também nossos casos de uso do setor abaixo.

| Medical Imaging | Named Entity Recognition | Fraud Detection |
| :-: | :-: | :-: |
| [![](./docs/pics/industry-medical-imaging.png)](./docs/real-world-examples/pneumonia.md) | [![](./docs/pics/industry-ner.png)](./docs/real-world-examples/ner.md) | [![](./docs/pics/industry-fraud-detection.png)](./docs/real-world-examples/ccfraud.md) |
| [pneumonia.md](./docs/real-world-examples/pneumonia.md) | [ner.md](./docs/real-world-examples/ner.md) | [ccfraud.md](./docs/real-world-examples/ccfraud.md) |

### Documentação

Encontre a documentação completa deste projeto [**aqui**](docs/README.md).

### Precisa de suporte?

Verifique o [**guia de solução de problemas**](./docs/tsg.md) para possíveis soluções. Se você não conseguir encontrar uma solução, abra um problema neste repositório.

Se você tiver alguma solicitação de recurso, perguntas técnicas ou encontrar algum bug, não hesite em entrar em contato conosco.

For bug reports and feature requests, you are welcome to open an [**issue**](https://github.com/Azure-Samples/azure-ml-federated-learning/issues).

### Contribuindo

Este projeto aceita contribuições e sugestões. A maioria das contribuições exige que você concorde com um Contrato de Licença de Contribuidor (CLA) declarando que você tem o direito de, e realmente nos concede, os direitos de usar sua contribuição. Para obter detalhes, visite https://cla.opensource.microsoft.com.

Para contribuir, comece criando um [**problema**] autoatribuído (https://github.com/Azure-Samples/azure-ml-federated-learning/issues/new) fornecendo uma visão geral de alto nível o que você gostaria de fazer. Depois que qualquer discussão for concluída, faça o acompanhamento com um PR.

Por favor, envie um e-mail para aim-team@microsoft.com para solicitar um acesso de "colaborador" a este repositório, caso tenha dificuldade em criar uma ramificação. Quando você envia uma solicitação pull, um bot CLA determinará automaticamente se você precisa fornecer um CLA e decorar o PR adequadamente (por exemplo, verificação de status, comentário). Basta seguir as instruções fornecidas pelo bot. Você só precisará fazer isso uma vez em todos os repositórios usando nosso CLA.

Este projeto adotou o Código de Conduta de Código Aberto da Microsoft. Para obter mais informações, consulte as Perguntas frequentes sobre o Código de Conduta ou entre em contato com opencode@microsoft.com para fazer perguntas ou comentários adicionais.
