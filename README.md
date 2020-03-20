
     Scanner input = new Scanner (System.in);
     int n1,n2,n3,total;
     double avg;
     System.out.println("Enter three numbers");
     int num1 = input.nextInt();
     int num2 = input.nextInt();
     int num3 = input.nextInt();
     total = sum(n1,n2,n3);
     avg = average(n1,n2,n3);
     display (total,avg);
    public static int sum (int n1, int n2,int n3){ 
             return n1 + n2 + n3;}
     public static double average (int n1, int n2,int n3){
             return sum (n1,n2,n3)/3;}
     public static void display (int s, double a){
         System.out.println("the sum of the 3  numbers"+ s);
         System.out.println("the sum of the 3  numbers"+ a); }
    
