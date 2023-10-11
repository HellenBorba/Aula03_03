# Aula03_03

Faça um programa em JAVA que verifique quais são os números múltiplos de 2. 


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
