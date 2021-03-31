1: polymorphism is something that can take many shapes

2: A method with the same name can do two different things:

public int add(int num1, int num2){
    return num1 + num2;
}

public int add(int num1, int num2, num3){
    return num1 + num2+ num3;
}

3: interfaces

4: possibly near-infinite?

5: see number 2

6: an object is a part of another object

7: 
public class Tyre{}

public class Bike{
    private Tyre tyre;

    public Bike(){
        this.roof = new Roof();
    }
}

8: aggregation: an object has another object, composition: an object is part of another object. Aggregation passes in class objects into the (super class?) constructor, composition just instantiates them

9: Aggregation: objects can still exist if the parent class is destroyed
Composition: objects are destroyed if the parent class is destroyed

10: they are destroyed

11: they are not destroyed