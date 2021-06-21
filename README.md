public class Program
{
    public static void main(String[] args) {
        System.out.println(SENA);
	}
}

// para los comentarios de solo una linea //

/* para los comentarios
   de varias lineas */

/ ** para los comentarios estilo javadoc, encierra en cuadro */

class Ejem1
{
    public static void main(String[] args) {
        String name="Esteban Aguilar";
        int age = 18;
	}
}

int suma1 = 170 + 100;
int suma2 = suma1 + 400;
int suma3 = suma1 - suma2;
int a = 31;
++a;
System.out.println(a);


int day = 3;
switch(meses) {
 case 3:
   System.out.println("Enero"); 
   break;
 case 4:
   System.out.println("Febrero");
   break:
   case 5:
   System.out.println("Marzo");
}


int[ ] arrays = new int[3];

arr[4] = 22;

String [ ] Ejeminta = {"L", "A", "U"};
System.out.println(Ejeminta [4]);

int[ ] intArr = new int[5];
System.out.println(intArr.length);

// multidimencional

int[ ][ ] sample = { {1, 2, 3}, {4, 5, 6} };
int x = sample[1][0];
System.out.println(x);

public class Methods {
   static void Laura() {
     System.out.println("Esteban");
   }
  public static void main(String[ ] args) {
  Esteban();
  }
}

public class Calling {
   static void Tapiero() {
     System.out.println("Tapiero");
   }
  public static void main(String[ ] args) {
  Tapiero();
  Tapiero();
  }
}

public class Parameters {
   static void sayHello(String name) {
     System.out.println("Hello" + name);
   }
  public static void main(String[ ] args) {
  sayHello("Esteban");
  sayHello("Tapiero");
  }
}
