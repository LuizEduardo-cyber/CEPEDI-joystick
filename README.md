# Conversor com joy stick 🚀

Esse projeto faz uso do joy stick que tem vomo função movimentar um quadrado na tela do display e mudara frequencia do led azul e vermelho, e ao pressionar o joy stick ele faz um animção com um retangulo na tela do display e alterna estado do led verde.

## Hardware 🛠️

- Microcontrolador RP2040 (Raspberry Pi Pico).
- display.
- joy stick.
- LED RGB.

## Software 💻

* **SDK do Raspberry Pi Pico:** O SDK (Software Development Kit) do Pico, que inclui as bibliotecas e ferramentas necessárias para desenvolver e compilar o código. [Instruções de instalação](https://www.raspberrypi.com/documentation/pico/getting-started/)
* **CMake:** Um sistema de construção multiplataforma usado para gerar os arquivos de construção do projeto.
* **Compilador C/C++:**  Um compilador C/C++ como o GCC (GNU Compiler Collection).
* **Git:** (Opcional) Para clonar o repositório do projeto.


### O código está dividido em vários arquivos para melhor organização:

- **`ADC_DisplayC.c`**: Código que tem como função
- **`CMakeLists.txt`:** Define a estrutura do projeto para o CMake.



## Como Compilar e Executar ⚙️

1. **Instale o SDK do Raspberry Pi Pico:** Siga as instruções no site oficial do Raspberry Pi.
2. **Clone este repositório:** `https://github.com/LuizEduardo-cyber/CEPEDI-joystick.git`
3. **Navegue até o diretório do projeto:** `cd CEPEDI-joystick`
4. **Compile o projeto:** `cmake -B build && cmake --build build`
5. **Copie para o Pico:** Copie o conteúdo da pasta `build` (gerada após a compilação) para o Raspberry Pi Pico. O programa iniciará automaticamente.

## Próximo Passos ➡️

- fazer um jogo da cobrinha no display.
- quando movimentar o joy stick mudar a frequenica das tres cores ao mesmo tempo.
  
 ## 🔗 Link do Vídeo de Funcionamento:
https://drive.google.com/file/d/1PT7HQALPs8PjhMQnsvt4F8gI7Q_qn7_d/view?usp=drive_link

 ## Contribuições 🤝

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📞 Contato

- 👤 **Autor**: Luiz Eduardo Soares Ferreira.
 
- 📧 **E-mail**: luizeduardosoaresferreira942@gmail.com 

--- 
