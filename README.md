<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            font-size: 25px;
            box-sizing: border-box;

        }

        body {
            margin: 0;
            padding: 0;
            background-color: #edefed;

        }



        .img {

            margin-left: 640px;
            transform: translateY(-590px);




        }


        .form {
            display: flex;
            justify-content: center;
            /* Yatayda ortalar */
            align-items: center;
            /* Dikeyde ortalar */
            height: 100vh;
            /* Tam ekran yüksekliği */
            margin: 480px;
            flex-direction: column;
            /*dikey şekilde sığdırır*/

        }


        .box {
            height: 1400px;
            width: 900px;
            background-color: white;
            border-top: 8px solid #9d9e9e;
            margin: -5px;
            border-radius: 8px;
            padding: 35px;
            margin-top: 1250px;

        }

        .box h1 {
            font-size: 45px;
            text-align: left;
            
        }


        .eposta-div,
        .adsoyad-div,
        .vardiya-div,
        .hat-div,
        .bassaat-div,
        .bitsaat-div,
        .muskod-div,
        .boruboy-div,
        .borucap-div,
        .boruetkal-div,
        .uretad-div,
        .uretmet-div,
        .durkod-div,
        .zorfıre-div,
        .norfıre-div,
        .fırened-div,
        .fıreac-div {

            height: 1700px;
            width: 900px;
            background-color: white;
            outline: none;
            margin: 15px;
            border-radius: 8px;
            border: 1mm solid hsla(180, 1%, 82%, 0.988);
            padding: 25px;
            margin-top: 0px;
            margin-bottom: 20px;

        }

        .eposta,
        .adsoyad,
        .vardiya,
        .hat,
        .basaat,
        .bitsaat,
        .muskod,
        .boruboy,
        .borucap,
        .boruetkal,
        .uretad,
        .uretmet,
        .durkod,
        .zorfıre,
        .norfıre,
        .fırened .zorfıre,
        .fıreac {
            font-size: 30px;
            font-weight: lighter;
            text-align: left;
        }


        .muskod-div input[type="text"],
        .boruboy-div input[type="text"],
        .uretad-div input[type="input"],
        .uretmet-div input[type="input"],
        .zorfıre-div input[type="input"],
        .norfıre-div input[type="input"],
        .fıreac-div input[type="input"]
         {
            border: none;
            /* Kenarlığı kaldırır */
            outline: none;
            /* Odaklanıldığında görünen çerçeveyi kaldırır */
            border-bottom: 2px solid hwb(0 0% 100% / 0.508);
        }
    </style>
</head>

<body>
    <br><br><br><br><br>
    <br><br><br><br><br>
    <br><br><br><br><br>
    <br><br><br><br><br>
    
    




    <div class="img">
        <img src="img/kuzeyboru-logo-2024.png" width="920px" height="300px">


    </div>
    <br>
    <div class="form">
        <div class="box">
            <h1>VARDİYA ÜRÜN TAKİP FORMU</h1>
            <p>KUZEYBORU FİRMASINA AİT ÜRÜN TAKİP FORMU</p>
        </div>
        <br>

        <div class="eposta-div">
            <div class="eposta">E-POSTA</div>
            <br>
            <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
            <label for="vehicle1">Yanıtıma eklenecek e-posta adresi olarak kaydet</label><br>
        </div>
        <br><br>
        <div class="adsoyad-div">
            <div class="adsoyad">AD SOYAD</div>
            <div class="input-div" required>
                <br>
                <select name="answer">
                    <option value="" disabled selected>Seçin</option>
                    <option value="ahmet_dogan">Ahmet DOĞAN</option>
                    <option value="ahmet_dogan">Mehmet DOĞAN</option>
                    <option value="ahmet_dogan">Fadime ÖCAL</option>
                </select>
            </div>
        </div>

        <br><br>
        <div class="vardiya-div">
            <div class="vardiya">VARDİYA</div>
            <div class="input-div">
                <br>
                <select name="answer">
                    <option value="" disabled selected>Seçin</option>
                    <option value="Vardiya-1">Vardiya-1(07:00-15:00)</option>
                    <option value="Vardiya-2">Vardiya-2(15:00-23:00)</option>
                    <option value="Vardiya-3">Vardiya-3(23:00-07:00)</option>


                </select>
            </div>
        </div>
        <br><br>
        <div class="hat-div">
            <div class="hat">HAT SEÇ</div>
            <br>
            <select name="answer">
                <option value="" disabled selected>Seçin</option>
                <option value="HAT-1">HAT-1</option>
                <option value="HAT-2">HAT-2</option>
                <option value="HAT-3">HAT-3</option>
                <option value="HAT-4">HAT-4</option>
            </select>
        </div>

        <br><br>
        <div class="bassaat-div">
            <div class="basaat">BAŞLANGIÇ SAATİ</div>
            <br>
            <p><i><u>Lütfen üretime başlama saatini giriniz:</u></i></p>
            <div class="input-div"><input type="time" name="answer" placeholder="Baş Saat Girin"></div>

        </div>

        <br><br>
        <div class="bitsaat-div">
            <div class="bitsaat">BİTİŞ SAATİ</div>
            <br>
            <p><i><u>Lütfen duruş ve bitiş saatini giriniz:</u></i></p>
            <div class="input-div"><input type="time" name="answer" placeholder="Bitiş Saati Girin"></div>

        </div>


        <br><br>
        <div class="muskod-div">
            <div class="muskod">MÜŞTERİ KODU</div>
            <br>
            <p><i><u>Müşteri Numarası yok ise lütfen 0 (sıfır) yazınız.</u></i></p>
            <div class="input-div"><input type="text" name="answer" placeholder="Yanıtınız"required></div>



        </div>

        <br><br>
        <div class="boruboy-div">
            <div class="boruboy">BORU BOYU</div>
            <br>
            <div class="input-div"><input type="text" name="answer" placeholder="Yanıtınız"required></div>

        </div>


        <br><br>
        <div class="borucap-div">
            <div class="borucap">MALZEME SINIFI BORU ÇAPI</div>
            <div class="input-div"required></div>
            <br>
            <select name="answer">
                <option value="" disabled selected>Seçin</option>
                <option value="1">20</option>
                <option value="2">25</option>
                <option value="3">32</option>
                <option value="4">40</option>
                <option value="5">50</option>
                <option value="6">63</option>
                <option value="7">75</option>
                <option value="8">90</option>
                <option value="9">110</option>
                <option value="10">125</option>
            </select>
        </div>



        <br><br>
        <div class="boruetkal-div">
            <div class="boruetkal">BORU ET KALINLIĞI</div>
            <div class="input-div"></div>
            <br>
            <select name="answer">
                <option value="" disabled selected>Seçin</option>
                <option value="1">3,4</option>
                <option value="2">4,2</option>
                <option value="3">5,4</option>
                <option value="4">6,7</option>
                <option value="5">8,3</option>
                <option value="6">10,5</option>
                <option value="7">12,5</option>
                <option value="8">15,0</option>
                <option value="9">15,0</option>
                <option value="10">18,3</option>
                <option value="10">20,8</option>
            </select>

        </div>

        <br><br>
        <div class="uretad-div">
            <div class="uretad">ÜRETİLEN ADET</div>
            <br>
            <div class="input-div"><input type="input" name="answer" placeholder="Yanıtınız"></div>

        </div>

        <br><br>
        <div class="uretmet-div">
            <div class="uretmet">ÜRETİLEN METRE</div>
            <br>
            <div class="input-div"><input type="input" name="answer" placeholder="Yanıtınız"></div>


        </div>
        <br><br>
        <div class="durkod-div">
            <div class="durkod">DURUŞ KODU</div>
            <div class="input-div"></div>
            <br>
            <select name="answer">
                <option value="" disabled selected>Seçin</option>
                <option value="1">AYAR YOL VERME SÜRESİ</option>
                <option value="2">BAKIMCI BEKLEME SÜRESİ</option>
                <option value="3">BLOWER EMİCİ FİLTRE TEMİZLİĞİ</option>
                <option value="4">CHILLER ARIZASI</option>
                <option value="5">ÇAP/ET KALINLIĞI İNCE AYAR</option>
                <option value="6">ÇEKİCİ ARIZASI</option>

            </select>


        </div>

        <br><br>
        <div class="zorfıre-div">
            <div class="zorfıre">ZORUNLU FİRE KG</div>
            <br>
            <div class="input-div"><input type="input" name="answer" placeholder="Yanıtınız"></div>
        </div>
        <br><br>
        <div class="norfıre-div">
            <br>
            <div class="norfıre">NORMAL FİRE KG</div>
            <div class="input-div"><input type="input" name="answer" placeholder="Yanıtınız"></div>
        </div>
        <br><br>
        <div class="fırened-div">
            <div class="fırened">FİRE NEDENİ</div>
            <div class="input-div"></div>
            <br>
            <select name="answer">
                <option value="" disabled selected>Seçin</option>
                <option value="1">AYAR YOL VERME SÜRESİ</option>
                <option value="2">BAKIMCI BEKLEME SÜRESİ</option>
                <option value="3">BLOWER EMİCİ FİLTRE TEMİZLİĞİ</option>
                <option value="4">CHILLER ARIZASI</option>
                <option value="5">ÇAP/ET KALINLIĞI İNCE AYAR</option>
                <option value="6">ÇEKİCİ ARIZASI</option>

            </select>
        </div>

        <br><br>
        <div class="fıreac-div">
            <div class="fıreac">FİRE AÇIKLAMA</div>
            <br>
            <div class="input-div"><input type="input" name="answer" placeholder="Yanıtınız"></div>
        </div>

        <div class="button">
            <br>
            <input type="button" value="Gönder">
        </div>
    </div>
</body>

</html>
