# Importadores GMVB



## Informações Gerais

- Serão aceitos somente arquivos .xlsx
- Importante usar os aquivos atrelados a documentação, pois a aplicação usa os parâmetros prédefinidos no cabeçalho para fazer consultas no banco de dados.
Cabeçalhos com espaço ou com nomes diferentes resultam em erro da aplicação.

###Uso 
#### Caso 1:
##### Todas as propostas inseridas/Alteradas com sucesso:
![sucessocod 127 0 0 1](https://user-images.githubusercontent.com/32857539/113604157-41f83100-961b-11eb-95c2-113606c72d4a.png)


#### Caso 2:
##### Algumas propostas com erro:
![aviso de propostas não inseridas](https://user-images.githubusercontent.com/32857539/113605111-94861d00-961c-11eb-8b29-e081a63c9b16.png)


#### clicando em "veja mais" podera ver propostas e motivo do erro:
![errovejamais](https://user-images.githubusercontent.com/32857539/113605876-a2886d80-961d-11eb-9e74-a6c723863a84.png)


#### mensagens de erro:
- taxa: "a cedula taxa do arquivo deve ter formatçao ex. 0.0123";
- banco: "para alteraçao proposta deve existir no banco de dados";
- erro interno do servidor: "esse tipo de erro acontece por má formatação de cedulas no arquivo o servidor não tem parametros
- para processar os dados "

## Aterar propostas
###### Módulo allterar propostas, não irá alterar caso consulta no banco for:

- status "PAGO" e valores liberados acima de 0
erro:proposta com status "PAGO" não pode ser alterada

- status EM "PROCESSO DE PAGTO" e valores liberados acima de 0
- erro:proposta com status "EM PROCESSO DE PAGTO" não pode ser alteradas.

- Erros comuns mencionados nas informaçoes gerais 






