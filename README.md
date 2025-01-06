# KONTAKT LIBRARY MANAGER

O Kontakt é um sampler de software desenvolvido pela Native Instruments. Ele é amplamente utilizado na produção musical e permite que músicos e produtores criem e manipulem instrumentos virtuais através da amostragem de sons reais. Eu inclusive faço muito uso deste software.
O software disponibiliza um aplicativo próprio para gerenciamento das livrarias que realiza a importação, entretanto, que só funciona com as livrarias registradas da Kontakt e que são pagas. Eu constumo criar minhas próprias livrarias, com teclados que tenho a oportunidade de tocar, e por possuir recursos de gravação digital, crio meus próprios samplers, e para facilitar, crio minhas bibliotecas para organizar esses samplers que crio.

Utilizava um software de terceiro, disponível na internet, entretanto, a cada importação, é necessário fechar e abrir novamente o software, o que custa bastante tempo, uma vez que crio muitas bibliotecas com muita frequência, e importar uma a uma já é ruim, tendo que ficar reabrindo o software torna-se pior ainda. 
Motivado por esta dificuldade, e estudando programação em python, pensei, por que eu não desenvolvo um Library Manager próprio?

Inicia-se o estudo, como o Kontakt encontra as bibliotecas importadas. Após algumas semanas, entendi o funcionamento, o Kontakt carrega as bibliotecas que são importadas no registro do Windows, em três locais diferente. Com tudo isso em mãos, e relembrando os comandos para importação de registro para o regedit no Windows, já tenho tudo o que preciso para começar a desenvolver.
Após cerca de uma semana, o software toma forma, onde posso importar quantas bibliotecas que quiser, sem a necessidade de ficar reabrindo a aplicação. Surge o Library Manager totalmente funcional, desenvolvido em python.

Aplicando o mesmo padrão do MultiConversor, as imagens da interface do software, estão embutidas no .exe, utilizando o resource_rc.

![image](https://github.com/user-attachments/assets/213405d8-e022-4b67-9b33-9206a914645f)

E assim, desenvolvo mais um software para atender minhas necessidades do dia, e que também tem o poder de ajudar muitas pessoas.
