import java.util.Scanner;

class Actividad_Programacion{
    public static void main(String args[]){
Scanner lectoor=new Scanner (System. in) ;
       String cadena = "";
       char [] Arraycadena;
       char caracter;
       int contador = 0;
       System.out.println("Escriba una palabra");
       cadena = lectoor.nextLine();
       Arraycadena = cadena.toCharArray();
       for (int i = 0; i < Arraycadena.length; i++){
           caracter = Arraycadena[i];
           for (int k = 0; k < Arraycadena.length; k++){
               if (Arraycadena[k] == caracter) {
                   contador++;
               }
               
           }
           System.out.println("La "+Arraycadena[i] +" sale "+ contador+" vez");
           contador = 0;
       }
       
    }
}
