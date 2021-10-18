# empswitch.java
public class empswitch {

	public static final int part_time = 1;
        public static final int full_time = 2;
	public static final int wage_per_hour = 20;


	public static void main(String[] args) {
		int empcheck = (int) Math.floor(Math.random() * 10) % 3;
		int working_hours = 0;
		int  salary = 0;
		switch (empcheck) {
		case part_time:
			working_hours=4;
		break;
		case full_time:
			working_hours=8;
		break;
		default:
			System.out.println(" Employee wage is 0 and Employee  is absent");
		}		
			salary = working_hours * wage_per_hour;
			System.out.println(" Employee wage is: " +salary);
	}

}
