# digituDownload arduino IDE (http://www.arduino.org/downloads)
Download a biblioteca (https://github.com/adafruit/Adafruit-Fingerprint-Sensor-Library)
Instale a biblioteca (https://www.arduino.cc/en/Guide/Libraries)

Ligue o sensor conforme o esquema abaixo:

Sensor		Arduino
=======        ========
Red	<—-> 	5v
Green	<—-> 	Digital2
White	<—-> 	Digital3
Black	<—-> 	GND

Carregue o código de exemplo da biblioteca chamado ENROLL ele permite cadastrar digitais (cadastre a sua digital) no monitor serial, tenha certeza de que a opção “Nova-linha” está selecionada na caixa ao lado da velocidade.

Carregue o código de exemplo da biblioteca chamado FINGERPRINT, ele deve reconhecer a sua digital recém cadastrada.