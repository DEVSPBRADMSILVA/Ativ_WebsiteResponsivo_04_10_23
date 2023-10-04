# Meu Website Interativo

Este é um exemplo de um website interativo simples com HTML e CSS.

## Descrição

Este website possui as seguintes seções:

- Um cabeçalho com um título e um menu de navegação.
- Uma seção principal com uma imagem flexível.
- Seções sobre "Sobre Nós" e "Nossos Serviços" com informações sobre o Senac.
- Uma tabela de projetos.
- Uma barra lateral com links úteis.
- Um rodapé com informações de direitos autorais.

## Explicação do Código CSS

### Reset de estilos padrão

O código a seguir redefine os estilos padrão de elementos HTML para garantir um comportamento consistente em diferentes navegadores:

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
Estilos gerais
Definimos as fontes, cores e o plano de fundo geral do site:

body {
    font-family: Arial, sans-serif;
    background-color: #3498db; /* Cor de fundo */
    color: #fff;
}
Estilos para o cabeçalho
Estilizamos o cabeçalho do site, incluindo o posicionamento fixo na parte superior da página e o uso de flexbox para alinhar elementos:

header {
    background-color: #333; /* Cor de fundo do cabeçalho */
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Sombra suave para o cabeçalho */
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 100;
    padding: 20px; /* Espaçamento interno para o conteúdo do cabeçalho */
    display: flex; /* Usar flexbox para alinhar os elementos horizontalmente */
    justify-content: space-between; /* Alinhar os elementos ao espaço entre eles */
}
Estilos para a lista de navegação do cabeçalho
Estilizamos a lista de navegação no cabeçalho, alinhando os itens horizontalmente com flexbox:

header ul {
    list-style: none;
    padding: 0;
    display: flex; /* Usar flexbox para alinhar os itens horizontalmente */
}
E assim por diante...

Como Usar
Clone este repositório em seu computador:
git clone https://github.com/seu-usuario/seu-repositorio.git
Abra o arquivo index.html em um navegador da web para visualizar o website.

Você também pode personalizar o conteúdo e os estilos editando o arquivo CSS/styles.css.

Pré-requisitos
Um navegador da web para visualizar o website.
Autores
Adilson_|_Renato
Licença
Este projeto está licenciado sob a Licença ALUNOS_FULLSTACK SENAC-SP LARGO_13 - consulte o arquivo LICENSE para obter detalhes.
