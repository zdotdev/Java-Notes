Generics make the class ability in terms of Data types. You don't have to declare multiple class to do specific task for each data types. All you need is to create a generic class `<>`. You have declare the type parameter after the class name. It doesn't matter what the name is.

**Example**

Integer printer:
```java
class printer <T>{
	T number;
	
	public printer(T newNum){ // Constructor
		this.number = newNum;
	} 
	
	public void print(){
		System.out.println(number);
	}
}
```

```java
public class Main{
	public static void main(String[] args){
		printer<Integer> pInt = new Printer<>(23); // Add value to Constructor
		p.print();
		
		printer<String> pInt = new Printer<>("Anja"); // Add value to Constructor
		p.print();
		
		printer<Double> pInt = new Printer<>(23.00); // Add value to Constructor
		p.print();
	}
}
```
You can create different instantiation for different data types.

# Bounded Generic

# ArrayList Generic