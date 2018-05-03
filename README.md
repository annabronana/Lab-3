# Lab-3
Circle and CircleTester Lab



public class CircleTester {

	public static void main(String[] args) {
		//*******************************************************
		// CircleTester.java
		//
		//
		//  A client to test the functionality of objects
		//  of the class Circle
		//
		//*******************************************************
		Circle circle1 = new Circle();
		Circle circle2 = new Circle();
		circle1.setX(-3.0);
		circle1.setY(4.0);
		circle1.setRadius(2);
		circle2.setX(2.0);
		circle2.setY(1.0);
		circle2.setRadius(5.3);
		System.out.println("circle1="+circle1);
		System.out.println("circle2="+circle2);
		// If the method setRadius is implemented correctly,
		// a call to setRadius with a negative number
		// will not change the value of the circle's radius.
		//
		circle1.setRadius(-2.0);
		//
		// Reset the center of circle1 (-3.0,4.0) ^^
		//
		circle1.setX(-3.0);
		circle1.setY(4.0);
		// print circle1 characteristics (center and radius), use ^^
		//a statement similar
		// to the previous println statements. Note that is not 
		//necessary to call
		//the method toString, why?
		System.out.println("Circle 1 Center:"+ circle1.getX() +','+ circle1.getY());
		System.out.println("Circle 1 Radius:" + circle1.getRadius());
		// set the circle2 radius to 5.3 ^^
		// print circle2 characteristics (center and radius), use 
		//a statement similar to the first and
		// second println statements
		System.out.println("Circle 2 Center:" + circle2.getX() + ',' + circle2.getY());
		System.out.println("Circle 2 Radius:" + circle2.getRadius());
		// print circle1 diameter, area and perimeter ^^
		System.out.println(circle1.diameter());
		System.out.println(circle1.area());
		System.out.println(circle1.perimeter());
		// print circle2 diameter, area and perimeter ^^
		System.out.println(circle2.diameter());
		System.out.println(circle2.area());
		System.out.println(circle2.diameter());
		// display whether circle1 is a unit circle ^^
		System.out.println(circle1.isUnitCircle());
		// display whether circle2 is a unit circle
		System.out.println(circle2.isUnitCircle());
		// your additional tests should be placed below here
		}

}
