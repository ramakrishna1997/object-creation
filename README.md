# object-creation

public class objectcreation2 {

	public static void main(String[] args) {
		int Emp_id;
		String Emp_name;
		String Emp_Department;
		int Emp_salary;
		Employee Emp = new Employee();
		System.out.println(Emp.Emp_id);
		System.out.println(Emp.Emp_name);
		System.out.println(Emp.Emp_Department);
		System.out.println(Emp.Emp_salary);

	}
}
class Employee{
	int Emp_id=1;
	String Emp_name="Jai Ram";
	String Emp_Department="IT Desk";
	int Emp_salary=50000;
}
