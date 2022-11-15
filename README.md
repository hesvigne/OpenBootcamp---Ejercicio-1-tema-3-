# OpenBootcamp---Ejercicio-1-tema-3-
Ejercicio del curso Introducción a la programación - Tema 3
package ejercicio1;

public class ejercicioFunciones {

	public static void main(String[] args) {
		//Primera parte
		suma(40, 30,  20);
		//Segunda parte
		Coche miCoche = new Coche();
		miCoche.incrementarPuertas();
		System.out.println("Puertas del objeto Coche: " + miCoche.numPuertas);
	}
	//Primera parte
	public static void suma (int u, int s, int b) {
		int resultado;
		resultado = u + s + b;
		System.out.println(resultado);
	}
}
//Segunda parte
	class Coche {
	int numPuertas;
	public void incrementarPuertas() {
		this.numPuertas++;
}
}

