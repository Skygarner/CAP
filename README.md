# CAP
capstone
---Layout---
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">


    <ImageView
        android:id="@+id/TitleImg"
        android:layout_width="match_parent"
        android:layout_height="129dp"
        app:srcCompat="@drawable/remindertitle" />

    <ImageButton
        android:id="@+id/setBtn"
        android:layout_width="320dp"
        android:layout_height="78dp"
        android:layout_marginHorizontal="50dp"
        app:srcCompat="@drawable/setreminders" />

    <ImageButton
        android:id="@+id/editBtn"
        android:layout_width="320dp"
        android:layout_height="75dp"
        android:layout_marginHorizontal="50dp"
        app:srcCompat="@drawable/editreminders" />

    <androidx.recyclerview.widget.RecyclerView
        android:layout_width="match_parent"
        android:layout_height="449dp"

        />


</LinearLayout>
------------
---reminder_add----
   <?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <TextView
            android:id="@+id/textView2"
            android:layout_width="331dp"
            android:layout_height="78dp"

            android:text="New Reminder"
            android:textSize="50dp" />

        <TextView
            android:id="@+id/textView8"
            android:layout_width="61dp"
            android:layout_height="34dp"
            android:layout_marginTop="15dp"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:text="Title"
            android:textSize="20dp"/>

        <EditText
            android:id="@+id/editTextTextPersonName"
            android:layout_width="match_parent"
            android:layout_height="44dp"
            android:background="@android:color/holo_blue_light"
            android:ems="10"
            android:inputType="textPersonName"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:singleLine="true"
            android:textSize="14dp"
            android:text="Enter Title" />

        <TextView
            android:id="@+id/textView3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="5dp"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:text="Description"
            android:textSize="20dp"
            />

        <EditText
            android:id="@+id/editTextTextPersonName3"
            android:layout_width="match_parent"
            android:layout_height="44dp"
            android:background="@android:color/holo_blue_light"
            android:ems="10"
            android:inputType="textPersonName"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:singleLine="true"
            android:textSize="14dp"
            android:text="Enter Description" />

        <TextView
            android:id="@+id/textView4"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="5dp"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:text="Date"
            android:textSize="25dp" />

        <EditText
            android:id="@+id/editTextTextPersonName4"
            android:layout_width="match_parent"
            android:layout_height="44dp"
            android:background="@android:color/holo_blue_light"
            android:ems="10"
            android:inputType="textPersonName"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:singleLine="true"
            android:textSize="14dp"
            android:text="Enter Date" />

        <TextView
            android:id="@+id/textView5"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginTop="5dp"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:text="Time"
            android:textSize="25dp" />

        <EditText
            android:id="@+id/editTextTextPersonName2"
            android:layout_width="match_parent"
            android:layout_height="44dp"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:background="@android:color/holo_blue_light"
            android:ems="10"
            android:inputType="textPersonName"
            android:singleLine="true"
            android:text="Set Time"
            android:textSize="14dp" />

        <Button
            android:id="@+id/button"
            android:layout_width="match_parent"
            android:layout_height="71dp"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="25dp"
            android:layout_marginRight="10dp"
            android:backgroundTint="@android:color/holo_blue_light"

            android:text="Add" />

    </LinearLayout>


-----------------
--reminder_design---
<?xml version="1.0" encoding="utf-8"?>
<androidx.cardview.widget.CardView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    app:cardUseCompatPadding="true"
    app:cardElevation="5dp"
    app:cardCornerRadius="10dp"
    app:contentPadding="10dp"
    android:layout_height="150dp">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="100dp"
            android:layout_height="50dp"
            android:layout_weight="1"
            android:orientation="vertical">

            <TextView
                android:id="@+id/textView6"
                android:layout_width="34dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="title" />

            <TextView
                android:id="@+id/textView7"
                android:layout_width="373dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="description" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="297dp"
            android:layout_height="20dp"
            android:layout_weight="1"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textView10"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="dd" />

            <TextView
                android:id="@+id/textView11"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="mm" />

            <TextView
                android:id="@+id/textView12"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="year" />

        </LinearLayout>

    </LinearLayout>

</LinearLayout>
</androidx.cardview.widget.CardView>

---------------
