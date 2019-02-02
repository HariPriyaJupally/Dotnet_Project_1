# Dotnet_Project_1

1. Which algorithm is faster?
   Bucket sort is faster than Quick sort.

2. Where is the entry point of the application? (The place execution begins - provide the fully qualified class name and method name)
   The entry point of the application is in Program.cs, The fully qualified class name is SortComparision.Program.Main and the place where the execution begins is static void Main()

3. What is the name of the code file that displays the main form?
   frmMain.cs is the name of the code file that displays the main form.

4. What method does the main form constructor call?  Hint: look at frmMain.cs, right-click if necessary to "View Code", and then find the constructor (the constructor method name is the same as the class name.)
   InitializeComponent() is the method the main form constructor calls.

5. What is the fully qualified name of the class from which the main form is derived? 
   SortComparision.frmMain is the fully qualified name of the class.
 
6. Add code to the Form1_Load method - use intellisense and your IDE to determine: 
   What is this.tbSamples.Value? Set the default value to 10x your team number (if team 1, use 100). If this causes an error, read the error message carefully and make changes as needed.
   tbSamples.Value represents the number of samples on the scroll bar.

7. What is this.cboAlg1?  Set its SelectedIndex to an integer so that the default is Bucket Sort.
   this.cboAlg1 is used on SelectedIndex to set the default first sorting index value to Bucket Sort.

8. What is this.cboAlg2? Set its SelectedIndex to an integer so that the default is Quick Sort.
   this.cboAlg2 is used on SelectedIndex to set the default first sorting index value to Quick Sort.

9. Use AppDomain.CurrentDomain.BaseDirectory.ToString() to get the base directory. 
   I have used it.

10. Create a new method called InitializeOutputFolder() and call it - see the suggested content below. What does this method do? 
    InitializeOutputFolder() method is used to return the path of the output folder.

11. What is this.cmdShuffle?  Call its PerformClick() method before exiting Form1_Load.
    this.cmdShuffle is used to shuffle the number of samples that are to be sorted. When we call PerformClick() method on it, whenever we run the program it automatically shuffles the samples.

12. What is this.cmdSort?  Change its appearance (e.g. ForeColor or BackColor) to highlight it so users will click it. 
    this.cmdSort is the button, when clicked the sorting process starts. We have changed the appearance by using both BackColor and ForeColor to highlight it so users will click it.
    (for BackColor we used this.cmdSort.BackColor = System.Drawing.Color.Aquamarine;
     for ForeColor we used this.cmdSort.ForeColor = System.Drawing.Color.Red;)

13. Make at least one other obvious improvement or customization as desired.
    We have changed the algorithm name font color and also changed the background color of shuffle button.