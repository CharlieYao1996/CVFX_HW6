# CVFX_HW6
 Please click on the photo to enter the video
  # 1.Take videos
  
  | orign_1        | orign_2        | orign_3  |
  | :-------------: |:-------------:| :-----:|
  | [![](http://img.youtube.com/vi/TYtgs9knkJ4/0.jpg)](http://www.youtube.com/watch?v=TYtgs9knkJ4 "")   | [![](http://img.youtube.com/vi/21RdlwbpWR0/0.jpg)](http://www.youtube.com/watch?v=21RdlwbpWR0 "")      | [![](http://img.youtube.com/vi/dLcWU2yw-xY/0.jpg)](http://www.youtube.com/watch?v=dLcWU2yw-xY "") |
  
  >>
  

  
  # 2.Make these visual effects with ORB-SLAM2
  
  ![image](https://github.com/CharlieYao1996/CVFX_HW6/blob/master/screenshot.png?raw=true)
  在比較三個原始檔案的處理後我們決定使用origin_3來操作這次的作業，推測是因為場景明亮以及角度移動幅度小。
  
  # 3.Make these visual effects with any post-production software
  
| output2-1        | output3-1     | 
| :-------------: |:-------------:| 
| [![](http://img.youtube.com/vi/gPdjCcPHROo/0.jpg)](http://www.youtube.com/watch?v=gPdjCcPHROo "")       |[![](http://img.youtube.com/vi/7O5jF0ynfUc/0.jpg)](http://www.youtube.com/watch?v=7O5jF0ynfUc "") |
  
  
我們這次使用AE(After Effect)來進行Match-Moving的實作，AE上有內建track camera的功能，我們簡單的利用此功能製作了上述效果，不過也許是因為影片拍攝時晃動過度，有些角度的track效果明顯的很差，所以我們擷取了部分效果較好的片段來進行操作，而在2-1我們利用空間座標差異製造出遠近的感覺，效果看起來還不錯。而3-1的效果是最好的，在多個面向甚至是在桌面上新增圖示，更加了一些gif都有不錯的效果。
  
  
  # 4.Compare above methods
  
  可能是在操作上有些失誤或是我們對於ORB-SLAM2的操作還不熟悉，我們使用ORB-SLAM2所呈現的效果其實並不太好，可以看到加入的文字其實還是會跟著畫面浮動。
  在可控度以及多面向的操作上，AE還是比較直觀的能夠呈現我們想要的畫面。在有詳細內容UI的情形下，AE能夠提供我們的幫助相對機器學習來說更直接了。
  希望在繼續鑽研後我們也可以利用ORB-SLAM2做出跟AE一樣好甚至是更好的效果。
  
  # 5.Make some special effects based on the pose information
  
  # 6.Insert a 3D model to your video
  
  | output1-1        |   output1-2   | 
  | :-------------: |:-------------:| 
  | [![](http://img.youtube.com/vi/aKZJNS_WkwM/0.jpg)](http://www.youtube.com/watch?v=aKZJNS_WkwM "")        |   [![](http://img.youtube.com/vi/eEKa6103t0A/0.jpg)](http://www.youtube.com/watch?v=eEKa6103t0A "")      |
  
  在手上加上了火焰特效，雖然還是有些許的浮動，但是看起來還不錯，不過因為origin_1拍的並沒有很好，背景人太多太雜，還有在影片開頭晃動幅度太大導致對焦不準確，導致影響到後面一連續的座標處理，不過因時間關係沒有再拍新影片，影片品質提升後效果應該會更好。

  


