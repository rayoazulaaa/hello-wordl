# hello-wordl
my firts program with Java.
package classone;
public class ClassOne {
    	private String simbolos = "+,?,=";
	private String numeros = "0,1,3,5,9";
        public String getNumeros() {
            return numeros;
        }
	private char sim_1 = '+';
	private char sim_2 = '?';
	private char sim_3 = '=';
	private int num_1 = 0;
	private int num_2 = 1;
	private int num_3 = 3;
	private int num_4 = 5;
	private int num_5 = 9;
	private int result_1 = 3+1;
	private int result_2 = 5+result_1;
	private String queNumerosConsecutivosFaltanParaLLegarAl9ConsecutivamentePartiendoDeCeroDeLaSiguienteSerieNumerica;
	private String serieNumericaIncompleta = "0,1,?,3,?,5,?,?,?,9";
        public String getSerieNumericaIncompleta() {
            return serieNumericaIncompleta;
        }
    public static void main(String[] args) {
        ClassOne co = new ClassOne();
        co.queNumerosConsecutivosFaltanParaLLegarAl9ConsecutivamentePartiendoDeCeroDeLaSiguienteSerieNumerica = co.getNumeros();
        System.out.println("que\nNumeros\nConsecutivos\nFaltan\nPara\nLLegar\nAl\n9\nConsecutivamente\nPartiendo\nDe\nCero\nDe\nLa\nSiguiente\nSerie Numerica\n" + co.queNumerosConsecutivosFaltanParaLLegarAl9ConsecutivamentePartiendoDeCeroDeLaSiguienteSerieNumerica);
        System.out.println("La logica fue la siguiente: \nque numero sumado con cual\nes el resultado para encontrar\nel numero que se encuentra entre el 3 y el 5");
        System.out.println("utilizando los digitos de la serie numerica\nde cuantas formas es posible sumar dos digitos y que el resultado sea 9");
        System.out.println("Todas las Respuestas : \n //2,4,6,7,8, 3+1, 2 (5+4 y 5+3+1)");
        System.out.println("Otras respuestas correctas podrian ser : \n 1+3 , 2 (4+5 y 1+3+5 o 3+1+5 o 5+1+3 o 1+5+3 o 3+5+1");
    }
}
