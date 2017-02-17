# Modelo de monografia
Modelo em LaTeX para monografias que pode ser utilizado na Universidade Estadual de Santa Cruz (UESC). Todas as informações de como preencher podem ser encontradas no arquivo modelo.tex. Esta classe foi desenvolvida pelo prof. Maxwell Mariano de Barros do DEMAT/UFMA, atualizada e adaptada por nós. (http://www.demat.ufma.br) 

(Este modelo é compatível com ShareLatex basta que se coloque o modelo.tex como documento principal no menu!)

# Funcionalidades extras
## Citações longas
```
\begin{citado}
Sua citação longa aqui.
\begin{citado}
```

## Comentários
```
\begin{coment}
Seu comentário aqui
\end{coment}
```

## Imagens com fonte
```
\begin{figure}[!htp]
    \centering
    \includegraphics[scale=0.1]{Images/logo.png}
    \captionsource{Legenda}{Fonte}
    \label{fig:label2}
\end{figure}
```
