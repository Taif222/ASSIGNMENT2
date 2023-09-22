# ASSIGNMENT2
CCSW 325 Software Construction Assignment

Taif Alharbi 2110198 / The constructor was declared as DataProcessor instead of SensorDataProcessor , the constructor should match the class name, It's a rule in Java to helps identify and differentiate constructors from other methods in the class.

Nihal kutbi - 2115006 / Variable Declarations: In the current code, the variables i, j, and k are declared outside the loop and then assigned values inside the loop. It's better to declare and initialize loop variables within the loop itself to limit their scope. For example, instead of int i = 0; before the loop, you can declare int i; inside the for loop, like for (int i = 0; i < data.length; i++).

Layan alnoumani 2110350 / The method calculates data given by the user  and it's written here down void and it must return a double type
A calculation method can't return void except if it was a printing  statement method
// calculate data
public double calculate(double d) {
int i, j, k = 0;
double[][][] data2 = new double[data.length][data[0].length][data[0][0].length];

Rogayah Garout 2112035/ The code is lacking three import statements for the following classes: BufferedWriter, IOException, and
FileWriter. In addition, it is better to specify the exception catch block by modifying it to IOException. 
