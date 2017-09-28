## Possível correção para o TEXMAKER

Após alguma pesquisa encontrei esse post no _StackExchange_ comentando sobre
esse mesmo erro.  [Link para o forum](https://tex.stackexchange.com/questions/84357/new-installation-texmaker-quick-build-says-could-not-start-the-command?rq=1)

Realmente somente com o __TEXMAKER__ não seria possível compilar uma vez que
ele não tem o "código fonte" do LaTeX que é capaz de gerar os documentos. 
 
Faz-se então necessário instalar ou o __MikTeX__ ou __Tex Live__, uma ressalva
a ser feita é de que caso opte pelo Miktex é necessário instalar como
__user-mode__ devido a problemas relacionados com a conexão com a internet.

No link acima também tem explicações para algumas diferenças entre o Miktex e o
Tex Live, as quais considera o Tex Live mais seguro quando a malwares.  

Para fazer download do miktex use o link
[Miktex distribution](https://miktex.org/download)

> Atenção: selecione a versão correta para seu sistema operacional e siga os
> passos nesse tutorial [tutorial](https://miktex.org/howto/install-miktex)

Para fazer download do Tex Live use o link 
[Tex Live distribution](https://www.tug.org/texlive/)

> Atenção: faça download do arquivo relacionado ao seus sistema operacional e
> caso aconteça algum problema leia a documentação no link [documentação do Tex
> Live](https://www.tug.org/texlive/windows.html)

--- 

> Após fazer o download e instalação da distribuição (Miktex ou Tex Live) é recomentado
> reinstalar o TEXMAKER para que esse identifique automaticamente o caminho
> para o código fonte do LaTeX. 

Após realizar esse procedimento é provável que seja possível compilar o arquivo __.tex__ sem
maiores problemas.

---

# LaTeX Básico

> Paulo Conci

LaTex que é pronunciado _Lah-tech_ ou _Lay-tech_ <sup>1</sup>, é um linguagem para escrita
e edição de texto, usualmente longos textos científicos, porém pode ser usado
basicamente para qualquer texto.

LaTeX é baseado na ideia de que é muito melhor deixar o design do documento com
os designers, e o autor do documento se preocupar com o conteúdo do texto.

#### Características do LaTeX
* Escrever artigos científicos, livros, relatórios técnicos, apresentação de
  slides;
* Facilidade em controlar grandes documentos em seções, _cross-references_,
  tabelas e figuras;
* Escrever equações matemáticas complexas facilmente;
* Geração automática de referências, bibliografia e índex.
* Escrita multilíngue;
* Usa PostScrip e Metafont fontes.

---
## Como Começar 

Para a criação de textos utilizando LaTeX é necessário um editor de texto capaz
de compilar a linguagem. Existem vários atualmente, porém recomendo a
utilização do __TEXMAKER__, devido entre outras vantagens a possibilidade de
visualizar o PDF no próprio programa. 

No link abaixo, é possível encontrar o __TEXMAKER__ para as várias plataformas, e
após o download, sua instalação é bem direta e simples.

Link para download: [TEXMAKER](http://www.xm1math.net/texmaker/download.html)

#### Para Gerenciamento de Referências

Para que seja possível automatizar o processo de referências, é recomendado a
utilização do __Mendeley__, sendo este capaz de organizar os arquivos
existentes em seu computador.

Link para download: [Mendeley](https://www.mendeley.com/download-mendeley-desktop)

> Será __necessário__ criar uma conta, para que esta faça backup de todas as suas
> referências e seja possível logar no programa.

---
## Materiais para o minicurso

Link para modelo canônico da ABNT
[Modelo ABNT](https://github.com/abntex/abntex2/wiki/Download)
> Fazer download do arquivo compactado __abntex2-modelos-1.9.6.zip__ 

Este modelo será utilizado como ponto de partida para a formatação do trabalho
acadêmico durante o minicurso. 

---

## Vantagens

Prático, rápido e extensível.

## Contato

Email: pauloagconci@gmail.com

## Fontes

(1) [LaTeX org](https://www.latex-project.org/about/)

[Lista de pacotes](https://www.ctan.org/pkg)

[LaTex wiki book](https://en.wikibooks.org/wiki/LaTeX)

[LaTeX Stackexchange](https://tex.stackexchange.com/)

[LaTeX Community](http://latex.org/forum/)

[Google](https://www.google.com/)
