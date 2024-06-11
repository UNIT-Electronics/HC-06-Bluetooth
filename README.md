## Bluetooth HC-06 Esclavo

En este repositorio encontrarás el código y diagrama de conexión 📄📚🔌.

### Diagrama de Conexión 🔌

Asegúrate de realizar las siguientes conexiones entre el Arduino UNO y el Bluetooth HC-06 Esclavo🔌⬅️📟.

![Display LCD](https://github.com/UNIT-Electronics/HC-06-Bluetooth/blob/main/Bluetooth%20HC-06%20Conexion%20con%20Arduino%20UNO.jpg)

### Código de Funcionamiento🧾

Para que este código funcione, no necesitas instalar librerías adicionales, ya que SoftwareSerial.h viene incluida en el IDE de Arduino. 😃

Puedes configurar los siguientes parámetros para tu próximo proyecto en la sección correspondiente del código:

1. **Nombre del dispositivo:** 

```arduino
char NOMBRE[21] = "My-hc06"; // Aquí puedes cambiarle el nombre a tu BLUETOOTH, solo puedes usar 20 caracteres como maximo 

```
2. **Velocidad de comunicación:** 

```arduino
char BPS = '4'; // 1=1200 , 2=2400, 3=4800, 4=9600, 5=19200, 6=38400, 7=57600, 8=115200 , Selecciona un numero para definir los baudios 

```
3. **Contraseña de emparejamiento:** 

```arduino
char PASS[5] = "0000"; /* PIN o CLAVE de 4 caracteres numéricos, no exceder los 4 caracteres, para mejor funcionamiento dejar la contraseña en "0000"*/ 
```

### Contribuir al Repositorio 🤗

Si encuentras algún problema o tienes una mejora para este repositorio, te invitamos a realizar un pull request. Para hacerlo, sigue estos pasos:

1. **Haz un Fork de este repositorio**: Haz clic en el botón "Fork" en la parte superior derecha de esta página para crear una copia del repositorio en tu cuenta de GitHub.

2. **Clona el repositorio forked**: Clona el repositorio a tu máquina local usando el siguiente comando:

```sh
git clone https://github.com/tu-usuario/nombre-del-repositorio.git
 ```
   
3. **Crea una nueva rama:** Crea una nueva rama para tus cambios:

```sh
git checkout -b nombre-de-tu-rama
```
   
4. **Realiza tus cambios:** Realiza los cambios necesarios y commits:

```sh
git add .
git commit -m "Descripción de los cambios"
```

5. **Envía los cambios a tu repositorio forked:** Empuja los cambios a tu repositorio en GitHub:

```sh
git push origin nombre-de-tu-rama
```

6. **Abre un Pull Request:** Ve a la página del repositorio original en GitHub y abre un Pull Request desde tu rama recién creada.

#### Apreciamos tus contribuciones y esperamos trabajar juntos para mejorar este repositorio. ¡Gracias por tu colaboración!
