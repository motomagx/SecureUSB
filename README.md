# SecureUSB

SecureUSB é um projeto OpenSource de um simples protertor conta surtos de tensão, protegendo dispositivos USB 2.0 contra descargas elétricas, como transientes eletrônicos e para evitar riscos de queima dos aparelhos, vítima do USB Killer.<br><br>

Funcionamento:<br><br>

-A linha de tensão de 5V e os terminais de TX/RX possuem diodos em série e capacitores em paralelo.
-Caso a entrada (à direita) receba uma sobrecarga de 5.5V ou mais (valor delimitado pelos diodos zener), ocorrerá uma sobrecarga de corrente, fazendo o respectivo fusível a se romper, desabilitando esta linha (VCC ou DATA), protegendo o host de danos elétricos.<br><br>

-Um LED na linha de VCC indica tensão operacional.<br><br>

-O mesmo ocorre caso o host receba a conexão de um dispositivo maliciosos na expectativa de causar uma descarga elétrica no aparelho.<br><br>

-O projeto em anexo possui os layouts de PCB em formato Gerber para pronta produção, e o arquivo esquemático em Fritzing estará disponível em breve.<br><br>

Revisões:<br><br>

1.0: Lançamento inicial.
