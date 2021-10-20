# 2D-ArrayList
import java.util.ArrayList;

public class Stringtool {

	public static void main(String[] args) {
		
		ArrayList<ArrayList<String>> groceryList = new ArrayList();
		
		
		ArrayList<String> bakerayList = new ArrayList();
		bakerayList.add("pasta");
		bakerayList.add("garlic bread");
		bakerayList.add("donut");
		
		ArrayList<String> produceList = new ArrayList();
		produceList.add("Tomato");
		produceList.add("garlic");
		produceList.add("suger");
		
		ArrayList<String> drikList = new ArrayList();
		drikList.add("soda");
		drikList.add("water");
		
		groceryList.add(bakerayList);
		groceryList.add(produceList);
		groceryList.add(drikList);
		
		
		System.out.println(groceryList.get(0).get(0));
	}

}
