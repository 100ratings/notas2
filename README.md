# Notas, ANIMAIS, versão 3

Primeira versão completa do efeito, baseada no ZIP original que funcionou melhor no iPhone 12 Pro Max

## Como usar

1. Na tela de notas, toque em **Buscar**
2. Digite exatamente **duas teclas** para codificar a posição, a tela mostrará **A**, depois **AN**
3. Toque em **ANIMAIS** e deslize até a posição desejada
4. Toque no botão **amarelo ✓**, aguarde 5 segundos, o emoji da Joaninha desaparecerá, sem mexer na palavra ou na posição dos outros animais
5. Toque na seta de **voltar** para restaurar o emoji e reiniciar

## Teclas secretas

I=1, O=2, P=3, J=4, K=5, L=6, B=7, N=8, M=9, qualquer outra tecla=0

- `OP` = 23
- `QP` = 03 = 3
- `IQ` = 10
- `MM` = 99
- `QQ` = 00 = 100

## Personalizar notas falsas

Edite a variável `FAKE_NOTES` no `index.html`: cada nota contém um título em MAIÚSCULAS, prévia e texto

## Publicar no GitHub Pages

Envie todos os arquivos deste ZIP à raiz do repositório, substituindo os antigos, e habilite GitHub Pages a partir da branch `main`, raiz `/`

No Safari, use **Compartilhar > Adicionar à Tela de Início**

## Observações

- A lista é ordenada e numerada de 1 a 100, sem itens duplicados
- Apenas o emoji 🐞 desaparece, após 5 segundos e somente depois de tocar no check
- A rolagem é preservada, mas a experiência exata no Safari do iOS 26 deve ser conferida no aparelho real
- O código não acessa notas verdadeiras do iPhone
- Os arquivos são autocontidos, sem bibliotecas externas
