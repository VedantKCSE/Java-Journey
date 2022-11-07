# Java-Journey
- Cmd usage is compulsary to learn to get any language.
```bash
  DIR - Directory
```
- Protected: No one can read the content of the class
- Method = Functions
```java
public class OddEven{
  boolean checkEven(int x){
    if(x%2 == 0){
      return true;
    }
    else return false;
}
public static void main(String[] args){
  OddEven o = new OddEven();
  // invoking the method
  boolean result = o.checkEven(10);
  System.out.println(result);
}
```
