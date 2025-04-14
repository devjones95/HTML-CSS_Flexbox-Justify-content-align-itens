# Flexbox: Entendendo `justify-content`, `align-items` e `align-self`

Flexbox é um modelo de layout poderoso no CSS usado para alinhar e distribuir espaço entre os itens dentro de um contêiner. Aqui vamos falar sobre três propriedades importantes:

---
<hr>
 ##🔹 `justify-content`

Controla o **alinhamento horizontal** dos itens dentro de um contêiner flexível (no eixo principal, que por padrão é horizontal).

### Valores mais usados:
- `flex-start` → alinha os itens no início
- `flex-end` → alinha os itens no final
- `center` → centraliza os itens
- `space-between` → distribui com espaçamento entre os itens
- `space-around` → distribui com espaçamento ao redor dos itens
- `space-evenly` → distribui com espaçamento igual entre e ao redor dos itens


.container {
  display: flex;
  justify-content: center;
}

Controla o alinhamento vertical dos itens dentro do contêiner (no eixo transversal).

Valores mais usados:
stretch → estica os itens para preencher o contêiner (padrão)

flex-start → alinha no topo do contêiner

flex-end → alinha na parte inferior

center → centraliza verticalmente

baseline → alinha com base na linha de base do texto.<br>
.container {
  display: flex;
  align-items: center;
}
<hr>

##🔹 align-self 
Permite que um item individual tenha um alinhamento diferente do align-items aplicado no contêiner.

Exemplo:<br>
.item {
  align-self: flex-end;
}

