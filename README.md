# HVImageView

This library is useful to make round corner image view in android studio. You can make specific corner round of an image. By Default all the corners will affect.

It has following properties which is useful to make round corners.
Property named "cornerRadius" will accept inter value which Will indicate the radius of the round corner.
Property named "topLeftCorner" is a boolean value to set this corner will round or not. By default it is true.
Property named "topRightCorner" is a boolean value to set this corner will round or not. By default it is true.
Property named "bottomLeftCorner" is a boolean value to set this corner will round or not. By default it is true.
Property named "bottomRightCorner" is a boolean value to set this corner will round or not. By default it is true.

# Example:-

<unique.solution.hvimageview.RoundedCornerImageView
        android:id="@+id/roundimage1"
        android:layout_width="300dp"
        android:layout_height="300dp"
        android:src="@drawable/ic_launcher_background"
        android:layout_gravity="center"
        app:cornerRadius = "30"
        app:topLeftCorner="false"
        app:topRightCorner="true"
        app:bottomLeftCorner="true"
        app:bottomRightCorner="false" />
