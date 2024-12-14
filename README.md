# desafio_modulo5

El presente proyecto tiene por objectivo instanciar un EC2 de AWS a partir de un workflow de Github Actions, con el cuál después se crea una imagen para uso posterior.

El EC2 configurado es uno simple, donde se utiliza una instancia t2.micro (tier gratuito), se le asigna una ip pública, un grupo de seguridad, una subred asociada y una llave previamente creada.
El grupo de seguridad sólo tiene acceso por el puerto 22 para conección SSH desde cualquier dispositivo.

Dado que la idea es probar la creación de la instancia por la herramienta de actions y AWS CLI, se optó por una máquina simple a la que pudiera accederse a través de SSH, logrando el resultado esperado.

