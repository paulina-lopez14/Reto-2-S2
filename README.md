## Simulador de cajero automático
🏥 Reto 2 sesión 2 🏥

## 📌 Intro 
Este programa permite simular un cajero automático básico, aplicando estructuras de control como while, switch, break y continue para navegar entre opciones y validar operaciones del usuario.

## ✨ Instrucciones
🏗️ 1. Crea una clase llamada CajeroAutomatico.

💸 2.  En el método main, define un saldo inicial (por ejemplo: saldo = 1000.0), dicha variable deberá ser inferida por java.

📋 3. Muestra un menú interactivo en consola con las siguientes opciones:

Bienvenido al cajero automático
1. Consultar saldo
2. Depositar dinero
3. Retirar dinero
4. Salir
Puedes usar un do-while

🔁 4. El programa debe repetirse usando un while hasta que el usuario elija salir (opción 4).

🧠 5. Utiliza un switch para manejar las opciones:

✅ 1. Consultar saldo → Mostrar el saldo actual.
💰 2. Depositar dinero → Pedir monto a depositar y sumarlo al saldo.
💸 3. Retirar dinero → Pedir monto a retirar y:
⚠️ Validar si hay saldo suficiente.
❌ Si no hay suficiente, mostrar un mensaje y continuar sin restar.
👋 4. Salir → Mostrar mensaje de despedida y terminar el programa.
🧭 Controla el flujo con break y continue donde sea necesario.

## 📂 Estructura 
- CajeroAutomatico.java: Clase principal que contiene el main, mediante el uso de do-while muestra el menú interactivo y pide al usuario elegir una opción, adentro del do-while agregamos un switch para realizar la acción que el usuario requiera, el programa termina cuando el usuario ingresa la opción 4 "Salir".
  *Nota: para ocupar el scanner en el archivo CajeroAutomatico.java, se pone lo siguiente al inicio del archivo "import java.util.Scanner;"*

##  💻 Preview
Simulador farmacia
![image](https://github.com/user-attachments/assets/1fa0766a-70cd-4787-aeb4-032ca7d9df78)

![image](https://github.com/user-attachments/assets/13e6ae95-75cc-4525-9d52-598d7e148c7b)

![image](https://github.com/user-attachments/assets/3bf8539b-0c91-412b-99ab-c523035ac3f1)

Resultado
![image](https://github.com/user-attachments/assets/3161ec61-3296-4ada-a187-a1d62fcf9313)

## 🛠️ Tecnologías usadas
* Lenguaje: Java
* IDE: IntelliJ IDEA

## 📚 Recursos útiles
🔗 Material sesión 2 https://github.com/beduExpert/Java-Standar-Edition-1-2025/tree/main/Sesion-02 
