# Homework5-Multi-view 3D Visual Effects

## Multi-view images by ourselves
- Motion parallax

    下兩圖為書桌角落，並以中間的書本以及盒玩作為中心來拍攝。
利用輕微調整相機視角，使第一張的視角偏左側，而第二張較為右側。
![](https://i.imgur.com/TGOa4Tw.jpg)
![](https://i.imgur.com/BLKZEB5.jpg)

- Stop motion

    下圖是請model維持相同姿勢不動，而攝影者繞著人物拍攝的圖像。
![](https://i.imgur.com/AJexvsL.jpg)

- Live photo

    下方為背景不動，而人物自行旋轉的連拍圖像。
![](https://i.imgur.com/14scj0s.jpg)

## Image alignment results
- Motion parallax
    - Matching
    ![](https://i.imgur.com/X3BwXRw.jpg)
    
    - Alignment
    ![](https://i.imgur.com/TtlrrHz.jpg)
    
- Stop motion
    - Matching
    
      ![](https://i.imgur.com/BSI1XAZ.jpg)
    
    - Alignment
    
      由於match的效果不佳，例如頭match到樓梯、鞋子match到平面圖，所以導致alignment的成果極度扭曲。因此，我們的動圖不採用alignment後的結果。 
    
      ![](https://i.imgur.com/1s0k92H.jpg)

- Live photo
    - Matching 
    
      此為從一連串照片中取一組作為範例，左邊為原版的照片，右邊為上一組alignment後的結果，將左圖和右圖進行match。
    
      ![](https://i.imgur.com/02z5whA.jpg)
    
    - Alignment
    
      ![](https://i.imgur.com/5rECoi9.jpg)


## Multi-view 3D visual effects and effect enhancement
以下為3種不同的3D visual effects，並放上effect enhancement後的結果作比較。Effect enhancement的圖皆是用PhotoImpact進行修圖。
- Motion parallax
    - Original:
    
      以中間的書本以及盒玩為主體來維持不動，並輕微改變相機視角使周圍景物晃動而產生。作法主要是將兩張原圖進行alignment後，再將align過的成果與原圖對比，產生動圖。
      ![](https://i.imgur.com/fUORS4I.gif)
    
    - Effect enhancement:
    
      透過修改兩張圖片中的其中一張圖，去改變盒玩的位置與角度，讓它與另一張圖的盒玩位置與角度幾乎不變，以達到更佳的3D效果。
      ![](https://i.imgur.com/yhutiek.gif)
    
- Stop motion
    - Original:
    
      此為展示靜止不動的動作。作法為從人的背後，以不同視角拍攝照片，最後做成動圖。
    
      ![](https://i.imgur.com/CN2UbdE.gif)
    
    - Effect enhancement:
    
      原本的結果因為每張圖片的亮度不同，所以在某些地方會有閃爍的感覺（像是衣服的部分會有時亮有時暗）。修圖方式為改變每張圖的光線及色彩，調整其亮度、對比以及彩度，除了改善圖片本身的色彩之外，也讓每張圖片的亮度更加相似，減少原本動圖閃爍的感覺。
   
      ![](https://i.imgur.com/fkjCqQU.gif)
    
- Live photo
    - Original:
    
      此為原始圖檔直接產生動圖的結果，由於尚未經過align的處理，因此整個背景容易因為拍照的不穩定而產生晃動。
    
      ![](https://i.imgur.com/CvTzGWK.gif)
    
    - Original (aligned):
    
      下圖作法為連拍數張照片，兩張照片進行alignment，完成後若成果有黑邊則先將照片剪裁至無黑邊的大小，再用剪裁完的圖片和下一張照片進行alignment，以此類推，最後將所有alignment的成果做成動圖。alignment後的動圖改善了整體背景的晃動，但造成了天花板有些微的空間扭曲以及地板稍浮動的現象。
    
      ![](https://i.imgur.com/4Wmf5bA.gif)
    
    - Effect enhancement:
    
      由於在align過後，後面的背景會有扭曲的狀況，因此用修圖的方式盡量將每張圖的背景都固定成與第一張圖相同的背景。由下圖結果可以看出，雖然前方地板因為較難修圖而仍有一點扭曲，但像是天花板、牆壁，以及後方地板等大部分的背景都有明顯的改善。
    
      ![](https://i.imgur.com/E1sfvYj.gif)
    
