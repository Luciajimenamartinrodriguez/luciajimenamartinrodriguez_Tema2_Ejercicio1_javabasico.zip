package PROJECTS;

public class PROJECT2PRECIO {

    //Para este ejercicio tendréis que crear una función que reciba un precio y devuelva el precio con el IVA incluido

    public static void main(String[] args) {
        int preciosilla = 20;
        double iva = 0.2;
        int resultado = (int) (preciosilla * iva);



        System.out.println(resultado + preciosilla);
    }
}
