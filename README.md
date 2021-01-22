# lab-1

public class Arrayoutput {

	public static void main(String[] args) {
		int array_variable[] = new int[10];
			for (int i=0;i<10;++i)
				
			{
				array_variable[i]=i;
				System.out.println(array_variable[i]+ "");
				i++;
				try {
		            array_variable[i] = 10;
		        } catch (Exception e) {
		            System.out.println("out of bounds");;
		        }		
			}

	}

}
