# Teste de PSI 1 - Turno 2 - Versão 2

## Informação do aluno

    Nome: Lucas Fernandes de Araújo

Teste termina às 13:25.

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    ulong uL = ulong.MaxValue;

    Console.WriteLine(uL + 1);

P1 - Resposta

    0, Isso ocorre quando você tenta adicionar um valor que ultrapassa o máximo representável.

### P2. Considera o seguinte código com um *bug*

    float f = double.MaxValue;

    Console.WriteLine(f);

### Indica uma possível correção para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    float f = (float)double.MaxValue;

    Console.WriteLine(f); 

### P3. Escreve um programa que solicite ao utilizador dois números reais e apresente o resultado do segundo (base) elevado ao primeiro (expoente). Não podes usar um método da classe Math para obter o resultado

P3 - Resposta

    ...

### P4. Estás na pasta raiz do teu repositório local, onde atualizaste um ficheiro de nome 'Perks.cs'. Queres enviar **apenas** esta atualização para o teu repositório remoto. Indica os comandos necessários. A mensagem de commit deve ser apropriada

P4 - Resposta

    git commit -m "Atualização do Perks" 
    git push origin main 
