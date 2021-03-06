# Teste mobile app filmes

O objetivo desse teste é com que possamos analisar o código e ao mesmo tempo que o desenvolvedor possa estudar baseado em um objetivo final.

# Linguagem e libs:
Kotlin (https://kotlinlang.org/docs/android-overview.html)

Sugestão do que deve ser utilizado baseado no nosso dia a dia:
- Arquitetura MVVM (https://developer.android.com/topic/libraries/architecture/images/final-architecture.png)
- Retrofit (https://square.github.io/retrofit/)
- Camadas de dados com RxJava 2 (https://github.com/ReactiveX/RxJava) e RxAndroid (https://github.com/ReactiveX/RxAndroid)
- Livedata (https://developer.android.com/topic/libraries/architecture/livedata?hl=pt-br)
- Databinding (https://developer.android.com/topic/libraries/data-binding?hl=pt-br)
- Room (Banco de dados) (https://developer.android.com/training/data-storage/room)
- Navigation component (https://developer.android.com/guide/navigation/navigation-getting-started)

 
# Endpoint 
Consumir o endpoint:
https://developers.themoviedb.org/3/movies/get-popular-movies
para utilização desse serviço é necessário criar a conta e configurar a api_key

# Telas e o que fazer:

- Screen principal: 
Implementar uma lista onde é exibido os filmes, podendo entrar no detalhe do mesmo.

- Detalhe do filme: 
Aqui sera exibido o titulo do filme, resumo e o poster, o usuário pode marca ele como favorito assim salvando o mesmo no banco de dados.

- Tela de favoritos:
Lista onde é exibido os filmes favoritados pelo usuário.

A UI fica a critério do desenvolvedor, mas que seja seguido a guideline de material design (https://material.io/components?platform=android)

