## Arquivos Usados

• Todos os arquivos anexados foram desenvolvidos e executados através do Visual Studio Code. Salvos no Disco Local (C:);

• Para que os arquivos "app.js" e "index.html" seja executado de forma correta, utilizei o Node.js, abrindo um novo terminal e utlizando o seguinte comando: "PS C:\minhaapi> node app.js". E em seguida, com o botão direito do mouse sobre o arquivo "index.html", selecionei a opção "Open with Live Server", para abrir e executar este arquivo:

![Utilizando o Terminal no VS Code](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/3d5c67b8-4ae7-447e-9559-5c5303700dc7)

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/0d5a072a-7a13-4cbd-923d-ce91b898695e)

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/5e97ef52-1566-4443-8d33-635ffdd0c797)

## Postman

GET por ID

• A criação da API contendo os métodos {id}/estados para listar todos os estados da região e o método {id}/csv que deverá gerar um arquivo excel com a lista de Estados da região referente ao ID, se encontra no serviço utilizado "Postman", segue o passo-a-passo para acessá-lo:

**1:** Através do link de convite: "https://app.getpostman.com/join-team?invite_code=39a802085a7a700f831480510571b8b5" é possivel acessar a parte de "Collections" onde se encontra as etapas solicitadas, localizadas na opção "View complete documentation:

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/1bee68ae-68b4-44c8-b782-a5036bc86d02)

**2:** Clicando opção "Open Request", é possível ver com mais detalhes cada etapa:

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/eabd9089-d951-4f75-838e-728657271eb1)

**3:** Clicando na aba "Headers", é possível ver a tabela "Key" que se refere à chave de acesso (API Key) usada para autenticar e autorizar solicitações feitas à API, e as tabela "Value" e "Description":

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/011bb238-0707-4cca-975d-a9b21e8f3f8e)

Foram inseridas as informações "ordem" e "asc" para que a API compreenda a função de listar todos os estados da região por ordem alfabética crescente (A-Z), e logo em seguida clicando na opção "Send" fazendo uma solicitação de envio para o servidor, esperando ele retornar com o pedido feito:

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/48bf872e-0bb1-4a2b-92e9-9396000a97a7)

O mesmo vale para ordem alfabética decrescente (Z-A), utilizando "ordem" e "desc" e logo em seguida executando, clicando na opção "Send":

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/378d9b8c-ed6c-4cd0-b07f-16015cb50030)

**OBS: Caso apareça alguma mensagem de erro quando clicar na opção "Send", recomendo baixar o aplicativo e realizar os testes por lá.**

**Download CSV**

• Para gerar um arquivo excel com a lista de Estados da região referente ao ID, acesse o próximo arquivo chamado "Download CSV" e logo em seguida, clicando na opção "Send" para o servidor receber a solicitação:

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/2c4d6d4e-9e15-49d8-8ed6-c3acdb5a5874)

• Logo em seguida, é possível copiar a URL do site e colar em seu navegador. (Navegador utilizado foi o Google Chrome), e automaticamente o download do arquivo em excel será feito:

![image](https://github.com/luixzg/Teste-EDI-Labs/assets/168920288/39eede34-e7b6-49a1-911c-4b3d991d2f8b)

















