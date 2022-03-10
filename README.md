# Nombre
<?php

class nombre{
    
    
    /*
     * Creo la funcion para crear atributos en los parametros
     * $n para el nombre
     * $a para el apellido
     */
    public function miNombre($n, $a){
        
        return ("El nombre es " + $n + "\nmi apellido es" + $a);
    }
    
    /*
     * muestro mi edad con el parametro $edad
     * imprimo directamente con return y entre parentesis y comillas "Edad: " 26
     */
    public function miEdad($edad){
        return ("Edad: " + $edad);
    }
    
    /*
     * Creo una funcion para saber si es mayor de edad
     * con la condicion if y else para verificar
     * llamo a la funcion miEdad y saber si esta numero es mayor que 17
     */
    public function mayorEdad($e){
        if(miEdad($e) > 17){
            return ("Mayor de edad");
        }
        else{
            return ("menor de edad");
        }
    }
}

