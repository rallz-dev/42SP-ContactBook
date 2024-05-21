
# 42SP-ContactBook
Esse repositório tem a finalidade de auxiliar no ensino do desenvolvimento web.

## Getting Started
Para iniciar o projeto é necessário que já tenha instalado o **docker**. Caso ainda não tenha, instale-o seguindo este [tutorial](https://docs.docker.com/engine/install/).
Após a instalação do docker  rode o comando `docker-compose up -d`. O argumento `-d` tem como finalidade rodar o docker em **detached mode**, assim o processo roda em background e libera o terminal para uso.

Uma vez que o serviço esteja em pé, você terá acesso a um banco de dados **Postgres** com a seguinte estrutura:

### Tabela Contacts
|id_contact|contact_name|contact_email|contact_phone_number|contact_cpf
|--|--|--|--|--|
|int not null autogenerated (PK)|text|text|text|text

### Tabela Users
|id_user|user_name|user_email|user_password
|--|--|--|--|
|int not null autogenerated (PK)|text|text|text|text

##

Estas tabelas serão usadas ao longo dos exercícios propostos.

# Como fazer as entregas
Caso tenha interesse que seu exercício seja corrigido, crie um fork deste projeto e torne-o público. Ao término, sinalize que deseja que seu projeto seja corrigido. Todas as considerações serão adicionadas ao projeto através de um arquivo markdown chamado Review que será adicionado durante a correção.
