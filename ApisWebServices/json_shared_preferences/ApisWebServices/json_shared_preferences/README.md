# json_shared_preferences

A new Flutter project.


Shared Prefrences (Armazenamento Interno do Aplicativo)

Armazenamento   Chave -> Valor
                "config" -> "Texto" texto em formato Json

O que é um Texto em Formato Json -> 
[
     config:{
        "NomedoUsuario" : "nome do usuario",
         "IdadedoUsuaro" : 25,
        "TemaEscuro" : true,
    }
]

dart -> Linguagem de Programação do Flutter não lê JSON
     -> converter => ( json.decode => convert Text:Json em Map:Dart)
                  => ( json.encode => convert Map:Dart em Text:Json)