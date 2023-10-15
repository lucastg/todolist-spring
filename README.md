# Todo List

> **🚀** Um gerenciador de tarefas desenvolvido em Java 17 com Spring Boot 3.

## O que é?

> Este projeto é um gerenciador de tarefas desenvolvido em Java 17 com Spring Boot 3. Foi desenvolvido como parte do evento gratuito "Semana JAVA" fornecido pela Rocketseat.

## Tecnologias utilizadas

> * **Java 17** ☕
> * **Spring Boot 3** 🌱
> * **Lombok**
> * **H2 Database** 💧
> * **BCrypt** 🛡️

## Como executar

> 1. Clone o repositório do projeto:
     git clone https://github.com/lucastg/todolist-spring.git

> 2. Acesse a pasta do projeto e execute o comando para instalar as dependências:
     *mvn install*

> 3. Execute a aplicação

> Acesse a aplicação no navegador em http://localhost:8080/

## Funcionalidades
A aplicação permite que você cadastre, edite e exclua tarefas. Você também pode marcar tarefas como concluídas.

## Collection
Colection com as rotas:
[Uploa{"_type":"export","__export_format":4,"__export_date":"2023-10-15T21:47:31.920Z","__export_source":"insomnia.desktop.app:v2023.4.0","resources":[{"_id":"req_0b7c0b3f229b4d72b0ae87c26a63e0b3","parentId":"fld_c6c50db522cd4789a9f2558c911d43fc","modified":1697406231128,"created":1697406198929,"url":"http://localhost:8080/tasks/{id}","name":"New Request","description":"","method":"PUT","body":{"mimeType":"application/json","text":"{\n    \"title\":\"New Title\"\n}"},"parameters":[],"headers":[{"name":"Content-Type","value":"application/json"}],"authentication":{"type":"basic","useISO88591":false,"disabled":false,"username":"username","password":"12345"},"metaSortKey":-1697406198929,"isPrivate":false,"settingStoreCookies":true,"settingSendCookies":true,"settingDisableRenderRequestBody":false,"settingEncodeUrl":true,"settingRebuildPath":true,"settingFollowRedirects":"global","_type":"request"},{"_id":"fld_c6c50db522cd4789a9f2558c911d43fc","parentId":"wrk_cf1b07cf4a354498a279e90ec81a2fdb","modified":1697406102484,"created":1697406102484,"name":"Tasks","description":"","environment":{},"environmentPropertyOrder":null,"metaSortKey":-1697406102484,"_type":"request_group"},{"_id":"wrk_cf1b07cf4a354498a279e90ec81a2fdb","parentId":null,"modified":1697405948462,"created":1697405948462,"name":"Rocketseat Java","description":"","scope":"collection","_type":"workspace"},{"_id":"req_260899c972de45c6bfa291d4a9615c0b","parentId":"fld_c6c50db522cd4789a9f2558c911d43fc","modified":1697406186348,"created":1697406138234,"url":"http://localhost:8080/tasks/","name":"New Request","description":"","method":"POST","body":{"mimeType":"application/json","text":"{\n    \"description\":\"test\",\n    \"title\":\"test\",\n    \"priority\":\"test\",\n    \"startAt\":\"2023-10-30T12:30:00\",\n    \"endAt\":\"2023-10-30T15:00:00\"\n}"},"parameters":[],"headers":[{"name":"Content-Type","value":"application/json"}],"authentication":{"type":"basic","useISO88591":false,"disabled":false,"username":"username","password":"12345"},"metaSortKey":-1697406138234,"isPrivate":false,"settingStoreCookies":true,"settingSendCookies":true,"settingDisableRenderRequestBody":false,"settingEncodeUrl":true,"settingRebuildPath":true,"settingFollowRedirects":"global","_type":"request"},{"_id":"req_73a2c42751c0454387757f32e257cde1","parentId":"fld_c6c50db522cd4789a9f2558c911d43fc","modified":1697406127426,"created":1697406103875,"url":"http://localhost:8080/tasks/","name":"New Request","description":"","method":"GET","body":{},"parameters":[],"headers":[],"authentication":{"type":"basic","useISO88591":false,"disabled":false,"username":"username","password":"12345"},"metaSortKey":-1697406103875,"isPrivate":false,"settingStoreCookies":true,"settingSendCookies":true,"settingDisableRenderRequestBody":false,"settingEncodeUrl":true,"settingRebuildPath":true,"settingFollowRedirects":"global","_type":"request"},{"_id":"req_7812ba4066cd4e7a9c924b73d22ea512","parentId":"fld_444cd7d2095141fd84ca80fb0e33a7ff","modified":1697406093483,"created":1697406070642,"url":"http://localhost:8080/users/","name":"Create User","description":"","method":"POST","body":{"mimeType":"application/json","text":"{\n    \"username\":\"username\",\n    \"password\":\"12345\",\n    \"name\":\"Username\"\n}"},"parameters":[],"headers":[{"name":"Content-Type","value":"application/json"}],"authentication":{},"metaSortKey":-1697406070642,"isPrivate":false,"settingStoreCookies":true,"settingSendCookies":true,"settingDisableRenderRequestBody":false,"settingEncodeUrl":true,"settingRebuildPath":true,"settingFollowRedirects":"global","_type":"request"},{"_id":"fld_444cd7d2095141fd84ca80fb0e33a7ff","parentId":"wrk_cf1b07cf4a354498a279e90ec81a2fdb","modified":1697406033802,"created":1697406033802,"name":"Users","description":"","environment":{},"environmentPropertyOrder":null,"metaSortKey":-1697406033802,"_type":"request_group"},{"_id":"req_878814c5d6da423dacd835bb72029d3a","parentId":"fld_444cd7d2095141fd84ca80fb0e33a7ff","modified":1697406068012,"created":1697405977808,"url":"http://localhost:8080/users/","name":"List Users","description":"","method":"GET","body":{},"parameters":[],"headers":[],"authentication":{},"metaSortKey":-1697405977808,"isPrivate":false,"settingStoreCookies":true,"settingSendCookies":true,"settingDisableRenderRequestBody":false,"settingEncodeUrl":true,"settingRebuildPath":true,"settingFollowRedirects":"global","_type":"request"},{"_id":"env_a31b527a832b77cae347256cfeb613ec3de190bf","parentId":"wrk_cf1b07cf4a354498a279e90ec81a2fdb","modified":1697405948465,"created":1697405948465,"name":"Base Environment","data":{},"dataPropertyOrder":null,"color":null,"isPrivate":false,"metaSortKey":1697405948465,"_type":"environment"},{"_id":"jar_a31b527a832b77cae347256cfeb613ec3de190bf","parentId":"wrk_cf1b07cf4a354498a279e90ec81a2fdb","modified":1697405948467,"created":1697405948467,"name":"Default Jar","cookies":[],"_type":"cookie_jar"}]}ding colection-todolist…]()


## Agradecimentos
Agradeço à Rocketseat pelo evento, que me motivou e orientou a desenvolver este projeto.
