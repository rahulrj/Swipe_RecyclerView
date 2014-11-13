SwipeList_RecyclerView
======================

<h3>RecyclerView</h3><br>
The RecyclerView widget is a more advanced and flexible version of ListView. This widget is a container for displaying large data sets that can be scrolled very efficiently by maintaining a limited number of views. Use the RecyclerView widget when you have data collections whose elements change at runtime based on user action or network events.<br>
It was introduced in Android Lollypop (5.0) and you can read more about it <a href="https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html">here.</a><br>


Using the originally built library<br>
<a href="https://github.com/47deg/android-swipelistview">47deg/android-swipelistview</a><br>
<a href="https://github.com/47deg/android-swipelistview-sample">47deg/android-swipelistview-sample</a>  ( sample of the above library )

I have modified the sample and also the library to work with a RecyclerView instead of a ListView.<br>
Just Playing around with RecyclerView.<br><br>

Here is the screenshot for the view.
![alt tag](http://i.imgur.com/ysLO3dA.png) <br>

<h3>XML Usage</h3>
```<com.fortysevendeg.swipelistview.SwipeListView
            xmlns:swipe="http://schemas.android.com/apk/res-auto"
            android:id="@+id/example_lv_list"
            android:listSelector="#00000000"
            android:layout_width="fill_parent"
            android:layout_height="wrap_content"
            swipe:swipeFrontView="@+id/front"
            swipe:swipeBackView="@+id/back"
            swipe:swipeActionLeft="[reveal | dismiss]"
            swipe:swipeActionRight="[reveal | dismiss]"
            swipe:swipeMode="[none | both | right | left]"
            swipe:swipeCloseAllItemsWhenMoveList="[true | false]"
            swipe:swipeOpenOnLongPress="[true | false]"
            swipe:swipeAnimationTime="[miliseconds]"
            swipe:swipeOffsetLeft="[dimension]"
            swipe:swipeOffsetRight="[dimension]"
           />
           ```





