public class Carro {
    // Atributos
        String marca;
        String modelo;
        int ano;
        
         public Carro(){
             
         }
           public Carro(String marca,String modelo, int ano){
               this.marca = marca;
               this.modelo = modelo;
               this.ano = ano;
           }
        // Métodos
        public void Ligar (){
            System.out.println("O carro esta ligando");
        }
        public void acelerar (){
            System.out.println("O carro esta acelerando");
        }
        public void frear (){
            System.out.println("O carro esta freando");
        }
      
    }


    public class TestarCarro {
    public static void main(String[] args) {
       Carro c1 = new Carro();
       c1.marca = "Jeep";
       c1.modelo = "compass";
       c1.ano = 2017;
       
       System.out.println ("marca:" + c1.marca);
       System.out.println ("modelo:" + c1.modelo);
       System.out.println ("ano:" + c1.ano);
       
       c1.Ligar();
       c1.acelerar();
       c1.frear();
        }
        
    }
