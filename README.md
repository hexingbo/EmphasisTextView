# EmphasisTextView


Screenshots           
===========
![Demo Screenshot][1]

### 第三步：在XML复制如下代码：
```
<com.athkalia.emphasis.EmphasisTextView
            android:id="@+id/main_activity_first_text_view"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:paddingBottom="20dp"
            android:paddingTop="20dp"
            android:textSize="30sp" />
```
======

### 第四步：拷贝如下代码到activity实现图片第一个效果
```java
private void setUpFirstEmphasisTextView() {

        firstEmphasisTextView.setText("saladSALAD");
        firstEmphasisTextView.setTextToHighlight("sa");
        firstEmphasisTextView.setTextHighlightColor("#ff3393b4");
        firstEmphasisTextView.highlight();
}
```

### 拷贝如下代码到activity实现图片第二个效果
```java
private void setUpSecondEmphasisTextView() {

        secondEmphasisTextView.setText("saladSALAD");
        secondEmphasisTextView.setTextToHighlight("sa");
        secondEmphasisTextView.setTextHighlightColor(android.R.color.black);
        secondEmphasisTextView.highlight();
    }
```

### 拷贝如下代码到activity实现图片第三个效果
```java
private void setUpThirdEmphasisTextView() {

        thirdEmphasisTextView.setText("saladsalad");
        thirdEmphasisTextView.setTextToHighlight("sa");
        thirdEmphasisTextView.setTextHighlightColor("#ffff0000");
        thirdEmphasisTextView.setCaseInsensitive(true);
        thirdEmphasisTextView.highlight();
}
```

### 拷贝如下代码到activity实现图片第四个效果
```java
private void setUpFourthEmphasisTextView() {

        fourthEmphasisTextView.setText("saladSaladSALAD");
        fourthEmphasisTextView.setTextToHighlight("SA");
        fourthEmphasisTextView.setTextHighlightColor("#ff00ff00");
        fourthEmphasisTextView.setCaseInsensitive(true);
        fourthEmphasisTextView.highlight();
    }
```

### 拷贝如下代码到activity实现图片第五个效果
```java
private void setUpFifthEmphasisTextView() {

        fifthEmphasisTextView.setText("+301111111111");
        fifthEmphasisTextView.setTextToHighlight("+");
        fifthEmphasisTextView.setTextHighlightColor("#ff00ffff");
        fifthEmphasisTextView.highlight();
    }
```

### 拷贝如下代码到activity实现图片第六个效果
```java
 private void setUpSixthEmphasisTextView() {

        sixthEmphasisTextView.setText("pizzazzZ");
        sixthEmphasisTextView.setTextToHighlight("z");
        sixthEmphasisTextView.setTextHighlightColor(android.R.color.holo_green_light);
        sixthEmphasisTextView.setCaseInsensitive(false);
        sixthEmphasisTextView.setHighlightMode(HighlightMode.TEXT);
        sixthEmphasisTextView.highlight();
 }
```

### 拷贝如下代码到activity实现图片第七个效果
```java
 private void setUpSeventhEmphasisTextView() {

        seventhEmphasisTextView.setText("SaldZongLALALA");
        seventhEmphasisTextView.setTextToHighlight("A");
        seventhEmphasisTextView.setHighlightMode(HighlightMode.TEXT);
        seventhEmphasisTextView.setTextHighlightColor(android.R.color.holo_red_dark);
        seventhEmphasisTextView.highlight();
 }
```
