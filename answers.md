1: omething that can take many forms

2: public class addNewCar(Car car){}
public class addNewBike(Bike bike){}

replace it with:
public class addNewVehicle(IVehicle vehicle){}

6: an object is a part of another object

3: interfaces or abstract classes

4: 1

5: public class addNewCar(Car car){}
public class addNewBike(Bike bike){}

replace it with:
public class addNewVehicle(IVehicle vehicle){}

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