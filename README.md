<!DOCTYPE html>
<html>
    <head>
        <title>ALCHEMY</title>
        <script src="https://kit.fontawesome.com/8eb5905426.js" crossorigin="anonymous"></script>
        <style>
            h1 {
                text-align: center;
                border-color: gray;
                padding: 20px;
                background-color: rgb(239,239,239);
                margin-top: 0px;
            }
            .search{
                display: flex;
                justify-content: center;
                position: relative;
                text-align: center;
                margin: 0 auto;
            }
            #Ta{
                text-align: center;
                width: 700px;
                height: 70px;
                outline: none;
                border-top: 0px;
                border-left: 0px;
                border-right: 0px;
                border-bottom-color: black;            }
            input::placeholder{
                font-size: 20px;
            }
            .fa-search{
                position: relative;
                left: 15px;
                top: 40px;
                margin: 0;
            }
            .S{
                margin-top: 300px;
                display: grid;
                grid-template-columns: 1fr 2fr 1fr;
            }
            .s{
                background-color: rgb(239,239,239);
                border-bottom: 100px;
                text-align: center;
            }
            .lank{
                margin: 30px;
                color: blue;
            }
            #baro{
                margin-left: 10px;
                margin-right: 10px;
            }
            .barod{
                display: grid;
                grid-template-columns: 1fr 1fr;
            }
            .exam{
                margin: 60px;
                color: blue;
            }
        </style>
    </head>
    <body>
        <h1>ALCHEMY</h1> 
        <div class="search">
            <i class="fas fa-search"></i> 
            <input id="Ta" type="text" placeholder="FIND YOUR UNIV.">
        </div>
        <div class="S">
            <div class="s">
                <h2>인서울 대학 순위 보기</h2>
                <dl>
                    <dt class="lank">서울대></dt>
                    <dt class="lank">연세대></dt>
                    <dt class="lank">고려대></dt>
                    <dt class="lank">한양대></dt>
                    <dt class="lank">성균관대></dt>
                    <dt class="lank">서강대></dt>
                </dl>
            </div>
            <div class="s" id="baro">
                <h2>대학별 입시요강 바로보기</h2>
                <div class="barod">
                    <dl>
                        <dt class="lank">서울대></dt>
                        <dt class="lank">연세대></dt>
                        <dt class="lank">고려대></dt>
                        <dt class="lank">한양대></dt>
                        <dt class="lank">성균관대></dt>
                        <dt class="lank">서강대></dt>
                    </dl>
                    <dl>
                        <dt class="lank">서울대></dt>
                        <dt class="lank">연세대></dt>
                        <dt class="lank">고려대></dt>
                        <dt class="lank">한양대></dt>
                        <dt class="lank">성균관대></dt>
                        <dt class="lank">서강대></dt>
                    </dl>
                </div>  
            </div>
            <div class="s">
                <h2>모의평가 등급컷보기</h2>
                <dl>
                    <dt class="exam">3월></dt>
                    <dt class="exam">4월></dt>
                    <dt class="exam">6월></dt>
                    <dt class="exam">7월></dt>
                </dl>
            </div>
        </div>
    </body>
</html>
