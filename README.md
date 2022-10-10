AJUSTES E MELHORIAS DO CÓDIGO.

- A ORDEM DO ID DA EMPRESA ESTAVA CONFUNDINDO, ALTEREI PARA DEIXAR EM ORDEM CRESCENTE.
![image](https://user-images.githubusercontent.com/74841014/194925840-8c19e49c-697b-4394-8c4e-c41d24148ea9.png)

------------------------------------------------------------------------------------------------------------------------------------

- PELA REGRA DE NEGÓCIO SOMENTE O ADMIN E A EMPRESA PODEM TER ACESSO AS INFORMAÇÕES DA EMPRESA (ALÉM DO NOME)
- PARA ISSO PRECISEI ATRIBUIR UMA EMPRESA PARA OS USUÁRIOS ADMIN
- COMO TINHA SOMENTE UM USUÁRIO ADMIN, ADICIONEI MAIS DOI. FICANDO ASSIM, CADA EMPRESA COM SEU ADMIN.
![image](https://user-images.githubusercontent.com/74841014/194926424-96723547-7ef8-4b0c-8d22-ed7ce932579c.png)

------------------------------------------------------------------------------------------------------------------------------------

- ALTEREI A VALIDAÇÃO DO 'IF' POR BOA PRÁTICA, JÁ QUE É UMA FUNCIONALIDADE NATIVA DO JAVA.
![image](https://user-images.githubusercontent.com/74841014/194927043-56025199-32a2-4570-b253-ad83c0f04608.png)
 
------------------------------------------------------------------------------------------------------------------------------------

- ANTES VALIDAVA SOMENTE SE O USUÁRIO LOGADO ERA UMA EMPRESA, MAS O CORRETO ERA VALIDAR SE O USUÁRIO ERA UMA EMPRESA OU UM ADMIN
![image](https://user-images.githubusercontent.com/74841014/194927586-d196e964-3a27-4104-8724-1503b2802e00.png)

------------------------------------------------------------------------------------------------------------------------------------

- FORMATEI OS PRINTLN PARA RETORNAREM UM NÚMERO DOUBLE COM DUAS CASAS DECIMAIS, %2.F.
![image](https://user-images.githubusercontent.com/74841014/194927765-96ee8adb-9f6c-4b49-a673-07f7fabf2dff.png)

------------------------------------------------------------------------------------------------------------------------------------

- REMOVI O STREAM().TOLIST POIS JÁ É DECLARADO COMO PARÂMETRO.
- O VALOR QUE ESTAVA SENDO PASSADO NA INSTÂNCIA DD OBJETO 'VENDA' ERA O VALOR DA SOMA DOS PRODUTOS
- PARA ISSO CRIEI UMA OUTRA VARIÁVEL, ONDE SOMO O VALOR DOS PRODUTOS E DA COMISSÃO.
![image](https://user-images.githubusercontent.com/74841014/194928230-3176276d-7dc5-4de0-b703-d0d9ea48bd89.png)

------------------------------------------------------------------------------------------------------------------------------------
