<?xml version="1.0" encoding="utf-8"?> <androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:tools="http://schemas.android.com/tools"
android:id="@+id/main" android:layout_width="match_parent" android:layout_height="match_parent" tools:context=".MainActivity">
<LinearLayout android:layout_width="match_parent" android:layout_height="match_parent" android:orientation="vertical" android:textAlignment="center">
<TextView android:id="@+id/textView3" android:layout_width="match_parent" android:layout_height="wrap_content" android:text="WELCOME" android:textAlignment="center" />
<EditText android:id="@+id/editTextText3" android:layout_width="match_parent" android:layout_height="wrap_content" android:ems="10" android:inputType="text" android:text="Enter your name here" />
<RadioGroup android:layout_width="match_parent" android:layout_height="match_parent" >
<RadioButton android:id="@+id/radioButton" android:layout_width="match_parent" android:layout_height="wrap_content" android:text="Male" />
<RadioButton android:id="@+id/radioButton2" android:layout_width="match_parent" android:layout_height="wrap_content" android:text="Female" />
<TextView android:id="@+id/textView5" android:layout_width="match_parent" android:layout_height="wrap_content" android:text="Languages Known" />
<CheckBox android:layout_width="match_parent" android:layout_height="wrap_content" android:text="English" />
<CheckBox android:id="@+id/checkBox2" android:layout_width="match_parent" android:layout_height="wrap_content" android:text="Kannada" />
<ProgressBar android:id="@+id/progressBar" style="?android:attr/progressBarStyle" android:layout_width="match_parent" android:layout_height="wrap_content" />
<Button android:id="@+id/button4" android:layout_width="match_parent" android:layout_height="wrap_content" android:text="Submit" />
<ImageView android:id="@+id/imageView2" android:layout_width="match_parent" android:layout_height="wrap_content" app:srcCompat="@drawable/img" />
</RadioGroup>
</LinearLayout>
</androidx.constraintlayout.widget.ConstraintLayout> 
