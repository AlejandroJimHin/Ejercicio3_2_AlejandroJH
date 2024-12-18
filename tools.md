En mi componente he usado las siguientes librias:
- import java.util.Random;
- import javafx.fxml.FXML;
- import javafx.scene.control.Button;
- import javafx.scene.control.TextField;
- import javafx.scene.transform.Rotate;

Y las herramientas que he utilizado en mi componente han sido las siguientes:
Un evento que lo he asignado al boton, en el cual dentro de este hay dos objetos creados, uno de la 
clase Rotate y otro de la clase Random. El objeto de la clase Rotate ha sido utilizado para poder girar el TextField a la hora de pulsar el boton.
Y el objeto de la clase Random ha sido utilizado para generar un numero del 1 al 255 y al obtener el numero, utilizarlo en el RGB para poder generar
colores aleatorios.