# Desafio


Implementar uma aplicação para armazenar dados de artistas e músicas preferidos em um banco de dados relacional, podendo buscar informações por artistas e consultar dados sobre os mesmos através de integração com a API do ChatGPT.

- Precisará de uma classe Artista, com os dados para representar o mesmo;
- Será necessário também uma classe específica para representar as músicas;
- Para o artista, pode praticar a implementação de *enum*, para definir o tipo do artista, por exemplo: solo, dupla ou banda;
- Criar uma classe principal com o menu, com as opções desejadas, como: cadastrar artista, cadastrar música, pesquisar músicar por artistas, etc;
- Estender o CommandLineRunner na classe do Spring, sobrescrevendo o método *run* para chamar o menu criado.



## 🔨 Objetivos do projeto

- O objetivo do projeto é praticar a modelagem de classes e relacionamentos utilizando o Spring Data JPA;
- É importante descrever e implementar corretamente a relação entre Artista e Música, visto que um artista pode estar associado a mais de uma música;
- Uma música só deve ser salva no banco de dados, caso o Artista tenha sido previamente cadastrado;
- Praticar *derived queries* e *JPQL* para verificar se o artista já está cadastrado e buscar músicas por um determinado artista;
- Integrar com a API do ChatGPT para buscar informações sobre um determinado artista.

