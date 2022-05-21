package practice.problems.java;

import java.util.Objects;

public class uc1 {
    String employee;

    public uc1() {

    }

    void attendence(){
        String employee = "yes";

        if (Objects.equals(employee, "yes")) {
            System.out.println("present");
        }else{
            System.out.println("absent");
        }
    }

      public static void main(String[] args) {
          uc1 employee =new uc1();
          employee.attendence();
        }
}