# HVImageView

This library is useful to make round corner image view in android studio. You can make specific corner round of an image. By Default all the corners will affect.

It has following properties which is useful to make round corners. <br/>
Property named "cornerRadius" will accept inter value which Will indicate the radius of the round corner. <br/>
Property named "topLeftCorner" is a boolean value to set this corner will round or not. By default it is true. <br/>
Property named "topRightCorner" is a boolean value to set this corner will round or not. By default it is true. <br/>
Property named "bottomLeftCorner" is a boolean value to set this corner will round or not. By default it is true. <br/>
Property named "bottomRightCorner" is a boolean value to set this corner will round or not. By default it is true. <br/>

# Example:-

<unique.solution.hvimageview.RoundedCornerImageView <br/>
       &emsp;&emsp;android:id="@+id/roundimage1" <br/>
       &emsp;&emsp;android:layout_width="300dp" <br/>
       &emsp;&emsp;android:layout_height="300dp" <br/>
       &emsp;&emsp;android:src="@drawable/ic_launcher_background" <br/>
       &emsp;&emsp;android:layout_gravity="center" <br/>
       &emsp;&emsp;app:cornerRadius = "30" <br/>
       &emsp;&emsp;app:topLeftCorner="false" <br/>
       &emsp;&emsp;app:topRightCorner="true" <br/>
       &emsp;&emsp;app:bottomLeftCorner="true" <br/>
       &emsp;&emsp;app:bottomRightCorner="false" />
