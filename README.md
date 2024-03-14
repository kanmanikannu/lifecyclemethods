# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by: Kanmani U
Registeration Number : 212221040070
*/
```

package com.example.myapplicationex1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart() {
        super.onStart();
        Toast toast1 = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        toast1.show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Toast toast2 = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
        toast2.show();
    }

    protected void onPause() {
        super.onPause();
        Toast toast3 = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
        toast3.show();
    }

    protected void onResume() {
        super.onResume();
        Toast toast4 = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
        toast4.show();
    }

    protected void onStop() {
        super.onStop();
        Toast toast5 = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
        toast5.show();
    }

    protected void onDestroy() {
        super.onDestroy();
        Toast toast6 = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
        toast6.show();
    }
    

## OUTPUT

![EXP2 OUTPUT](https://github.com/kanmanikannu/lifecyclemethods/assets/114866367/758656e5-3868-4b67-a120-c4fefd5f8272)



## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
