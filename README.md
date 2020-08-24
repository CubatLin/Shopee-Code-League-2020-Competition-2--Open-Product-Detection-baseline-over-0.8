Shopee Code League 2020- [Open]Product Detection- Baseline over 0.8
======================================
* **My Medium about Shopee Code League 2020:**
[【Shopee Code League】2020蝦皮數據競賽系列賽參賽心得&亞太區15th做法分享 ](https://medium.com/@ethan1126.ilink/shopee-code-league-2020%E8%9D%A6%E7%9A%AE%E6%95%B8%E6%93%9A%E7%AB%B6%E8%B3%BD%E7%B3%BB%E5%88%97%E8%B3%BD%E5%8F%83%E8%B3%BD%E5%BF%83%E5%BE%97-%E4%BA%9E%E5%A4%AA%E5%8D%8015th%E5%81%9A%E6%B3%95%E5%88%86%E4%BA%AB-6d228b681935?source=---------2------------------)

* **Competition Link:** [[Open] Shopee Code League - Product Detection- Detect Real Product On E-commercial Platform ](https://www.kaggle.com/c/shopee-product-detection-open)

* **Team & Ranking**
```
Team:台灣梯度下降第一品牌
Members:Alexi,LuJian,Ming-Xiang,Ethan
Private Leaderboard Score : 0.81826
Ranking: 67 of 646 teams
```

![image](https://github.com/CubatLin/Shopee-Code-League-2020-Competition-2--Open-Product-Detection-baseline-over-0.8/blob/master/Shopee%20Code%20League-%20Ranking.JPG)

* **VGG16 BaseLine Model:** [VGG16](https://github.com/CubatLin/Shopee-Code-League-2020-Competition-2--Open-Product-Detection-baseline-over-0.8/blob/master/ShopeeCodeLeague_2_VGG16.ipynb)

* **XGBoost:**  [XGBoost ](https://github.com/CubatLin/Shopee-Code-League-2020-Competition-2--Open-Product-Detection-baseline-over-0.8/blob/master/CNNtoXGB_128dims.ipynb)

* **Background:** 
At Shopee, we always strive to ensure the correct listing and categorization of products. For example due to the recent pandemic situation, face masks become extremely popular for both buyers and sellers, everyday we need to categorize and update a huge number of masks items. A robust product detection system will significantly improve the listing and categorization efficiency. But in the industrial field the data is always much more complicated and there exists mis-labelled images, complex background images and low resolution images, etc. The noisy and imbalanced data and multiple categories make this problem still challenging in the modern computer vision field.

* **Task:** 
In this competition, a multiple image classification model needs to be built. There are ~100k images within 42 different categories, including essential medical tools like masks, protective suits and thermometers, home & living products like air-conditioner and fashion products like T-shirts, rings, etc. For the data security purpose the category names will be desensitized. The evaluation metrics is top-1 accuracy.

* **Keywords:** 
VGG16, EfficientNet, Xception, MobileNet, XGBoost 

* **And here's a short solution of competition 1- order brushing!(Score over 0.95):** [Order Brushing! ](https://github.com/CubatLin/Shopee-Code-League-2020-Competition-2--Open-Product-Detection-baseline-over-0.8/blob/master/Pandas%20War-%20Order%20Brushing.ipynb)
