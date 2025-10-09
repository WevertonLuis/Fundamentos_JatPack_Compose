# App de Lista de Carros com Jetpack Compose

Este é um projeto de estudo para Android, desenvolvido com Kotlin e Jetpack Compose, que demonstra a criação de listas dinâmicas e interativas. O aplicativo exibe uma lista de modelos de carros clássicos e permite ao usuário filtrar a lista por montadora.

<img width="460" height="824" alt="image" src="https://github.com/user-attachments/assets/d0768744-b035-4901-a6f6-a89c1ca1d50a" />

<img width="457" height="818" alt="image" src="https://github.com/user-attachments/assets/974e2aab-d278-4112-82eb-f07c72df46b6" />




## ✨ Funcionalidades

-   **Listagem Dinâmica**: Exibe uma lista de carros usando `LazyColumn`.
-   **Filtro por Montadora**: Permite filtrar os carros pelo nome da montadora (fabricante).
-   **Busca Interativa**: O filtro pode ser aplicado de duas formas:
    1.  Digitando no campo de busca.
    2.  Clicando no card da montadora em uma lista horizontal (`LazyRow`).
-   **Limpar Filtro**: Opção para remover o filtro aplicado e restaurar a lista completa.

## 🛠️ Tecnologias Utilizadas

-   **[Kotlin](https://kotlinlang.org/)**: Linguagem de programação principal.
-   **[Jetpack Compose](https://developer.android.com/jetpack/compose)**: Toolkit de UI moderno para Android.
    -   Gerenciamento de estado com `remember` e `mutableStateOf`.
    -   Listas eficientes com `LazyColumn` e `LazyRow`.
    -   Componentes do Material Design 3 (`Card`, `OutlinedTextField`, `Scaffold`).
