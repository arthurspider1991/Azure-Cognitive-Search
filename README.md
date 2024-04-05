# Cognitive Search Azure ML

Neste repositório, vou demonstrar como integrar o Azure Cognitive Search, Azure AI Services e Azure Storage Account para criar uma solução avançada de pesquisa e análise de dados. O Azure Cognitive Search permite indexar e pesquisar dados não estruturados de forma eficiente. Com os serviços de IA do Azure, como Azure Machine Learning e Azure Cognitive Services, podemos enriquecer os dados indexados com análise de sentimentos, reconhecimento de imagem e outras capacidades de IA. Por fim, o Azure Storage Account será utilizado para armazenar os dados e modelos necessários para essa solução. Siga este guia passo a passo para aprender a configurar e utilizar essas ferramentas em conjunto para criar soluções poderosas de análise de dados.


## Criando os Recursos no Portal Azure
Para começar você precisa ter uma conta no Microsoft Azure

1. Pesquise e cire o recurso "Azure AI Search"
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/Capturar.JPG)

2. Crie um gurpo de recuso, esse grupo de recurso sera usado nos proximos serviços, nome do serviço, recomendo não colocar a localização no Brasil por motivo de preço, em Pricing Tier coloque Basic e clique em Review + Create

![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%202.JPG)

3. Pesquise e cire o recurso "Azure AI Services"
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%203.JPG)
4. Preencha as seguinte informações e clique em Review + Create
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%204.JPG)

5. Agora vamos criar uma conta de armazenamento "Storage Accounts"
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%205.JPG)
6. Clicar em Create
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%206.JPG)
7. Preenha as seguintes informações e clique em Review + create
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%207.JPG)

8. Agora vamos confirgurar o Storage Accounts, clicar em configurações, habilitar o acesso anônimo de blob e clicar em Salvar
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%208.JPG)

9. Em Data Storage escolher a opção Containers, adicionar um novo container, e colocar as seguintes informações e clicar em create
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%209.JPG)
10. clicar no container criado
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%2010.JPG)
11. Agora fazer o Upload dos arquivos que estão dispoiniveis em (https://aka.ms/mslearn-coffee-reviews)
![print](https://raw.githubusercontent.com/arthurspider1991/Azure-Cognitive-Search/main/prints/image%2011.JPG)

## AI Search

1. Voltando a Home do portal, vamos entrar no recurso  AI Search que criamos anteriormente
