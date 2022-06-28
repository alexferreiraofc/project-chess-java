<h1 align="center">
  :trophy: Chess System Java
</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#%EF%B8%8F-instalacao">Instalação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#%EF%B8%8F-imagens">Imagens</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

## 🚀 Tecnologias 

Esse projeto foi desenvolvido com as seguintes tecnologias:

- Java
- IntelliJ

## 💻 Projeto
  Este projeto foi desenvolvido com base no curso  *__Java COMPLETO 2022 Programação Orientada a Objetos + Projetos__* da [Udemy](https://www.udemy.com/course/java-curso-completo/). Esta aplicação consiste em um jogo simples de Xadrez, que pode ser executado através do terminal. O jogo possui tratamento de erros, programação defensiva (contra bugs), jogadas especiais do xadrez (promoção, roque e en passant) e previsão de movimento das peças.
  
Peças: Pawn (Peão), Rook (Torre), Knight (Cavalo), Bishop (Bispo), Queen (Rainha) e King (Rei).
|-|

 A mecânica do jogo é baseada em **linhas** (_1, 2, 3, 4, 5, 6, 7, 8_) e **colunas** (_a, b, c, d, e, f, g, h_)
- Para **escolher** uma peça é necessário selecionar _primeiramente_ a **coluna** e logo em seguida (sem espaços) selecionar a **linha**, exemplo: **c2**
- Em **Captured pieces** o jogo armazena as peças capturadas.
- O **Turn** exibe o turno (rodada) em que o jogo está.
- **Waiting player** exibe qual é o jogador a jogar a próxima peça.
- **Source** é a origem, ou seja, a peça no qual o jogador irá jogar.
- **Target** é o destino, ou seja, o local no qual o jogador irá mover a peça.
- O jogo possui sistema de **Check** e **CheckMate**
- O jogo também possui o sistema de **promoções** do **Pawn**
- Incluído jogadas especiais como En **Peasant** e **Roque**
  
## ♟️ Instalacao

1. Faça o dowload e extração do projeto. 
2. Abra um terminal ([Git Bash](https://git-scm.com/book/pt-pt/v2/Appendix-A%3A-Git-em-Outros-Ambientes-Git-in-Bash) é o recomendado, pois é colorido)
3. Entre no diretório Chess/out/production/Chess do projeto (comando: cd Chess/out/production/Chess)
4. Após entrar no diretório, digite java application/Program para rodar a aplicação (O java precisa estar na versão 11 ou superior).
5. Bom Jogo!

## 🖼️ Imagens

| Tela Inicial  | Tratamento de Erro | Check | 
|---|---|---|
| ![tela-inicial](https://user-images.githubusercontent.com/54365007/90513167-9787d800-e135-11ea-8a35-ebf67854ea14.PNG)  | ![tratamento-erro](https://user-images.githubusercontent.com/54365007/90513194-9f477c80-e135-11ea-8383-9f3515959954.PNG)  | ![check](https://user-images.githubusercontent.com/54365007/90513197-9fe01300-e135-11ea-9fc8-5beef82c6557.PNG)  | 

| Jogada Roque (Castling)  | Jogando... | Jogadas Finais | 
|---|---|---|
| ![rook-moving](https://user-images.githubusercontent.com/54365007/90513202-a078a980-e135-11ea-8156-e130702f7b64.PNG)  | ![jogo-continuo](https://user-images.githubusercontent.com/54365007/90513198-9fe01300-e135-11ea-9626-a02c3bb40636.PNG)  | ![late-game](https://user-images.githubusercontent.com/54365007/90513199-a078a980-e135-11ea-8b69-9590e1f11081.PNG)  | 

## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
