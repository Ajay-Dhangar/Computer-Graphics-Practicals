# Computer Graphics

<h2> ✍️ List of Practicals</h2>

<details id=1 open>
<summary><h5>1. Write a program to draw a rectangle using line function</h5></summary>
 
  - In ` C ` language
    
    ```
    / C program to draw a rectangle
    #include <graphics.h>
  
    // Driver code
    int main()
    {
        // gm is Graphics mode which is a computer display
        // mode that generates image using pixels.
        // DETECT is a macro defined in "graphics.h" header file
        int gd = DETECT, gm;
  
        // location of left, top, right, bottom
        int left = 150, top = 150;
        int right = 450, bottom = 450;
  
        // initgraph initializes the graphics system
        // by loading a graphics driver from disk
        initgraph(&gd, &gm, "");
  
        // rectangle function
        rectangle(left, top, right, bottom);
  
        getch();
  
        // closegraph function closes the graphics
        // mode and deallocates all memory allocated
        // by graphics system .
        closegraph();
  
       return 0;
    }
    ```
  - In ` C++ ` language 
  
    ```
    // C++ program to demonstrate rectangle
    // over a self-formed background image

    #include <iostream>
    #include <opencv2/core/core.hpp>
    
    // Drawing shapes
    #include <opencv2/imgproc.hpp>
    
    #include <opencv2/highgui/highgui.hpp>
    using namespace cv;
    using namespace std;
    
    // Driver Code
    int main(int argc, char** argv)
    {
    	// Creating a blank image with
    	// white background
    	Mat image(500, 500, CV_8UC3,
    			Scalar(255, 255, 255));
    
    	// Check if the image is created
    	// successfully or not
    	if (!image.data) {
    		std::cout << "Could not open or "
    				<< "find the image\n";
    
    		return 0;
    	}
    
    	// Top Left Corner
    	Point p1(30, 30);
    
    	// Bottom Right Corner
    	Point p2(255, 255);
    
    	int thickness = 2;
    
    	// Drawing the Rectangle
    	rectangle(image, p1, p2,
    			Scalar(255, 0, 0),
    			thickness, LINE_8);
    
    	// Show our image inside a window
    	imshow("Output", image);
    	waitKey(0);
    
    	return 0;
    }

    ```
  - In ` JAVA ` language 
  
    ```
    // java program to draw a ellipse
    // using drawOval function.
    import java.awt.*;
    import javax.swing.*;
     
    public class ellipse extends JApplet {
     
        public void init()
        {
            // set size
            setSize(400, 400);
     
            repaint();
        }
     
        // paint the applet
        public void paint(Graphics g)
        {
            // set Color for rectangle
            g.setColor(Color.red);
     
            // draw a ellipse
            g.drawOval(100, 100, 150, 100);
        }
    }
    ```
  - In ` Python ` language 
    
    ```
    # draw Rectangle in Python Turtle
    import turtle

    t = turtle.Turtle()

    l = int(input("Enter the length of the Rectangle: "))
    w = int(input("Enter the width of the Rectangle: "))

    # drawing first side
    t.forward(l) # Forward turtle by l units
    t.left(90) # Turn turtle by 90 degree
    
    # drawing second side
    t.forward(w) # Forward turtle by w units
    t.left(90) # Turn turtle by 90 degree

    # drawing third side
    t.forward(l) # Forward turtle by l units
    t.left(90) # Turn turtle by 90 degree
    
    # drawing fourth side
    t.forward(w) # Forward turtle by w units
    t.left(90) # Turn turtle by 90 degree

    ```
   <br />
 
 **Output:**
 
 ![image](https://user-images.githubusercontent.com/99037494/198338595-5422d2f9-cb8d-401f-91b9-ab593c67d492.png)

   
 </details>

<details id=2 open>
<summary><h5>2. Write a program to draw a line using DDA’s line drawing algorithm</h5></summary>

 - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>
 
<details id=3 open>
<summary><h5>3. Write a program to draw a line using Bresenham’s line drawing algorithm</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>
 
<details id=4 open>
<summary><h5>4. Write a program to draw a circle using equation of circle.</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>
 
<details id=5 open>
<summary><h5>5. Write a program to draw a circle using Bresenham’s circle drawing algorithm</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>
 
<details id=6 open>
<summary><h5>6. Write a program to draw a circle using mid point circle drawing algorithm</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>


<details id=7 open>
<summary><h5>7. Write a program to draw a circle using polar co-ordinates</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>


<details id=8 open>
<summary><h5>8. Write a program to fill a circle using Boundary Fill Algorithm</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>


<details id=9 open>
<summary><h5>9. Write a program to fill a circle using Flood Fill Algorithm</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>


<details id=10 open>
<summary><h5>10. Write a program for line clipping using cohen Sutherland algorithm</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>


<details id=11 open>
<summary><h5>11. Write a program to translate a triangle about the origin</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>


<details id=12 open>
<summary><h5>12. Write a program to scale a triangle about a fixed point taken as one of the vertex of the triangle</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>


<details id=13 open>
<summary><h5>13. Write a program to rotate a triangle about a fixed point taken as one of the vertex of the triangle</h5></summary>

  - In ` C ` language
    
    ```
    
    ```
  - In ` C++ ` language 
  
    ```
    
    ```
  - In ` JAVA ` language 
  
    ```
    
    ```
  - In ` Python ` language 
    
    ```
    
    ```
   <br />
   
 </details>

