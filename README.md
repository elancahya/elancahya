package pbotugas1;

import java.util.Scanner;

public class PBOTUGAS1 {

  public static void main(String[] args) {

  Scanner Elan = new Scanner(System.in);

  double galon,liter;

  System.out.print("masukan jumlah galon:");

  galon = Elan.nextDouble();

  

  liter = galon * 3.785;

  

  System.out.print("jumlah liter = "+liter);

  

  }

}
