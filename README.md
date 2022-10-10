# gitskills
public class D{
  public void static main(String[] args){
      Random r = new Random();
      int q = r.nextInt(10)+1;
      while(true){
      System.out.print("请输入：");
      Scanner sc = new Scanner(System.in);
      int s = sc.nextInt();
      if(s<q){
      System.out.println("小了")；
      
      }else if(s>q){
      System.out.println("大了");
      }
      else{
      System.out.println("恭喜获胜！！！");
      break;
          }
      
       }
     }
   }
