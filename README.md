# Multi-level-Inheritance
class College{
	void Engineering() {
		System.out.println("The college name is:K.S.R College of Engineering");
	}
}
class Cse extends College {
	void computer() {
		System.out.println("Department of computer science engineering");
	}
}
class CseA extends College{
	void strength() {
		System.out.println("The total strength is:56");

	}
}
public class Multilevelnheritance {

	public static void main(String[] args) {
		CseA  a=new CseA();
		Cse a1=new Cse();
		College a2=new College();
		a2.Engineering();
		a1.computer();
		a.strength();
	}
  }
