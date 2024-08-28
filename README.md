# nodered-monitoramento
Exercício de monitoramento em tempo real: NodeRED

- O aplicativo através de um nó simples de text input envia dados de texto para uma função, que a formata em um json, separando data/hora de um outro campo chamado texto.

- A mensagem é enviada para um tópico mqtt.

- Após receber a mensagem, o aplicativo verifica se a data/hora contém o número 8. Caso contenha tal número, substitui a data por uma mensagem '8 presente'.

- Verifica também se a mensagem contém 'Bom dia', caso contenha o troca por 'Boa noite', emitindo também um alerta.

- Exibe ambas as informações num text do dashboard.

- Recebe dados de frases aleatórias de uma api e exibe na tela.