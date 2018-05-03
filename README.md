# Lab-3
Circle and CircleTester Lab


public class Circle {

	//public static void main(String[] args) {

//*******************************************************
// Circle.java
//
//
//*******************************************************
		private double radius;    // declare the private double 

		private double x;         // declare the private double 

		private double y;       // declare the private double 

		//----------------------------------------------
		// getX - returns the value of x
		//----------------------------------------------
		public double getX() {
			return this.x;
		}
		//----------------------------------------------
		// getY - returns the value of y
		//----------------------------------------------
		public double getY() {
			return this.y;
		}
		//----------------------------------------------
		// getRadius - returns the value of radius
		//----------------------------------------------
		public double getRadius() {
			return this.radius;
		}
		//----------------------------------------------
		// setX - assigns a new value to x
		//----------------------------------------------
		public void setX(double x) {
			this.x = x;
		}
		//----------------------------------------------
		// setY - assigns a new value to y
		//----------------------------------------------
		public void setY(double y) {
			this.y = y;
		}
		//----------------------------------------------
		// setRadius - assigns a new value to radius
		//----------------------------------------------
		public void setRadius(double radius) {
			if (radius <= 0) {
				this.radius = radius;
			}
		
		}
		//--------------------------------------------------------
		// diameter - calculates the diameter of the circle
		//--------------------------------------------------------
		public double diameter() {
			return 2*radius;
		}
		//--------------------------------------------------------
		// area - returns the area of the circle
		//--------------------------------------------------------
		public double area() {
			return Math.PI * Math.pow(radius, 2);
		}
		//--------------------------------------------------------
		// perimeter - returns the perimeter of the circle
		//--------------------------------------------------------
		public double perimeter() {
			return 2 * Math.PI * radius;
		}
		//--------------------------------------------------------
		// isUnitCircle - return true if the radius of this circle
		//                is 1 and its center is (0,0) and false
		//               otherwise.
		//--------------------------------------------------------
		public boolean isUnitCircle() {
			if (radius == 1 && x == 0 && y == 0) {
				return true;
			}	
			else {
				return false;
			}
		}
		//--------------------------------------------------------
		// toString - return a String representation of
		//            this circle in the following format:
		//            center:(x,y)
		//            radius: r
		//--------------------------------------------------------
		public String toString() {
		// Your code goes here
			return ("Center: (" + x + "," + y + ")" + '\n');
			//return ("Radius:" + radius);
		}
	//}

}
		

	
 




