# PhoneInfoga
PhoneInfoga  Una de las herramientas más avanzadas para escanear números de teléfono utilizando solo recursos gratuitos. El objetivo es recopilar primero información básica como país, área, operador y tipo de línea en cualquier número de teléfono internacional con muy buena precisión.

$apt update && apt upgrade -y

$termux-setup-storage

$pkg install -y python

$pkg install -y python2

$pkg install python3

$pkg install -y git

​$git clone https://github.com/sundowndev/PhoneInfoga

ABRIR NUEVA SESIÓN PEGAR TODO ESO

$clear && echo -e '\033[1;32m[*] Download starting...' && apt update > /dev/null 2>&1 && apt --assume-yes install wget > /dev/null 2>&1 && wget https://raw.githubusercontent.com/ExpertAnonymous/PhoneInfoga/master/phoneinfoga.sh -q && clear && bash phoneinfoga.sh

REGRESAR A LA SESION ANTERIOR

$cd PhoneInfoga

$pip install -r requirements.txt

$cd config.example.py config.py

$chmod +x phoneinfoga.py

$python3 phoneinfoga.py

LISTO AQUI DEBES ESCRIBIR EL SIGUIENTE COMANDO CON EL NÚMERO DE LA VÍCTIMA SIN EL ( + ) EJEMPLO:

$python3 phoneinfoga.py -n 541111111111
