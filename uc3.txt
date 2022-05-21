package practice.problems.java;

public class PartTimeEmployee {

    public void employeeWage1() {
        int hour = 8;
        int wage = 20;
        System.out.println(" Part time  Wage of  an Employee: "+(hour*wage));
    }

    public static void main(String[] args) {

        PartTimeEmployee employee = new PartTimeEmployee();
        employee.employeeWage1();
    }
}
