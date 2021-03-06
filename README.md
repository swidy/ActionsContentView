ActionsContentView
===================

ActionsContentView is an standalone library implements actions/content swiping view.

The library doesn't use any specific code introduced in new Android SDK versions. This allows develop an application with an action/content swiping view for every version of Android from 2.2 and up.

Some advantages of this library:

* ability to slide view by touch
* it is easy to adjust size of actions bar in XML
* support of all Android SDK version starting from 2.0 and up

There is one limitation:

* all horizontal scrolling views will not work at bounds of this view


![Example application looks on phone][1]

![Example application looks on tablet][2]

Here is exmple of usage ActionsContentView as element of XML layout:

    <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        android:layout_width="match_parent"
        android:layout_height="match_parent" >
    
    ...
    
        <shared.ui.actionscontentview.ActionsContentView
            android:id="@+id/content"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            app:actions_layout="@layout/actions"
            app:content_layout="@layout/content" />
    
    ...
    
    </RelativeLayout>

Try out the example application on the Android Market: [ActionsContentView Example][3].

Developed By
============

* Steven Rudenko - <steven.rudenko@gmail.com>



License
=======

    Copyright 2012 Steven Rudenko

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.




 [1]: http://lh6.ggpht.com/tdaPikC_eg8LMwoVm8lLu0TG3qMW4Vghw1e2q1e8BeY9pR7WitVZ7hsT_R593WhwLK8
 [2]: http://lh4.ggpht.com/gjSc5WXfxL2hZqq6Rno0Byx3nHEf7-n4G8ceDV3BC0e4wm2RpFxC7I8VMPgSA9fvKyw
 [3]: https://play.google.com/store/apps/details?id=sample.actionscontentview
