# 📊 Funções dos Sistemas Operacionais - Inicialização

O sistema operacional tem como uma de suas funções a inicialização do computador, seguidas por esses passos:

**Passo 1**: É fornecido energia elétrica para as diferentes partes do sistema.

**Passo 2**: O processador procura a BIOS\( _Firmware que contém as instruções de inicialização do computador_\).

**Passo 3**: A BIOS realiza o POST, o qual são verificados o mouse, teclado , conectores e placas de expansão.

**Passo 4**: É feita a comparação dos resultados do POST com os dados armazenados no _chip CMOS\(armazena informações de configuração do computador e também detecta novos dispositivos conectados\)_.

**Passo 5**: O BIOS procura os arquivos do sistema no drive A \(disco flexível\) e, em seguida, no drive C \(disco rígido\).

**Passo 6**: O programa de boot carrega na RAM o kernel do SO \(armazenado no HD\), o qual assume, a partir de então, o controle do computador.

**Passo 7**: O SO carrega informações de configuração, exibe a área de trabalho \(desktop\) na tela e executa programas na pasta Iniciar \(StartUp\).

