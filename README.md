# prueba
hola mundo

public class operacionescalcul {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		  int operaciones = 1;   //1 = suma, 2 = resta, 3 = multiplicacion
		                   // para cada operacion se elige el numero que corresponde
		   int a=10;
		   int b=2;

		   switch(operaciones){
		          case 1:
		        	  System.out.println("resultado suma:  "+(a+b));
		        	  break;
		          case 2:
		              System.out.println("resultado resta:  "+(a-b));
		              break;
		          case 3:
		        	  System.out.println("resultado multiplicacion:  "+(a*b));
		        	  break;
		   }
	}

}
