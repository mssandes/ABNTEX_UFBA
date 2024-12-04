# ABNTEX_UFBA
Personalizações para o estilo UFBA

Comandos para capa:
```latex
    \instituicao{Instituição}
    \faculdade{Departamento}
    \programa{Programa}
    \tipotrabalho{Ph.D. Thesis}
```
Uma sigla/abreviatura é chamada pelo comando `\gls{fgts}`. Na primeira aparição no documento será exibido: Fundo de Garantia por Tempo de Serviço (FGTS) no texto, e a entrada será registrada na lista de abreviaturas com a página de ocorrência. Nas demais aparições só será exibida a sigla conforme definido no arquivo `Cap_00_vi_SiglasSimbolos`, exemplo:

`\newacronym{fgts}{FGTS}{Fundo de Garantia por Tempo de Serviço}`

Para o caso de símbolos:
`\newglossaryentry{eta}{type=symbols,name=\ensuremath{\eta},sort=p,description={Pseudorapidity}}`

A entrada `sort=p` definie uma letra para que o compilador observe na ordenação. O comando `\ensuremath{}` garante a formação no ambiente matemático.
