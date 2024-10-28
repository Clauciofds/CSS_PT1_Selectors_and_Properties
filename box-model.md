# Modelo de Caixa (Box Model) em HTML

Todos os elementos HTML podem ser considerados como uma caixa. Essa caixa possui diferentes áreas que podem ser estilizadas:

| Área       | Descrição                                 |
|------------|------------------------------------------|
| Margem     | Espaço transparente ao redor da caixa.     |
| Borda      | Linha que delimita a caixa.               |
| Padding    | Espaço transparente dentro da borda.      |
| Conteúdo   | Conteúdo real da caixa (texto, imagem). |

**Exemplo:**

```css
div {
  width: 794px;
  height: 160px;
  margin: 50px;
  border: 5px solid black;
  padding: 50px;
}