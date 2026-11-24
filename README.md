# Coração Multilíngue de Amor ❤️

Um experimento de arte tipográfica generativa em Python que cria uma silhueta de coração composta pela frase “Eu te amo” em 20 idiomas diferentes, com animações suaves de flutuação e um discreto efeito de brilho.

## Recursos
- **Contorno paramétrico do coração:** utiliza uma curva paramétrica para calcular os limites exatos das linhas de varredura e o posicionamento dos textos.
- **Tipografia multilíngue:** alterna dinamicamente frases de amor em 20 idiomas, com escalas proporcionais de fonte.
- **Animação suave:** transições verticais de entrada com suavização cúbica (`cubic ease-out`) e gradação de cores do vermelho-escuro até as bordas iluminadas.
- **Brilho pós-renderização:** pequenas cintilações contínuas aparecem aleatoriamente nas frases após a conclusão do desenho.
- **Nenhuma dependência externa:** utiliza apenas a biblioteca padrão do Python (`turtle`, `tkinter`, `math`, `random`).

## Como executar

No PowerShell, dentro da pasta do projeto, execute:

```powershell
python love.py
```

Se o comando `python` não estiver configurado no Windows, você pode usar o caminho completo do interpretador ou desativar o alias da Microsoft Store para Python nas configurações de **Aplicativos > Aliases de execução**.
