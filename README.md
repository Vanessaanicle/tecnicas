# tecnicas
tr
package tecnicas;

public class FundoDeInvestimento {
	 public void notificar(Feedback ref) {
		 ref.avisar();
	 }


}

//

public abstract class Feedback{
public void avisar() {
}
}

//

public class grafico extends Feedback {

	@Override
	public void avisar() {
		System.out.println("Grafico");
	}

	

}

//

public class mensagem extends Feedback {

public void  avisar() {
	System.out.println("Mensagem");
}

}

//

import java.util.ArrayList;
import java.util.LinkedList;
import java.util.List;
public class n {

	public static void main(String[] args) {
		public static void main(String[] args) {
		 FundoDeInvestimento fi = new FundoDeInvestimento;
		     fi.notificar(new grafico());
		      fi.notificar(new mensagem());
		
	        }
	    }
	        


