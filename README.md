# Aula03_03

Escreva um algoritmo que mostre todos os números pares entre 13 e 23 usando do..while.


~~~
import javax.swing.JOptionPane;

public class Aula03_03 
{
    public static void main(String[] args)
    {
        int i = 13;
        do
        {
            if((i%2) == 0)
            {
                JOptionPane.showMessageDialog(null, "os valores sao: " + i);
            }
            i++;
        }while(i<23);
    }
}
~~~
