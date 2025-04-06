# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

Esse repósitorio tem como objetivo demonstrar como para aplicar técnicas de organização de documentos e realizar pesquisas eficientes com Azure Cognitive Search.

## Pré requisitos: 
- Uma conta ativa no Microsoft Azure
- Um serviço Azure Cognitive Search criado
- Dados para indexação (JSON, CSV ou Banco de Dados no Azure)
- Conhecimento básico do Azure Portal e APIs REST/SDK


## Criando um serviço de pesquisa com Azure AI Search:

1 - Entre no portal do Azure.

Clique no botão + Criar um recurso, pesquise o Azure AI Search e crie um recurso do Azure AI Search com as seguintes configurações:

> - Sua assinatura do Azure.
> - Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo.
> - Nome do serviço: necessãrio ser nome exclusivo.
> - Localização: recomendável colocar US.
> - Nível de preços: Básico

![image](https://github.com/user-attachments/assets/be544fa2-2fe7-47a5-82f7-88c855513a40)

##  Criando um recurso de serviços de IA do Azure

É necessário que o recurso de serviços de IA do Azure esteja localizado na mesma região que o seu recurso do Azure AI Search. A sua solução de busca utilizará esse recurso para enriquecer os dados armazenados com insights gerados por inteligência artificial.

![image](https://github.com/user-attachments/assets/eb519ccf-0db3-4d47-a231-e38a985e154c) ![image](https://github.com/user-attachments/assets/906924fd-6035-4227-b122-80963081ae01)


Implantaçao do Azure AI services criada: ![image](https://github.com/user-attachments/assets/b2e0be26-fd3f-4ad5-a8e2-415631b67a5a)

Criando uma conta de armazenamento: ![image](https://github.com/user-attachments/assets/85fbb841-c072-4430-8560-6765c7c6e999)

Na conta de Armazenamento do Azure que você criou, no painel de menu esquerdo, selecione Configuração (em Configurações).
Altere a configuração de Permitir acesso anônimo de Blob para Habilitado e selecione Salvar.
![image](https://github.com/user-attachments/assets/80db2674-5e6b-41ac-9ec4-5df1a5d4e8b2)

Criando um container: ![image](https://github.com/user-attachments/assets/c87c7ef9-0def-4dd0-a842-560e34f3fb31)

baixando ás avaliações: ![image](https://github.com/user-attachments/assets/95c72755-e3b5-4817-9f78-6efd0e35a7d9)

Selecionando o container: ![image](https://github.com/user-attachments/assets/099b9742-355b-41df-b955-f81e094fb1c8)

Use o Search Explorer para escrever e testar consultas. Você pode usar o Search Explorer para escrever consultas e revisar resultados em JSON.

![image](https://github.com/user-attachments/assets/a5661a42-a2f7-496b-b5e8-d21bb7483df0)




