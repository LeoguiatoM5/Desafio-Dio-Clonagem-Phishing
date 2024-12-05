# Desafio-Dio-Clonagem-Phishing


# Social Engineer Logs - Instagram Attack

## Descrição
Este repositório contém os logs gerados durante o ataque de **Credential Harvesting** utilizando o Social-Engineer Toolkit (SET) para a clonagem do site de login do Instagram.

## Passos Realizados



Iniciar o SET: No terminal, execute o comando:

setoolkit
Selecionar o tipo de ataque:

Escolha a opção Social-Engineering Attacks digitando o número correspondente e pressionando Enter.
Em seguida, escolha o vetor de ataque Web Site Attack Vectors.
Escolher o método de ataque:

Escolha Credential Harvester Attack Method para capturar credenciais.
Selecione Site Cloner para clonar uma página legítima.
Configurar o endereço da máquina:

Use o comando ifconfig para encontrar o endereço IP da sua máquina. Geralmente estará na interface eth0 (para rede cabeada) ou wlan0 (para Wi-Fi).
Informe o IP quando o SET solicitar o "IP address for the POST back".

Clonar o site:

Insira a URL do site que deseja clonar (exemplo: https://example.com).

 O SET gerará os logs na pasta .set/reports/

## Observações
- Certifique-se de realizar o ataque apenas em ambientes de testes e com permissão explícita.
