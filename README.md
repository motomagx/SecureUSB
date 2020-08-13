# SecureUSB

SecureUSB é um projeto OpenSource de um simples protertor conta surtos de tensão, protegendo dispositivos USB 2.0 contra discargas elétricas, como transientes eletrônicos e para evitar riscos de queima dos aparelhos, vítima sdo USB Killer.<br><br>

Funcionamento:<br><br>

-A linha de tensão de 5V e os terminais de TX/RX possuem diodos em série e capacitores em paralelo.
-Caso a entrada (à direita) receber uma sobrecarga de 5.5V ou mais (valor delimitado pelos diodos zener), ocorrerá uma sobrecarga de corrente, fazendo o fusível respectivo a se romper, e desabilitando esta linha (VCC ou DATA), protegendo o host de dados elétricos. O memso ocorre caso o host receba a conexão de um dispositivo maliciosos na expectativa de causar uma discrga elétrica no aparelho.
