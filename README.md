# sortedorder
import java.util.*;  
public class Merge
{  
public static void main(String[] args)   
{  
int[] firstArray = {69,36,43,55,95,73};        
int[] secondArray = {58,69,42,2,78,11};   
int fir = firstArray.length;          
int sec = secondArray.length;  
int[] result = new int[fir + sec];  
System.arraycopy(firstArray, 0, result, 0, fir);  
System.arraycopy(secondArray, 0, result, fir, sec);  
System.out.println(Arrays.toString(result));     
}  
}
