# 🦾 Projeto: Braço Robótico com LEGO MINDSTORMS EV3
Este projeto implementa o controle de um braço robótico utilizando o LEGO® MINDSTORMS® EV3 com MicroPython (Pybricks). O braço é capaz de pegar e mover pilhas de rodas entre três posições diferentes de forma contínua.

# 📦 Requisitos
LEGO® MINDSTORMS® EV3

Firmware LEGO EV3 MicroPython v2.0
# 📥 Download aqui

Estrutura montada com base nas instruções da LEGO
# 🔧 Instruções de montagem

# 🧠 Funcionalidades
Inicialização automática do braço robótico, base e garra.

Detecção de posição inicial usando sensores (toque e cor).

Movimentação suave dos motores com controle de aceleração.

Funções para pegar e liberar objetos em posições específicas.

Loop contínuo de movimentação entre as três posições: ESQUERDA, MEIO e DIREITA.

# ⚙️ Como funciona
O braço possui 3 motores:

Base (Porta C): gira o braço horizontalmente.

Cotovelo (Porta B): sobe e desce o braço.

Garra (Porta A): abre e fecha para pegar objetos.

Utiliza:

Sensor de Toque (Porta S1): identifica a posição inicial da base.

Sensor de Cor (Porta S3): identifica a posição inicial do cotovelo (detecção de cor branca).

A sequência de movimentos realiza uma troca contínua de posições entre pilhas de rodas.

# ▶️ Execução
Carregue o código no seu EV3 com Pybricks.

Ligue o EV3 e aguarde os três bipes de inicialização.

O robô começará a mover as pilhas de rodas automaticamente entre as posições pré-definidas.

# 🧾 Estrutura do Código
robot_pick(position): move o braço para uma posição, baixa o cotovelo, fecha a garra e levanta.

robot_release(position): move o braço para uma posição, baixa o cotovelo, abre a garra e levanta.

Posições:

LEFT = 160

MIDDLE = 100

RIGHT = 40


