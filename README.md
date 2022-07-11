<h1 align="center"> Drone </h1>
<p  align="center"> 
    This is a DIY drone based on the F450 quadcopter made with arduino. It will be controlled by the DIY remote control (radio) and by an mobile app (bluetooth). <br>
    :construction:  Project under construction  :construction:
</p>

<h2 align="center">  🔗 Resumo do projeto </h2>

- Será usado o controle remoto DIY para pilotar o drone (baseado em NRF24L01) ou o módulo HC-06 junto com um app par android feito no MIT App Inventor.
- É necessário bateria lipo por ser mais potente que as demais, necessário para alimentação dos motores que são bem fortes para levantar o drone.
- Os ESCs serão os controladores dos motores, como se fossem pontes-h.
- Através do acelerômetro/giroscópio de 3 eixos MPU6050 será medido a angulação do drone, para que ele fica estável no ar.
- Para fazer o controle, será usado o PID controller (controlador proporcional integral derivativo).
- Terá um medidor da tensão da bateria para que ela nunca fique abaixo do nível crítico, que também apitará caso isso aconteça, além de mostrar a tensao atual.

<h2 align="center">  📁 Descrição dos arquivos </h2>

- Drone-main.ino -> arquivo que fica o programa principal
- diagrama.fzz -> arquivo que fica todas as ligações do projeto

<h2 align="center">  🛠️ Lista de itens </h2>

- 1 frame 450 quadcopter
- PCB desenvolvida em software e fabricada
- Arduino nano
- 4 brushless motors 920kv
- 4 esc 30A
- 4 hélices
- 1 MPU6050
- 1 NRF24L01
- 1 HC-06
- 1 bateria lipo 3s 11.1v ?mAh ?C
- Medidor e sinalizador de nível da bateria
- Resistores, capacitor, diodo, parafusos, porcas, borne KRE 2 vias, barras de pinos macho e fêmea, fios, solda, XT-60, velcro, abraçadeira.

<h2 align="center">  ✔️ Técnicas e tecnologias utilizadas </h2>

- ``Arduino``
- ``C++``
- ``POO``
- ``PID controller``
