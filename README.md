# Employee

public class employee {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		employee e1 = new employee();
		employee e2 = new employee();
		employee e3 = new employee();
		System.out.println("NAME"+" "+"YEAR OF JOINING"+" "+"ADDRESS");
        e1.insert(1994, "Robert","64C-wallsStreet");
        e2.insert(2000, "Sam", "68D-WallsStreet");
        e3.insert(1999, "John", "26B-WallsStreet");
	}
}
class employee1 {
	String name ;
	int yearofjoining;
	String address;
	void insert (int yearofjoining1,String name1,String address1) {
		name=name1;
		yearofjoining = yearofjoining1;
		address=address1;
		display();
		System.out.println("NAME" + "YEAROFJOINING"+"ADDRESS");
	}
	void display()
	{
		System.out.println(name +""+ yearofjoining+" "+ address);
	}
}

		

	
