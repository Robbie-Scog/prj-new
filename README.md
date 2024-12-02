<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Birhtday Card</title>
    <link rel="stylesheet" href="cardstyle.css">
    <script defer src="cardscript.js"></script>
</head>
<body>
            <div id="card-screen" class="hidden">        
                <div class="card">
                    <div class="card-page front" style="display: flex; flex-direction: column;">
                        <img style="height: 300px;" src="imgs/flowers.jpg">
                        <p>Chạm vào thẻ để nhận lời chúc.</p>
                    </div>
                    <div class="card-page back">
                        
                        <div class="content">
                            <img style="height: 200px;" src="imgs/blue-cake.jpg" >
                            <p>Cũng không biết chúc gì, thôi thì chúc bạn qa tuổi mới ăn mau chóng lớn, sớm</p>
                            <p>ngày tu thành chánh quả nhá. Wish you all the best! Còn nữa, thank you for</p>
                            <p>being there for me. I truly appreciate your efforts being a supportive partner.</p>
                            <p> Now, rate this card:</p>   
                            
                            <div class="star-container" style="display: flex; gap: 20px; justify-content: center; align-items: center;">
                                <!-- Fake Star: Disappears when clicked -->
                                <div class="fake-star">
                                    <img id="fake-star" style="height: 50px; cursor: pointer;" src="imgs/fake-star.png" onclick="hideFakeStar()">
                                </div>
                                
                                <!-- Real Star: Redirects to flower.html when clicked -->
                                <div class="real-star">
                                    <img id="real-star" style="height: 50px; cursor: pointer;" src="imgs/real-star.png" onclick="redirectToFlower()">
                                </div>  
                            </div>
                        </div>

                    </div>
                </div>
            </div>   
</body>
</html>
