# Instruções:
## Criar uma página de documentação técnica
### Objetivo: criar uma aplicação que funcione de modo semelhante a https://technical-documentation-page.freecodecamp.rocks

### Histórias de usuário:

1. Deve haver um elemento main com um id="main-doc" correspondente, que contenha o conteúdo principal da página (documentação técnica)
2. Dentro do elemento #main-doc, deve haver vários elementos section, cada um com a classe main-section. Deve haver, pelo menos, cinco
3. O primeiro elemento de cada .main-section deve ser um elemento header que contenha o texto que descreve o tópico daquela seção.
4. Cada elemento section com a classe main-section também deve ter um id que corresponda ao texto de cada header contido dentro dela. Os espaços existentes devem ser substituídos por sublinhados (por exemplo, a seção que contém o cabeçalho "JavaScript e Java" deve ter um id="JavaScript_and_Java")
5. Os elementos .main-section devem conter, juntos, pelo menos dez elementos p no total (não 10 para cada elemento)
6. Os elementos .main-section devem conter, juntos, pelo menos cinco elementos code no total (não 5 para cada elemento)
7. Os elementos .main-section devem conter, juntos, pelo menos cinco elementos li no total (não 5 para cada elemento)
8. Deve haver um elemento nav com um id="navbar" correspondente
9. O elemento da barra de navegação (navbar) deve conter um elemento header que contenha o texto que descreve o tópico da documentação técnica
10. Além disso, a barra de navegação deve conter elementos de âncora (a) com a classe nav-link. Deve haver um para cada elemento com a classe main-section
11. O elemento header em #navbar deve vir antes de qualquer elemento de link (a) na barra de navegação
12. Cada elemento com a classe nav-link deve conter um texto que corresponda ao texto do header dentro de cada section (exemplo: se você tem uma seção/cabeçalho "Olá mundo", sua barra de navegação deve ter um elemento que contenha o texto "Olá mundo")
13. Ao clicar em um elemento da barra de navegação, a página deve navegar para a seção correspondente do elemento #main-doc (exemplo: ao clicar em um elemento .nav-link que contenha o texto "Olá mundo", a página deve navegar para o elemento section que tenha esse id e contenha o cabeçalho correspondente)
14. Em dispositivos com tamanho regular (laptops, desktops), o elemento com id="navbar" deve ser mostrado no lado esquerdo da tela e deve sempre estar visível para o usuário
15. A documentação técnica deve utilizar pelo menos uma media query
16. Atenda às histórias de usuário e passe em todos os testes abaixo para concluir este projeto. Dê ao projeto o seu próprio estilo pessoal. Boa programação!

Observação: não se esqueça de adicionar <link rel="stylesheet" href="styles.css"> em seu HTML para vincular sua folha de estilo e aplicar seu CSS