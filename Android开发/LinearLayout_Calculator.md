### 布局文件 ###
    <?xml version="1.0" encoding="utf-8"?>
    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    >

    <TextView
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1"
        android:text="0"
        android:gravity="center_vertical|end"
        android:textSize="50sp"
        android:id="@+id/resultText" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="3"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0"
            android:layout_weight="1"
            android:orientation="horizontal"
            >
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="C"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="+/-"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="%"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="÷"
                android:textSize="50sp"/>
        </LinearLayout>
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0"
            android:layout_weight="1"
            android:orientation="horizontal"
            >
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="7"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="8"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="9"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="x"
                android:textSize="50sp"/>
        </LinearLayout>
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0"
            android:layout_weight="1"
            android:orientation="horizontal"
            >
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="4"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="5"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="6"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="—"
                android:textSize="50sp"/>
        </LinearLayout>
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0"
            android:layout_weight="1"
            android:orientation="horizontal"
            >
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="1"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="2"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="3"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="+"
                android:textSize="50sp"/>
        </LinearLayout>
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0"
            android:layout_weight="1"
            android:orientation="horizontal"
            >
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="2"
                android:text="0"
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="."
                android:textSize="50sp"/>
            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:text="="
                android:textSize="50sp"/>

        </LinearLayout>
    </LinearLayout>
    </LinearLayout>

### 效果图 ###
![](http://upload-images.jianshu.io/upload_images/2106579-9cde15ecd8099d17.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
