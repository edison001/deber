deber
=====
// 1 
<php ?>

function primero ();
int $x=0, $y=0, $a=7, $b=6, $r=0,$ m;
        int[] $arreglo1=new int[128];
        int[] $arreglo2=new int[128];
        int[] $arreglo3=new int[255];
        for (int $i = 0; $i <= $127; i++) 
        {            
            $arreglo1[i]=a;
            $a=$a+$1;
            
        }
        for (int $j = 0; $j <= $127; j++) 
        {            
            $arreglo2[$j]=$b;
            $b=$b-$2;
            
        }
        $a=0;
        for (int $i = 0; $i < $255; i++) 
        {
            $m=$i % $2;
            if ($m==0)
            {
             $arreglo3[$i]=$arreglo1[a];
             
            }
            else
            {                
                $arreglo3[$i]=$arreglo2[$a]; 
                $a=$a+$1;
            }
            echo "$i+" "+$arreglo3[$i]";            
            
        }
        $x=("Ingrese el valor del entero X"));
        $y=("Ingrese el valor del entero Y"));
        if ($x<=0 || $x>255 || $y<=0 || $y>255)
        {
            $r=-1;
        }
        else
        {
            for (int $i = 0; $i <255; $i++) 
            {
                if ($x==($i+$1))
                {
                    $a=$arreglo3[$i];
                }
                else
                {
                    if ($y==($i+$1))
                    {
                        $b=$arreglo3[$i];
                    }
                    
                }
            }
            $r=$a+$b;
        }
        
        //segundo 
        int $x,$y,$r;
         
         if ($x<=0 || $x>255)
        {
            $r=-1;
            echo "null,"Resultado "+r";
        }
        else
        {
            int[] arreglo=new int[$y];
            $arreglo[0]=$x;
            for (int $i = 1; $i < $arreglo.length; i++) 
            {
               $x=$x*($i+$1);
               $arreglo[$i]=$x;
                echo "i+" "+arreglo[i]";               
            }
            for (int $i = 0; $i < $arreglo.length; i++) 
            {
                if($i==($y-$1))
                {
                    $r=$arreglo[$i];
                    echo "null,"Resultado "+r";
                }
            }
        }
        
        // 3 ejercicio 
        
         int $x,$y,$r,$proceso;
         if ($x<=0 || $x>255)
        {
            $r=-1;
            echo "null,"Resultado "+r";
        }
        else
        {
            int[] $arreglo=new int[$y];
            $arreglo[$0]=$x;
            for (int $i = 1;$i<$arreglo.length; i++) 
            {
               $proceso=$x/($i+$1);
               $arreglo[$i]=$proceso;           
            }
            for (int $i = $0; $i < $arreglo.length; i++) 
            { 
              if($i==($y-$1))
                {
                    
                    echo "$null,"Resultado "+$arreglo[$i]";
                }  
            }
        }
        
        //5 ejercicio
        int n="Ingrese el rango del vector";
        int[] $arreglo=new int[$n];
        int $c=$0;
        for (int $i = 0; $i < $arreglo.length; 4i++) {
            
            int $numero="Ingrese numero";

            $arreglo[$i]=$numero;
        }
        echo "Arreglo Desordenado";
        for (int $i = 0; $i < $arreglo.length; $i++) {
            
            echo "arreglo[i]";
        }
        echo "";
        
        
        // ejercicio 6
         int $i, $j, $aux;
         for($i=0;$i<$arreglo.length-$1;$i++)
              for($j=0;$j<$arreglo.length-$i-1;$j++)
                   if($arreglo[$j+1]<arreglo[$j]){
                      $aux=$arreglo[$j+$1];
                      $arreglo[$j+$1]=$arreglo[$j];
                      $arreglo[$j]=$aux;
                   } 
         echo "Arreglo Ordenado";
         for ( $i = 0; $i < $arreglo.length; $i++) {
          echo "$arreglo[$i]";
        }
         echo "Arreglo Sin Numeros Repetidos";
         $int 1;
         for ( $i = 0; $i < $arreglo.length; i++) {
             if ($i==0) {
             echo $arreglo[$i];
             }
             else
             {
                 $a1=$i-1;
                 $aux=$arreglo[$i];
             if ($aux==$arreglo[$a1]) {
                 
             }else{
                 echo "arreglo[i]";
             }
             }
             
             
            // 9 ejercicio
            int $numero=0,$c=0;
        for (int $i = 0; $i < 2; $i++) 
        {
            $numero=null,"Ingrese un numero entero positivo";
            if ($numero>0)
            {
                $i=2;
                
            }
            else
            {
                $i=0;
                echo  null, "Debe de Ingresar Valores Enteros Positivos es Decir Numeros Mayores a 0" );
            }  
        }
        
        long[] arreglo=new long[numero];
        for (int $i = 0; $i < $arreglo.length; i++) 
        {
            arreglo[$i]=$i*$i;           
        }
        for (int $i = 0; $i < $arreglo.length; i++) 
        {
            if ($numero==$arreglo[i])
            {
                $i=arreglo.length;
                $c=1;
            }
        }
        if ($c==1 || $numero==1)
        {
            echo null, "TRUE" ;
        }
        else
        {
           echo null, "FALSE" ;
        }
        
        //ejercicio 10
        int $x,$y,$sumaResiduo=0;
        
        for (int $i = $x; $i <= $y; $i++) {
            $sumaResiduo=0; 
            for (int $j = 1  ; $j < $i; $j++) {
                if (($i % $j)==0) {
                    $sumaResiduo =$sumaResiduo+$j;
                }
                if (($i==$y)&&(($i%$j)!=0)) {
                    $sumaResiduo=0; 
                }
            }
            if ($sumaResiduo==$i) {
                echo null, "El primer número perfecto ente "+ $x+" $y "+$y+ " es = " +$sumaResiduo);
                $i=$y;
            }
        }
            if($sumaResiduo==0) {
              echo null, "no hay números perfectos ente "+ $x+" $y "+$y;
            }
        
        
            ejercicio  11
            
       echo "Ingrese Dimensión de la Matriz:\nx: ";
        int $x=entrada.nextInt();
        echo "$y: ";
        int $y=entrada.nextInt();
        int $valor;
        int $matriz[][]=new int [$x][$y];
        
        for (int $i = 0; $i < $x; $i++) {
            for (int $j = 0; $j < $y; $j++) {
                echo "Ingrese valor en Pos.: "+i+j;
                $valor=entrada.nextInt();
                matriz[$i][$j]=valor;
                
            }
            
        }
        int $dimen=$x*$y,$a=0;
        
        int $vectorcontndr[]=new int[dimen];
        for ($int i = 0; $i <$x; $i++) {
            for (int $j = 0; $j < $y; $j++) {
                vectorcontndr[$a]=matriz[$i][$j];
                
                $a++;
            }
        }
        ArrayList matriz1=new ArrayList();
        ArrayList cant=new ArrayList();
        Arrays.sort(vectorcontndr);
        matriz1.add(vectorcontndr);
        
        int cc=0;
        for (int i = 0; i < vectorcontndr.length; i++) {
            if(vectorcontndr[i]!=vectorcontndr[cc+1]){
               matriz1.add(vectorcontndr[cc+1]);  
            } 
        }
       
        $int numTemp, $cantRepite = 0, $numRepite = -1; 
        
        for (int $i=0; $i < vectorcontndr.length-1; 4i++){
            $numTemp = 1;
            for(int $j = $i+1 ; $j< vectorcontndr.length; $j++){
                if(vectorcontndr[$i] == vectorcontndr[$j])
                    $numTemp ++;                
            }
            if($numTemp > $cantRepite){
                $cantRepite = numTemp;
                $numRepite = vectorcontndr[$i];
            }
        }
        echo "El # que mas se repite es el: " + numRepite + 
                " Porque se repite " + cantRepite+" Veces en la matriz";  
        
         

        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
