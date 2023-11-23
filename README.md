System.out.println("OBESITAS/BERAT BADAN BERLEBIHAN");
                      
                      }public class BmiJava {
      public static void main (String args[]){
          int beratbadan = 50;
          float tinggibadan =150;
          float bmi =(beratbadan/(tinggibadan*tinggibadan));
          
          System.out.println("BMI SAYA ADALAH\t:"+bmi);
          
          if (bmi<18.5){
              System.out.println("BERAT BADAN SAYA KURANG");
          if(bmi<24.9){
              System.out.println("BERAT BADAN SAYA NORMAL/IDEAL");
          if (bmi<29.9){
              System.out.println("BERAT BADAN SAYA LEBIH/GEMUK");
          }
          else{
          }
          }
          }
    }
    
}
