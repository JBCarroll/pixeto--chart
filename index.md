<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
    <style>
        .box{
            padding: 25px 20px;
            min-height: 300px;
            max-width: 1060px;
            overflow: visible;
        }
        .box svg{
            overflow: visible;
        }
        .box_legends{
            position: relative;
            margin-top: 0px;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            width: 1060px;
            height: auto;
            border-top: 1px solid #bfbfbf;
            margin-bottom: 6em;
        }
        .years{
            width: 93px;
        }
        .years + .years{
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: flex-start;
            margin-left: 2.695em;
        }
        .years span{
            color: #bfbfbf;
        }
        .years .xline{
            height: 10px;
            width: 1px;
            background: #000000;
        }
        #Ellipse > g{
            z-index: 20 !important;
            position: relative;
            cursor: pointer;
        }
        circle:hover{
            fill: #e26c07 !important;
            /* transform: scale(1.2);
            transform-origin: left top; */
        }

        #Repeat_Grid_1 > g, #Repeat_Grid_1 > g > line{
            width: 100% !Important;
        }

        #rect,#grid{
            z-index: 1 !important;
        }

        /* INFORMATION CSS */
        .information__container{
            display: flex;
            overflow-x:scroll;
            height: auto;
            gap: 60px;
            max-width: 1060px;
        }

        .years__information{
            padding: 30px 10px;
        }

        .years__header{
            display: flex;
        }
        .years__header h3{
            font-size: 1.5rem;
        }


        .timeline-Footer{
            display: none !important;
        }
        .timeline-TweetList{
            display: flex !important;
        }
    </style>
</head>
<body>
    <div class="box">
        <div id="twitter_t"></div>
        <div id="twitter_m">
           <div id="twitter_container">
               <ul id="twitter_update_list"></ul>
           </div>
        </div>
        <div id="twitter_b"></div>
        <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="1060" height="308.5" viewBox="0 0 1060 308.5">
            <g id="Repeat_Grid_1" data-name="Repeat Grid 1" transform="translate(5.5 6.5)" width="100%" clip-path="url(#clip-path)">
                <g transform="translate(-366 -232.5)">
                  <line id="Line_1" data-name="Line 1" x2="1060" transform="translate(360.5 233.5)" fill="none" stroke="#e9e9e9" stroke-width="2"/>
                </g>
                <g transform="translate(-366 -182.5)">
                  <line id="Line_1-2" data-name="Line 1" x2="1060" transform="translate(360.5 233.5)" fill="none" stroke="#e9e9e9" stroke-width="2"/>
                </g>
                <g transform="translate(-366 -132.5)">
                  <line id="Line_1-3" data-name="Line 1" x2="1060" transform="translate(360.5 233.5)" fill="none" stroke="#e9e9e9" stroke-width="2"/>
                </g>
                <g transform="translate(-366 -82.5)">
                  <line id="Line_1-4" data-name="Line 1" x2="1060" transform="translate(360.5 233.5)" fill="none" stroke="#e9e9e9" stroke-width="2"/>
                </g>
                <g transform="translate(-366 -32.5)">
                  <line id="Line_1-5" data-name="Line 1" x2="1060" transform="translate(360.5 233.5)" fill="none" stroke="#e9e9e9" stroke-width="2"/>
                </g>
                <g transform="translate(-366 17.5)">
                  <line id="Line_1-6" data-name="Line 1" x2="1060" transform="translate(360.5 233.5)" fill="none" stroke="#e9e9e9" stroke-width="2"/>
                </g>
                <g transform="translate(-366 67.5)">
                  <line id="Line_1-7" data-name="Line 1" x2="1060" transform="translate(360.5 233.5)" fill="none" stroke="#e9e9e9" stroke-width="2"/>
                </g>
              </g>
            <path id="Path_1" data-name="Path 1" d="M361.336,381.8s44.278-51.109,92.388-49.6,34.723,99.984,93.938,100.914,69.754-119.826,94.171-151.99,46.349-48.767,96.325-48.767,65.914,57.811,66.255,79.267c.1,6.608,1.309,21.852,1.538,39.31.5,38.5,1.311,80.268,32.406,81.827,17.611.092,27.969-9.079,34.012-24.338,9.353-23.615,9.771-57.448,17.814-84.879,7.129-24.313,18.985-40.751,43.644-40.868,38.722.392,51.891,37.769,61.669,67.851,4.241,13.872,14.2,80.124,33.371,80.491s92.19-47.972,92.19-47.972l94.713-50.844,96.108-48.984,95.8-50.224" transform="translate(-355 -226)" fill="none" stroke="#79bc7a" stroke-linejoin="round" stroke-width="2"/>
            <g id="Ellipse" transform="translate(-355 -226)">
              <g class="ellipseClick1Btn" id="Ellipse_1" data-name="Ellipse 1" transform="translate(355 376)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick2Btn" id="Ellipse_2" data-name="Ellipse 2" transform="translate(445 323)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick3Btn" id="Ellipse_3" data-name="Ellipse 3" transform="translate(542 427)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick4Btn" id="Ellipse_4" data-name="Ellipse 4" transform="translate(636 275)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick5Btn" id="Ellipse_5" data-name="Ellipse 5" transform="translate(733 226)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick6Btn" id="Ellipse_6" data-name="Ellipse 6" transform="translate(833 425)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick7Btn" id="Ellipse_7" data-name="Ellipse 7" transform="translate(928 277)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick8Btn" id="Ellipse_8" data-name="Ellipse 8" transform="translate(1023 425)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick9Btn" id="Ellipse_9" data-name="Ellipse 9" transform="translate(1115 377)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick10Btn" id="Ellipse_10" data-name="Ellipse 10" transform="translate(1209 326)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick11Btn" id="Ellipse_11" data-name="Ellipse 11" transform="translate(1306 277)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
              <g class="ellipseClick12Btn" id="Ellipse_12" data-name="Ellipse 12" transform="translate(1402 227)" fill="none" stroke="none" stroke-width="2">
                <circle cx="6" cy="6" r="6" stroke="#fff"/>
                <circle cx="6" cy="6" r="5" fill="#77bc78" onmouseover="this.setAttribute('r', '10');" onmouseout="this.setAttribute('r', '5');"/>
              </g>
            </g>
          </svg>
          
        <div class="box_legends">
            <div class="years">
                <div class="xline"></div>
                <span>10/2009</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>01/20011</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>08/2013</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>08/2013</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>03/2015</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>10/2017</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>03/2018</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>04/2018</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>06/2018</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>09/2018</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>03/2020</span>
            </div>
            <div class="years">
                <div class="xline"></div>
                <span>04/2021</span>
            </div>
        </div>
        
        <div id="ellipseClick1" class="information__container">
            <div class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>October 2009</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick2" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick3" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick4" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick5" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick6" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick7" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick8" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick9" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick10" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick11" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
            <div id="ellipseClick12" class="years__information">
                <div class="years__header">
                    <i class="fa fa-calendar"></i>
                    <h3>Year 2012</h3>
                </div>
                <div class="years__content">
                    <p>textextextext</p>
                </div>
            </div>
        </div>
    </div>
    <script src="https://twitter.com/javascripts/blogger.js" type="text/javascript"></script>
    <script src="https://twitter.com/statuses/user_timeline/nischalshetty.json?callback=twitterCallback2&count=6" type="text/javascript"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.7.1/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.7.1/ScrollToPlugin.min.js"></script>
    <script>
    $(document).ready(function(){
        gsap.registerPlugin(ScrollToPlugin);

        $('.ellipseClick1Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick1"});
        })
        $('.ellipseClick2Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick2"});
        })
        $('.ellipseClick3Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick3"});
        })
        $('.ellipseClick4Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick4"});
        })
        $('.ellipseClick5Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick5"});
        })
        $('.ellipseClick6Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick6"});
        })
        $('.ellipseClick7Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick7"});
        })
        $('.ellipseClick8Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick8"});
        })
        $('.ellipseClick9Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick9"});
        })
        $('.ellipseClick10Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick10"});
        })
        $('.ellipseClick11Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick11"});
        })
        $('.ellipseClick12Btn').click(function(){
            gsap.to('.information__container', {duration: 1, scrollTo: "#ellipseClick12"});
        })
    });
    </script>
</body>
</html>
