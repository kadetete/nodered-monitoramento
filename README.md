# nodered-monitoramento
Exercício de monitoramento em tempo real: NodeRED

- O aplicativo através de um nó simples de inject envia dados de tempo para uma função, que a formata em um json, separando data/hora de um outro campo chamado texto.

- A mensagem é enviada para um tópico mqtt.

- Após receber a mensagem, o aplicativo verifica se a data/hora contém o número 12. Caso contenha tal número, substitui o bom dia por um 'boa noite'.

- Exibe os dois parametros numa dashboard através do nó Text.