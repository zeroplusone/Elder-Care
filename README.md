# Elder-Care
An IOT project which helps elder to alert emergency events by using Linkit ONE, Android app and Mediatek Cloud Service.

# File Structure
 - **communication/**
   - Linkit ONE code (.ino)
 - **Doc/**
   - Proposal document
   - Oral proposal slide
   - Report
 - **ElderCare/**
   - Android app code
 - **Library/**
   - Libraries used in Linkit ONE.(described in the following section)

# Libraries used in this project

 -  [HttpClient](https://github.com/amcewen/HttpClient)
 -  [mThread](https://github.com/jlamothe/mthread)
 -  [Accelerometer_MMA7660](https://github.com/Seeed-Studio/Accelerometer_MMA7660) 
  -  Although we used the Accelerometer MMA7660 library, but we found that the data from getAcceleration() wasn't correct. So we change a little bit in the MMA7660.cpp based on this [solution](http://forum.arduino.cc/index.php?topic=265706.0).
  -  Append the [MMA7660 datasheet](http://garden.seeedstudio.com/images/e/ee/MMA7660FC.pdf). The table on page 28 helps us understand the changing from the solution above.
 
 -  [Grove_LED_Bar](https://github.com/Seeed-Studio/Grove_LED_Bar)
 
