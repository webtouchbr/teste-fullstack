# Teste fullstack

Leia primeiro todo o projeto, faça sua estimativa de horas para o desenvolvimento e envie um email com o título `[Teste Fullstack] Estimativa` para kaio@webtouch.com.br

Quando finalizar o teste, publique tudo no seu [Github](https://github.com) e envie um email com o título `[Teste Fullstack] Finalizado` para rh@webtouch.com.br

## Missão backend



Desenvolver uma **API JSON RESTful** em **Python** ou **.Net** ou **Node** ou **PHP**, que utilize todos os métodos (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`).  
Faça o teste unitário da **API** (Bônus :star:)

Pode utilizar algum framework para desenvolvimento do backend.

### Especificação

Monte uma base de veículo com a seguinte estrutura:

```
veiculo:   string
marca:     string
ano:       integer
descricao: text
vendido:   bool
created:   datetime
updated:   datetime
```

Utilize **MongoDB** ou **MySQL** para armazenar os dados que a **API** irá consumir.

### API endpoints

`GET /veiculos`

Retorna todos os veículos

---

`GET /veiculos/find`

Retorna os veículos de acordo com o termo passado parâmetro `q`

---

`GET /veiculos/{id}`

Retorna os detalhes do veículo

---

`POST /veiculos`

Adiciona um novo veículo

---

`PUT /veiculos/{id}`

Atualiza os dados de um veículo

---

`PATCH /veiculos/{id}`

Atualiza apenas alguns dados do veículo

---

`DELETE /veiculos/{id}`

Apaga o veículo


## Missão frontend

Desenvolver uma **UI (User Interface)** de acordo com o desenho que está na pasta [layout](https://github.com/webtouchbr/teste-fullstack/tree/master/layout)

### Especificação

- Cross browser support (IE11+)
- Consumir **API** criada acima
- Criar uma tela que tenha...
    - Listagem de veículos
    - Detalhe do veículo
    - Busca
    - Formulário de novo/edição de veículos

### Dica

Utilize algum framework para auxiliar no desenvolvimento da interface, por exemplo:

- https://getuikit.com
- https://getmdl.io/
- http://getbootstrap.com/css/
- http://foundation.zurb.com/




## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste Fullstack] O assunto que vc deseja` para kaio@webtouch.com.br
