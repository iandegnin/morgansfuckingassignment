# morgansfuckingassignment
my ass

class Main {
  public static int SIZE = 8;

  public static void main(String[] args) {
  }

  public static void drawMonth() {
    for(int week = 0; week < 5; week++){
      drawRow();
    }
    drawDashes();
  }

  public static void drawRow() {
    drawDashes();   
    for(int j = 0; j < SIZE / 2; j++) {
      drawSpaces();
    }
  }

  public static void drawDashes() {
    for(int i = 0; i < SIZE * 7; i++) {
      System.out.print("=");
    }
    System.out.println("=");
  }

  public static void drawSpaces() {
    for(int i = 0; i < 7; i++) {
      System.out.print("|");
      for(int j = 0; j < SIZE - 1; j++){
        System.out.print(" ");
      }
    }
  System.out.print("|");
  System.out.println();
  }
}
