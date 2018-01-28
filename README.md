# ChasingLoading
dyzs practice view

# Capture
![](https://github.com/dyzs/ChasingLoading/blob/master/capture/chasing_loading.gif)

# Features
This is a chasing loading view.   
Three arcs chasing like infinitely, but they also have chase regular.

# Usage
xml sample  
```xml
<com.dyzs.akuma.chasingloading.ChasingLoading
    android:layout_width="match_parent"
    android:layout_height="150dp"
    app:clDfmWidth="5dp"
    app:clDfmSpacing="5dp"
    app:clDsRate="4"
    app:clFsRate="5"
    app:clMsRate="6"
    app:clColor1="@color/holy_pink"
    app:clColor2="@color/black"
    app:clColor3="@color/oxygen_green"
    />
```

# Attributes
## using sys attrs {android.R.attr.padding}
 - <code>clDfmWidth</code> : This attributes is set arcs width. 设置圆弧的宽度
 - <code>clDfmSpacing</code> : arc spacing. 圆弧之间的间距
 - <code>clDsRate</code>: inner arc rolling rate. 内弧转动的速率
 - <code>clFsRate</code>: center arc rolling rate.
 - <code>clMsRate</code>: outer arc rolling rate.
 - <code>clColor1</code>: outer arc color. 圆弧颜色
 - <code>clColor2</code>: center arc color.
 - <code>clColor3</code>: inner arc color.

# License

    Copyright (C) 2018 Misaka Mikoto(dyzs)

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
